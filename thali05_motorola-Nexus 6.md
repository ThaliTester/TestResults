#### Test 519863409bc5c94_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2743): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2743): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2743): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3202): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3202): CheckJNI is OFF
D/AndroidRuntime( 3202): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{3d2e80b4 token=Token{2a09a987 ActivityRecord{357575c6 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3202): Shutting down VM
I/MicrophoneInputStream( 1504): mic_close com.google.android.apps.gsa.speech.audio.u@2b6500c0
I/HotwordDetector( 1504): Closing mic
V/WindowManager(  822): Adding window Window{2325e1d9 u0 Starting com.test.thalitest} at 3 of 8 (after Window{2bd3c758 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/ActivityManager(  822): Start proc 3216:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1504): Hotword detection finished
I/HotwordRecognitionRnr( 1504): Stopping hotword detection.
I/ActivityManager(  822): Killing 2702:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659516179
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  822): Killing 2834:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/kickstart(  874): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  874): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  874): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  874): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3216): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3216): Time to load native libraries: 5 ms (timestamps 3063-3068)
I/LibraryLoader( 3216): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3216): Binding Chromium to main looper Looper (main, tid 1) {34001637}
,I/LibraryLoader( 3216): Expected native library version number "",actual native library version number ""
I/chromium( 3216): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3216): Initializing chromium process, singleProcess=true
,W/art     ( 3216): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3216): ApplicationContext is null in ApplicationStatus
,W/chromium( 3216): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3216): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 3216): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3216): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3216): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  822): Message: 20
,D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bb5f349:true
,D/BluetoothAdapter( 3216): 809805582: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3216): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3216): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3216): CordovaWebView is running on device made by: motorola
,W/art     ( 3216): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3216): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3216): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3216): Validating map...
,V/WindowManager(  822): Adding window Window{37e540b9 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{2325e1d9 u0 Starting com.test.thalitest})
,W/chromium( 3216): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3216): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3216): Enabling debug mode 0
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +886ms (total +1m50s785ms)
,I/Keyboard.Facilitator( 1213): onFinishInput()
,W/BindingManager( 3216): Cannot call determinedVisibility() - never saw a connection for the pid: 3216
,D/JsMessageQueue( 3216): Set native->JS mode to OnlineEventsBridgeMode
,I/kickstart(  874): STATUS: Received file 'm9kefs2'
I/kickstart(  874): STATUS: 950272 bytes transferred in 0.985946 seconds
I/kickstart(  874): STATUS: Successfully downloaded files from target 
I/kickstart(  874): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  874): STATUS: Sahara protocol completed
,D/jxcore_app_log( 3216): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576266880
,D/JX-Cordova( 3216): jxcore cordova android initializing
,W/jxcore-log( 3216): Initializing JXcore engine
W/jxcore-log( 3216): JXcore engine is ready
,W/jxcore-log( 3216): Starting JXcore engine
,W/.test.thalitest( 3216): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12857]" dev="sockfs" ino=12857 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3216): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3216): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9815]" dev="sockfs" ino=9815 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3216): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20838]" dev="sockfs" ino=20838 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3216): Platform android
W/jxcore-log( 3216): 
,W/jxcore-log( 3216): Process ARCH arm
W/jxcore-log( 3216): 
,I/jxcore-log( 3216): JXcore Cordova bridge is ready!,
I/jxcore-log( 3216): 
W/jxcore-log( 3216): JXcore engine is started
I/Choreographer( 3216): Skipped 139 frames!  The application may be doing too much work on its main thread.
I/chromium( 3216): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3216): Toggling radios to true
I/jxcore-log( 3216): 
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  822): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  822): Message: 1,
D/BluetoothManagerService(  822): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  822): New client listening to asynchronous messages
,D/WifiService(  822): setWifiEnabled: true pid=3216, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  822): Start proc 3272:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,I/jxcore-log( 3216): Radios toggled
I/jxcore-log( 3216): 
D/SoftapController(  354): Softap fwReload - Ok
,D/CommandListener(  354): Setting iface cfg
D/CommandListener(  354): Trying to bring down wlan0
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,E/WifiMonitor(  822): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/WifiMonitor(  822): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3289): Successfully initialized wpa_supplicant
,I/ActivityManager(  822): Start proc 3291:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,W/ResourcesManager( 3272): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3289): rfkill: Cannot open RFKILL control device
,I/art     (  822): Explicit concurrent mark sweep GC freed 17991(893KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.430ms total 64.852ms
,D/AdapterServiceConfig( 3272): Adding HeadsetService
D/AdapterServiceConfig( 3272): Adding A2dpService
D/AdapterServiceConfig( 3272): Adding HidService
D/AdapterServiceConfig( 3272): Adding HealthService
D/AdapterServiceConfig( 3272): Adding PanService
D/AdapterServiceConfig( 3272): Adding GattService
D/AdapterServiceConfig( 3272): Adding BluetoothMapService
,D/BluetoothManagerService(  822): Message: 20
,D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1836f162:true
D/BluetoothAdapterState( 3272): make
,I/bluedroid( 3272): init
,I/BluetoothAdapterState( 3272): Entering OffState
,I/bte_conf( 3272): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3272): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3272): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3272): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3272): get_profile_interface socket
I/bluedroid( 3272): get_profile_interface map_client
I/GKI_LINUX( 3272): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3272): Address is:F8:CF:C5:D9:E5:61
D/BluetoothAdapterProperties( 3272): Name is: Nexus 6
D/BluetoothManagerService(  822): Bluetooth Adapter name changed to Nexus 6
,D/BluetoothManagerService(  822): Stored Bluetooth name: Nexus 6
,D/BluetoothManagerService(  822): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  822): Message: 40
,D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3272): config_hci_snoop_log,
,D/BluetoothManagerService(  822): Calling onBluetoothServiceUp callbacks,
D/BluetoothManagerService(  822): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3272): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON,
D/BluetoothAdapterProperties( 3272): Setting state to 11
I/BluetoothAdapterState( 3272): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  822): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3272): make
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,I/ActivityManager(  822): Start proc 3323:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  822): Killing 2868:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/art     (  369): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 1.188ms total 9.872ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 196us total 8.873ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 317us total 13.446ms
,I/BluetoothAdapterState( 3272): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/HeadsetService( 3272): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3272): classInitNative: succeeds
D/HeadsetStateMachine( 3272): make
,D/HeadsetStateMachine( 3272): max_hf_connections = 1
I/bluedroid( 3272): get_profile_interface handsfree
,D/HeadsetStateMachine( 3272): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/BluetoothA2dp(  822): Proxy object connected
D/A2dpService( 3272): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3272): classInitNative: succeeds
I/bluedroid( 3272): get_profile_interface avrcp
,E/RemoteController( 3272): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3272): classInitNative: succeeds
D/A2dpStateMachine( 3272): make
I/bluedroid( 3272): get_profile_interface a2dp
I/GKI_LINUX( 3272): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3272): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3272): classInitNative: succeeds
D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/BluetoothA2dp( 1065): Proxy object connected
,D/HidService( 3272): Received start request. Starting profile...
I/bluedroid( 3272): get_profile_interface hidhost
D/BluetoothInputDevice( 1065): Proxy object connected
I/BluetoothHealthServiceJni( 3272): classInitNative: succeeds
D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/HealthService( 3272): Received start request. Starting profile...
I/bluedroid( 3272): get_profile_interface health
,I/BluetoothPanServiceJni( 3272): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/PanService( 3272): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3272): initializeNative(L110): pan
I/bluedroid( 3272): get_profile_interface pan
I/BtGatt.JNI( 3272): classInitNative(L873): classInitNative: Success!
D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
D/BtGatt.DebugUtils( 3272): handleDebugAction() action=null
,D/BtGatt.GattService( 3272): Received start request. Starting profile...
D/BtGatt.GattService( 3272): start()
I/bluedroid( 3272): get_profile_interface gatt
D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
D/BtGatt.AdvertiseManager( 3272): advertise manager created
D/BluetoothPan( 1065): BluetoothPAN Proxy object connected
,D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/BluetoothMapService( 3272): Received start request. Starting profile...
D/BluetoothMapService( 3272): start()
D/BluetoothMap( 1065): Proxy object connected
,D/BluetoothMapEmailSettingsLoader( 3272): Found 0 applications
D/BluetoothMapEmailAppObserver( 3272): createReceiver()
D/BluetoothMapEmailAppObserver( 3272): initObservers()
D/BluetoothMapEmailAppObserver( 3272): getEnabledAccountItems()
,D/HeadsetStateMachine( 3272): Proxy object connected
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3272): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3272): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3272): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3272): enable
I/bt_hci_bdroid( 3272): init
I/GKI_LINUX( 3272): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3272): btu_task pending for preload complete event
,I/bt_vendor( 3272): init
I/bt_vnd_conf( 3272): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3272): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3272): userial_init
,I/art     ( 1528): Explicit concurrent mark sweep GC freed 23764(1257KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 960us total 20.862ms
,D/Tethering(  822): sendTetherStateChangedBroadcast 1, 0, 0
,I/bt_userial_vendor( 3272): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3272): device fd = 53 open
D/bt_userial( 3272): Entering userial_read_thread()
,I/bt_hwcfg( 3272): bt vendor lib: set UART baud 3000000
,I/ActivityManager(  822): Start proc 3360:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,D/bt_hwcfg( 3272): Chipset BCM4354A2
D/bt_hwcfg( 3272): Target name = [BCM4354A2]
I/bt_hwcfg( 3272): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,I/ActivityManager(  822): Killing 2803:com.google.android.gm/u0a78 (adj 15): empty #17
,I/wpa_supplicant( 3289): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3289): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  822): Loading config and enabling all networks 
,E/WifiConfigStore(  822): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1a24ae1a}
,W/Settings( 2656): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  822): Setting external_sim to 1
D/WifiStateMachine(  822): Setting OUI to 92-68-C3
I/WifiNative-HAL(  822): startHal
D/wifi    (  822): setting scan oui 0xa0b4ee08
,D/WifiHAL (  822): Sending mac address OUI
,E/WifiStateMachine(  822): cancelDelayedScan -> 1
,D/WifiScanningService(  822): SCAN_AVAILABLE : 3
D/RttService(  822): SCAN_AVAILABLE : 3
D/RttService(  822): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  822): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  822): startHal
W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
,D/wifi    (  822): getting scan capabilities on interface[0] = 0xa0b4ee08
D/WifiHAL (  822): Creating message to get scan capablities; iface = 5
D/WifiHAL (  822): In GetCapabilities::handleResponse
D/WifiHAL (  822): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  822): StartedState
D/CommandListener(  354): Setting iface cfg
,E/WifiP2pService(  822): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  822): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 3289): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN,
,E/native  (  822): do suspend false,
,D/WifiNative-HAL(  822): p2pGetDeviceAddress,
,D/WifiNative-HAL(  822): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
I/ActivityManager(  822): Killing 2354:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 3378:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,I/bt_hwcfg( 3272): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3272): Settlement delay -- 100 ms
I/bt_hwcfg( 3272): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3272): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3272): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3272): vendor lib fwcfg completed
I/bt-btu  ( 3272): btu_task received preload complete event
D/StrictMode( 3378): StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3378): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3378): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3378): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3378): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3378): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3378): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3378): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3378): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3378): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3378): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3378): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3378): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3378): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3378): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3378): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3378): StrictMode policy violation; ~duration=182 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3378): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3378): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3378): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3378): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3378): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3378): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3378): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3378): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3378): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3378): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3378): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3378): StrictMode policy violation; ~duration=180 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3378): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3378): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3378): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3378): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3378): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3378): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3378): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3378): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3378): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3378): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3378): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3378): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3378): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3378): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3378): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3378): StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
D/StrictMode( 3378): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3378): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3378): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3378): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3378): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3378): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3378): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
,D/StrictMode( 3378): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3378): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3378): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3378): StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
D/StrictMode( 3378): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3378): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3378): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3378): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3378): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3378): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3378): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3378): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3378): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3378): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3378): 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3378): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3378): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3378): StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3378): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3378): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3378): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3378): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3378): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3378): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
,D/StrictMode( 3378): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3378): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3378): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3378): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3378): # via Binder call with stack:
D/StrictMode( 3378): android.os.StrictMode$LogStackTrace
D/StrictMode( 3378): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3378): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3378): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3378): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3378): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3378): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3378): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3378): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3378): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3378): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3378): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3378): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3378): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3378): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3378): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3378): StrictMode policy violation; ~duration=42 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3378): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3378): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3378): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3378): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3378): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3378): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3378): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3378): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3378): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3378): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3378): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3378): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3378): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3378): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3378): 	,at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3378): StrictMode policy violation; ~duration=41 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3378): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3378): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3378): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3378): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3378): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3378): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3378): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3378): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3378): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3378): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3378): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3378): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3378): StrictMode policy violation; ~duration=41 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3378): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3378): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3378): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3378): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3378): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3378): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3378): 	,at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3378): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3378): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3378): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3378): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3378): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3378): StrictMode policy violation; ~duration=40 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3378): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3378): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3378): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3378): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3378): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3378): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3378): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3378): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3378): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3378): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3378): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3378): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3378): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3378): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3378): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3378): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3378): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3378): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3378): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3378): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,I/        ( 3272): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3272): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3272): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3272): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3272): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3272): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3272): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3272): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3272): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3272): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3272): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3272): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3272): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3272): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3272): BTE_InitTraceLevels -- TRC_BTIF
W/com.google.a.a.a.b.a( 3378): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  822): Message: 20
,D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31f2e672:true
,I/ActivityManager(  822): Killing 2905:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1528): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/bt-btm  ( 3272): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2dac085 
E/bt-btm  ( 3272): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2dac085 
,D/BluetoothAdapterProperties( 3272): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3272): Calling BTA_HhEnable,
,E/bt-btif ( 3272): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3272): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothAdapterProperties( 3272): Name is: Nexus 6
D/BluetoothManagerService(  822): Bluetooth Adapter name changed to Nexus 6
,D/BluetoothManagerService(  822): Stored Bluetooth name: Nexus 6
D/BluetoothAdapterProperties( 3272): Scan Mode:20
,D/BluetoothAdapterProperties( 3272): Discoverable Timeout:120
,D/bte_conf( 3272): Device ID record 1 : primary,
D/bte_conf( 3272):   vendorId            = 000f
,D/bte_conf( 3272):   vendorIdSource      = 0001
D/bte_conf( 3272):   product             = 1200
,D/bte_conf( 3272):   version             = 1436
D/bte_conf( 3272):   clientExecutableURL = 
,D/bte_conf( 3272):   serviceDescription  = 
D/bte_conf( 3272):   documentationURL    = 
D/bte_conf( 3272): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3272): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3272): ScanMode =  20
D/BluetoothAdapterProperties( 3272): State =  11
D/BluetoothPanServiceJni( 3272): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 3272): Setting state to 12
I/BluetoothAdapterState( 3272): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  822): Broadcasting onBluetoothStateChange(true) to 13 receivers.
D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3272): Entering On State
,D/BluetoothAdapterProperties( 3272): Scan Mode:21
D/BluetoothAdapterProperties( 3272): Discoverable Timeout:120
D/BluetoothManagerService(  822): Creating new ProfileServiceConnections object for profile: 1
D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 1065): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1065): onBluetoothStateChange: up=true
D/BluetoothMap( 1065): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1065): onBluetoothStateChange: up=true
D/BluetoothHeadsetClient( 1065): onBluetoothStateChange: up=true
E/BluetoothHeadsetClient( 1065): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
,D/BluetoothPan( 1065): onBluetoothStateChange(on) call bindService
,W/bt-btm  ( 3272): Stopping oneshot timer
,E/bt_h4   ( 3272): vendor lib postload completed
,D/BluetoothA2dpSink( 1065): onBluetoothStateChange: up=true,
E/BluetoothA2dpSink( 1065): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
D/BluetoothAvrcpController( 1065): onBluetoothStateChange: up=true
,E/BluetoothAvrcpController( 1065): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1279): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  822): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  822): Bluetooth State Change Intent: 11 -> 12
,W/bt-btm  ( 3272): Stopping oneshot timer
,W/bt-btm  ( 3272): Stopping oneshot timer
,D/BluetoothMapService( 3272): onReceive
D/BluetoothMapService( 3272): STATE_ON
D/BluetoothManagerService(  822): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  822): Message: 40
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,W/bt-btm  ( 3272): Stopping oneshot timer
,D/BluetoothMapMasInstance( 3272): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3272): MAS initSocket()
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/bt-btm  ( 3272): Stopping oneshot timer
,W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3272): Accepting socket connection...
,W/ContextImpl( 3360): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/bt-btm  ( 3272): Stopping oneshot timer
,W/bt-btm  ( 3272): Stopping oneshot timer
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@142b6417:true
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1528): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset(  822): Proxy object connected
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  822): Message: 400
D/BluetoothHeadset(  822): Proxy object connected
,D/LocalBluetoothProfileManager( 3360): Adding local A2DP profile
,D/BluetoothManagerService(  822): Message: 30
I/BtOppRfcommListener( 3272): Accept thread started.
D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset( 1065): Proxy object connected
,D/LocalBluetoothProfileManager( 3360): Adding local HEADSET profile
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 400
D/LocalBluetoothProfileManager( 3360): Adding local MAP profile
D/BluetoothHeadset(  822): Proxy object connected
D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset( 1279): Proxy object connected
,D/BluetoothMap( 3360): Create BluetoothMap proxy object
D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30,
,D/LocalBluetoothProfileManager( 3360): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3360): finishStartingService: stopping service
,D/BluetoothA2dp( 3360): Proxy object connected
,D/A2dpProfile( 3360): Bluetooth service connected
,D/BluetoothInputDevice( 3360): Proxy object connected
D/HidProfile( 3360): Bluetooth service connected
,D/BluetoothPan( 3360): BluetoothPAN Proxy object connected
D/PanProfile( 3360): Bluetooth service connected
D/BluetoothMap( 3360): Proxy object connected
D/MapProfile( 3360): Bluetooth service connected
,D/BluetoothMap( 3360): getConnectedDevices()
,D/BluetoothPbap( 3360): Proxy object connected
,D/PbapServerProfile( 3360): Bluetooth service connected
,D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset( 3360): Proxy object connected
,D/HeadsetProfile( 3360): Bluetooth service connected,
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/jxcore-log( 3216): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): my name is : motorola-Nexus 6_PT4432
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): attempting to connect to test coordinator
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): check test folder
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found test : ./testFindPeers.js
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found test : ./testReConnect.js
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found test : ./testSendData.js
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Test app app.js loaded
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): ,
I/Choreographer( 3216): Skipped 126 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3216): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3289): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  822):  rewrite network history for "NG700"WPA_PSK
,E/WifiConfigStore(  822):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  822): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,I/wpa_supplicant( 3289): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3289): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3289): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3289): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  822): Start Dhcp Watchdog 1
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 1
E/WifiStateMachine(  822):  RSSI mgmt: -44
E/WifiStateMachine(  822):  BE :  rx=0 tx=4 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 0 tx_time=58 rx_time=113 scan_time=0
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60,
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3216): 
,E/native  (  822): do suspend false,
,E/WifiStateMachine(  822): scanCount==0 - aborting,
,I/dhcpcd  ( 3420): version 5.5.6 starting
,I/dhcpcd  ( 3420): wlan0: rebinding lease of 192.168.1.110
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/dhcpcd  ( 3420): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 3420): wlan0: leased 192.168.1.110 for 86400 seconds
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  822): Adding iface wlan0 to network 100
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  822): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  822):    accepting network in place of null
,D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  822): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,V/BackupManagerService(  822): Scheduling immediate backup pass
,D/PhoneInterfaceManager( 1279): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1279): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,I/ActivityManager(  822): Start proc 3458:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,V/BackupManagerService(  822): Running a backup pass
,V/BackupManagerService(  822): clearing pending backups
,E/GpsLocationProvider(  822): No APN found to select.
,D/NetworkChangeNotifierAutoDetect( 1504): Network connectivity changed, type is: 2
,V/PerformBackupTask(  822): Beginning backup of 14 targets
,D/AlarmManagerService(  822): Setting time of day to sec=1448880691
W/AlarmManagerService(  822): Unable to set rtc to 1448880691: Invalid argument
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 30 Nov 2015 10:51:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448880691110], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448880691157]}
,D/PerformBackupTask(  822): invokeAgentForBackup on @pm@
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Validated
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION,
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
,V/BackupServiceBinder(  822): doBackup() invoked
,D/GpsLocationProvider(  822): NTP server returned: 1448880691102 (Mon Nov 30 11:51:31 GMT+01:00 2015) reference: 152420 certainty: 21 system time offset: -58
,I/PMBA    (  822): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/MusicStore( 3458): Database version: 120
I/BackupRestoreController(  822): Getting widget state for user: 0
,W/GmsBackupTransport( 1752): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1752): starting performBackup for @pm@
,V/GmsBackupTransport( 1752): performBackup done for @pm@
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1781): [CredentialSyncAdapter] Unknown sync event.
,W/GLSActivity( 1528): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1528): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1528): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1528): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1528): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1528): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1528): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/BackupManagerService(  822): Now staging backup of com.google.android.talk
,D/BackupManagerService(  822): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  822): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  822): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  822): Now staging backup of com.google.android.gm
,W/ResourcesManager( 3458): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3458): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BackupManagerService(  822): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  822): Now staging backup of com.android.nfc
,D/BackupManagerService(  822): Now staging backup of com.google.android.apps.genie.geniewidget
,I/art     ( 1528): Explicit concurrent mark sweep GC freed 8600(442KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 2.908ms total 32.757ms
D/BackupManagerService(  822): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  822): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  822): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  822): Now staging backup of com.android.vending
,W/DriveInitializer( 1781): Background init thread started
,D/BackupManagerService(  822): Now staging backup of android
,D/BackupManagerService(  822): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1752): Next backup will happen in 43199946 millis.
,I/BackupManagerService(  822): Backup pass finished.
V/JNIHelp ( 3458): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3458): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 3458): GMSCore installation verified
,I/art     (  822): Explicit concurrent mark sweep GC freed 48405(2MB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.597ms total 106.136ms
,I/ConfigStore( 3458): Config Database version: 1
,W/DriveInitializer( 1781): Background init thread ended
,I/MediaRouter( 3458): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3458): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 3458): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 3458): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  822): Start proc 3517:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/GHttpClientFactory( 3458): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3458): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SprintDMReceiver( 3517): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3517): simOperator:  IMSI: null
D/SprintDMReceiver( 3517): Not Sprint UICC, don't do anything.
,I/ActivityManager(  822): Start proc 3535:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/SystemUpdateService( 1781): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1781): onCreate
,D/SystemUpdateService( 1781): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/HttpOperation( 2989): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): 	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at blb.a(PG:3937)
E/HttpOperation( 2989): 	at czp.a(PG:18188)
E/HttpOperation( 2989): 	at czp.a(PG:9081)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125)
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 12 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089)
E/HttpOperation( 2989): 	... 14 more
,I/SystemUpdateService( 1781): active receiver: enabled
,I/SystemUpdateService( 1781): showing system update notification
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  822): skipping global notification
,I/iu.SyncManager( 1781): SYNC; picasa accounts
,E/HttpOperation( 2989): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): 	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at hec.a(PG:42)
E/HttpOperation( 2989): 	at hee.a(PG:102)
E/HttpOperation( 2989): 	at czr.a(PG:65)
E/HttpOperation( 2989): 	at kka.a(PG:108)
E/HttpOperation( 2989): 	at czp.a(PG:19176)
E/HttpOperation( 2989): 	at czp.a(PG:9081)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125)
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 15 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089)
E/HttpOperation( 2989): 	... 17 more
,E/ExperimentLoader( 2989): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2989): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2989): 	at jdm.a(PG:82)
E/ExperimentLoader( 2989): 	at jcs.o(PG:406)
E/ExperimentLoader( 2989): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2989): 	at jcs.i(PG:143)
E/ExperimentLoader( 2989): 	at hec.a(PG:42)
E/ExperimentLoader( 2989): 	at hee.a(PG:102)
E/ExperimentLoader( 2989): 	at czr.a(PG:65)
E/ExperimentLoader( 2989): 	at kka.a(PG:108)
E/ExperimentLoader( 2989): 	at czp.a(PG:19176)
E/ExperimentLoader( 2989): 	at czp.a(PG:9081)
E/ExperimentLoader( 2989): 	at czq.run(PG:1686)
E/ExperimentLoader( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/ExperimentLoader( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2989): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2989): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2989): 	at jdm.a(PG:77)
E/ExperimentLoader( 2989): 	... 15 more
E/ExperimentLoader( 2989): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2989): 	at fal.a(PG:38)
E/ExperimentLoader( 2989): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2989): 	... 17 more
V/SystemUpdateService( 1781): retry (wakeup: false) in 3599950 ms
,D/NetworkLogImpl( 1781): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1781): num queued entries: 0
,I/iu.UploadsManager( 1781): num updated entries: 0
,I/iu.SyncManager( 1781): NEXT; no task
,D/SystemUpdateService( 1781): onDestroy
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  822): Start proc 3566:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/Babel   ( 2656): connection state changed from DISCONNECTED to CONNECTED
,I/ActivityManager(  822): Killing 2204:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 36212, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/GCM     ( 1528): Connected
,I/GCM     ( 1528): Ack for not saved message 81
D/GCM     ( 1528): Message class com.google.f.a.a.p
,I/GAv4    ( 3566): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3566):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3566):   adb logcat -s GAv4
,W/GAv4    ( 3566): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3566): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3566): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 3216): BLE advertisement not supported: Not supported
I/jxcore-log( 3216): 
,V/KeepSync( 3323): Connecting to GoogleApiClient
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,W/GAV2    ( 3535): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,I/BooksApp( 3535): Created application version: 3.6.8 (30608)
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 3566): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3566): Time to load native libraries: 1 ms (timestamps 3516-3517)
I/LibraryLoader( 3566): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3566): Binding Chromium to main looper Looper (main, tid 1) {315168b8}
,I/LibraryLoader( 3566): Expected native library version number "",actual native library version number ""
I/chromium( 3566): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/art     ( 1528): Explicit concurrent mark sweep GC freed 14708(945KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 26MB/42MB, paused 739us total 20.177ms
,I/BrowserStartupController( 3566): Initializing chromium process, singleProcess=true
,W/art     ( 3566): Attempt to remove local handle scope entry from IRT, ignoring
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
,E/SysUtils( 3566): ApplicationContext is null in ApplicationStatus
,V/KeepSync( 3323): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,W/chromium( 3566): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3566): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3566): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3566): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/BooksSync( 3535): Starting books sync for 61035162, extras: ade
,W/AudioManagerAndroid( 3566): Requires BLUETOOTH permission
,I/NSApplication( 3566): Starting up...
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 25751(1183KB) AllocSpace objects, 4(105KB) LOS objects, 32% free, 33MB/49MB, paused 1.445ms total 48.165ms
,E/KeepSync( 3323): IOException
E/KeepSync( 3323): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3323): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3323): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3323): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3323): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3323): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3323): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3323): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3323): 	... 10 more
W/KeepSync( 3323): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 36214, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Start proc 3641:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  822): Killing 2436:android.process.acore/u0a5 (adj 15): empty #17
,I/BooksConfig( 3535): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3535): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3535): Soft error
E/BooksSync( 3535): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3535): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3535): Sync error
E/BooksSync( 3535): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3535): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3535): Finished books sync
,I/ActivityManager(  822): Killing 3098:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 36214, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Killing 3121:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  822): Killing 1808:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1a24ae1a}
,I/ActivityManager(  822): Start proc 3662:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,V/Herrevad( 1781): NQAS connected
,D/WifiService(  822): New client listening to asynchronous messages
,E/SQLiteLog( 3662): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/art     ( 1781): Explicit concurrent mark sweep GC freed 13883(1101KB) AllocSpace objects, 16(256KB) LOS objects, 35% free, 28MB/44MB, paused 1.188ms total 48.467ms
,I/ActivityManager(  822): Start proc 3684:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 3684): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3684): Created com.android.providers.calendar.CalendarAlarmManager@4a3e736(com.android.providers.calendar.CalendarProvider2@34001637)
,I/ActivityManager(  822): Start proc 3707:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3662): PlayLogger.onLoggerConnected
,D/TimeService( 3707): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448880693838
,D/        ( 3707): TimeServiceNative: User Time to be set is 1448880693838
D/QC-time-services( 3707): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3707): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3707): Lib:time_genoff_operation: pargs->ts_val = 1448880693838
D/QC-time-services( 3707): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  373): Daemon: Connection accepted:time_genoff
D/QC-time-services(  373): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448880693838
D/QC-time-services(  373): Daemon:genoff_opr: Base = 2, val = 1448880693838, operation = 0
D/QC-time-services(  373): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/17/70 7:4:32
D/QC-time-services(  373): Daemon:Value read from RTC seconds = 9183872000
D/QC-time-services(  373): Daemon:new time 1448880693838 
D/QC-time-services(  373): Daemon: delta 1439696821838 genoff 1439696821838 
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696821838 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  373): Updating the TOD offset
,D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696821838 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  373): Daemon:Update to modem bit set
D/QC-time-services(  373): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  373): Daemon: Base = 2, Value being sent to MODEM = 1132915893838
,E/QC-time-services( 3707): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/ActivityManager(  822): Killing 3149:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,E/QC-time-services(  373): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  373): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40,
,I/ActivityManager(  822): Start proc 3727:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 239us total 19.488ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 580us total 21.365ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 445us total 16.148ms
,I/GAv4    ( 3727): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3727):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3727):   adb logcat -s GAv4
,W/GAv4    ( 3727): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3727): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3727): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2656): UserRecoverableAuthException.
,E/Babel   ( 2656): eei: BadAuthentication
E/Babel   ( 2656): 	at eeg.a(Unknown Source)
E/Babel   ( 2656): 	at eeg.a(Unknown Source)
E/Babel   ( 2656): 	at eeg.a(Unknown Source)
E/Babel   ( 2656): 	at g.a(Unknown Source)
E/Babel   ( 2656): 	at cae.a(SourceFile:3089)
E/Babel   ( 2656): 	at cae.a(SourceFile:1131)
E/Babel   ( 2656): 	at cws.a(SourceFile:4333)
E/Babel   ( 2656): 	at cws.a(SourceFile:1419)
E/Babel   ( 2656): 	at crl.a(SourceFile:492)
E/Babel   ( 2656): 	at crl.a(SourceFile:1468)
E/Babel   ( 2656): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2656): 	at cas.b(SourceFile:106)
E/Babel   ( 2656): 	at cap.d(SourceFile:335)
E/Babel   ( 2656): 	at caq.run(SourceFile:81)
E/Babel   ( 2656): Error getting auth token
E/Babel   ( 2656): dvm
E/Babel   ( 2656): 	at g.a(Unknown Source)
E/Babel   ( 2656): 	at cae.a(SourceFile:3089)
E/Babel   ( 2656): 	at cae.a(SourceFile:1131)
E/Babel   ( 2656): 	at cws.a(SourceFile:4333)
E/Babel   ( 2656): 	at cws.a(SourceFile:1419)
E/Babel   ( 2656): 	at crl.a(SourceFile:492)
E/Babel   ( 2656): 	at crl.a(SourceFile:1468)
E/Babel   ( 2656): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2656): 	at cas.b(SourceFile:106)
E/Babel   ( 2656): 	at cap.d(SourceFile:335)
E/Babel   ( 2656): 	at caq.run(SourceFile:81)
,E/Babel   ( 2656): Account registration failed 1-Redacted-21,
E/Babel   ( 2656): cyp: null -- null
E/Babel   ( 2656): 	at cae.a(SourceFile:3121)
E/Babel   ( 2656): 	at cae.a(SourceFile:1131)
E/Babel   ( 2656): 	at cws.a(SourceFile:4333)
E/Babel   ( 2656): 	at cws.a(SourceFile:1419)
E/Babel   ( 2656): 	at crl.a(SourceFile:492)
E/Babel   ( 2656): 	at crl.a(SourceFile:1468)
E/Babel   ( 2656): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2656): 	at cas.b(SourceFile:106)
E/Babel   ( 2656): 	at cap.d(SourceFile:335)
E/Babel   ( 2656): 	at caq.run(SourceFile:81)
,I/art     ( 2656): Note: end time exceeds epoch: 
,I/art     (  822): Explicit concurrent mark sweep GC freed 16883(717KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 1.419ms total 82.375ms
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1528): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2656): Unexpected exception while authenticating.
E/Babel   ( 2656): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2656): 	at eeg.b(Unknown Source)
E/Babel   ( 2656): 	at eeg.b(Unknown Source)
E/Babel   ( 2656): 	at g.a(Unknown Source)
E/Babel   ( 2656): 	at cae.b(SourceFile:1146)
E/Babel   ( 2656): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2656): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2656): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2656): 	at java.lang.Thread.run(Thread.java:818)
,I/CalendarProvider2( 3684): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3684): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=34.38 rxSuccessRate=33.31 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,E/SQLiteLog( 3684): (284) automatic index on view_events(_id)
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=34.38 rxSuccessRate=33.31 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,I/ActivityManager(  822): Start proc 3773:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,I/MusicLeanback( 3458): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3458): Stop autocaching.
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3773): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3773): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3773): VM with version 2.1.0 has multidex support
I/MultiDex( 3773): install
,I/MultiDex( 3773): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3773): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3773): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1528): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1528): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1781): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3773): callingUid 10011, callindPid: 3773
,D/LocationInitializer( 1781): Restart initialization of location
,E/MDM     ( 1752): [135] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3458): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3458): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GAV2    ( 3535): Thread[GAThread,5,main]: No campaign data found.
I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/GAV2    ( 3662): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  822): Killing 3056:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/ActivityManager(  822): Killing 2743:com.android.vending/u0a19 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 3809:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (180 us)
,D/Finsky  ( 3809): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3809): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  822): Start proc 3846:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 3809): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3809): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 3846): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3846): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3846): VM with version 2.1.0 has multidex support
I/MultiDex( 3846): install
I/MultiDex( 3846): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3846): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 3809): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3809): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 3809): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3809): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ProviderInstaller( 3846): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1528): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1528): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 1781): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1752): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1781): Restart initialization of location
,I/art     ( 1528): Explicit concurrent mark sweep GC freed 21597(1199KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.631ms total 46.527ms
,V/Finsky  ( 3809): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3809): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3809): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3809): [1] 5.onFinished: Scheduling replication attempt 4.
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  822): Display changed displayId=0
,I/ActivityManager(  822): Killing 3378:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3360:com.android.settings/1000 (adj 15): empty #18
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0,
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 266ms
,I/DreamManagerService(  822): Entering dreamland.
I/PowerManagerService(  822): Dozing...
I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 5
,E/native  (  822): do suspend false
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@361e8b50}
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=4.92 rxSuccessRate=5.16 targetRoamBSSID=any RSSI=-44
,I/Keyboard.Facilitator( 1213): onFinishInput()
,E/WifiStateMachine(  822): cancelDelayedScan -> 7
,E/native  (  822): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,D/Finsky  ( 3809): [394] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3809): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3809): [394] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/art     (  822): Explicit concurrent mark sweep GC freed 23529(1147KB) AllocSpace objects, 2(220KB) LOS objects, 32% free, 33MB/49MB, paused 1.454ms total 86.685ms
,W/Finsky  ( 3809): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3809): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3809): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 3809): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3809): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3809): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1752): client connected with version: 7571000,
,I/GoogleURLConnFactory( 1752): Using platform SSLCertificateSocketFactory
,W/GoogleHttpClient( 1752): Ignoring unsupported parameter: http.conn-manager.max-per-route,
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@361e8b50}
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/ActivityManager(  822): Killing 1504:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  822): Client connection lost with reason: 4
,I/ActivityManager(  822): Killing 3517:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.50 rxSuccessRate=1.00 targetRoamBSSID=any RSSI=-44
,E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 4, 7 -> obsolete
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3291): [336] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1528): Vacuum at: now=1448880711569 tag=VacuumService
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3291): [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3291): [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3291): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3291): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3291): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1528): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1528): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1528): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1528): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1528): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1528): No account for auth token provided
,W/Uploader( 1528): No account for auth token provided
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,W/Uploader( 1528): No account for auth token provided
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1528): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1528): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1528): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1528): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1528): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1528): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1528): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1528): 	,at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1528): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1528): No account for auth token provided
,W/Uploader( 1528): No account for auth token provided
,W/Uploader( 1528): No account for auth token provided
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1528): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1528): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1528): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1528): 	,at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.b(SourceFile:477),
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1528): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125),
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1528): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1528): No account for auth token provided
,W/Uploader( 1528): No account for auth token provided
,W/Uploader( 1528): No account for auth token provided
,W/Uploader( 1528):  no longer exists, so no auth token.
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1528): Explicit concurrent mark sweep GC freed 59711(3MB) AllocSpace objects, 11(1062KB) LOS objects, 37% free, 27MB/43MB, paused 1.892ms total 68.959ms
,E/Uploader( 1528): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1528): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1528): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1528): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1528): No account for auth token provided
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1528): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1528): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1528): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1528): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1528): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1528): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1528): No account for auth token provided
,W/Uploader( 1528): No account for auth token provided
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3809): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3809): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3809): [1] 5.onFinished: Scheduling replication attempt 5.
,I/art     (  822): Explicit concurrent mark sweep GC freed 25630(1220KB) AllocSpace objects, 5(174KB) LOS objects, 31% free, 34MB/50MB, paused 1.776ms total 93.256ms,
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,V/GoogleAuthProtoRequest( 3291): [337] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3291): [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3291): [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3291): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3291): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3291): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3809): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3809): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3809): [1] 5.onFinished: Giving up after 6 failures.
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,V/KeepSync( 3323): Connecting to GoogleApiClient
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2989): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): 	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at blb.a(PG:3937)
E/HttpOperation( 2989): 	at czp.a(PG:18188)
E/HttpOperation( 2989): 	at czp.a(PG:9087)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125)
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 12 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089)
E/HttpOperation( 2989): 	... 14 more
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3323): GoogleApiClient failed to connect with error code: 4,
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2989): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): 	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at blb.a(PG:3937)
E/HttpOperation( 2989): 	at czp.a(PG:18188)
E/HttpOperation( 2989): 	at czp.a(PG:9081)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125)
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 12 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089)
E/HttpOperation( 2989): 	... 14 more
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2989): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): 	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at hec.a(PG:42)
E/HttpOperation( 2989): 	at hee.a(PG:102)
E/HttpOperation( 2989): 	at czr.a(PG:65)
E/HttpOperation( 2989): 	at kka.a(PG:108)
E/HttpOperation( 2989): 	at czp.a(PG:19176)
E/HttpOperation( 2989): 	at czp.a(PG:9081)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125)
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 15 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089)
E/HttpOperation( 2989): 	... 17 more
,E/ExperimentLoader( 2989): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2989): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2989): 	at jdm.a(PG:82)
E/ExperimentLoader( 2989): 	at jcs.o(PG:406)
E/ExperimentLoader( 2989): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2989): 	at jcs.i(PG:143)
E/ExperimentLoader( 2989): 	at hec.a(PG:42)
E/ExperimentLoader( 2989): 	at hee.a(PG:102)
E/ExperimentLoader( 2989): 	at czr.a(PG:65)
,E/ExperimentLoader( 2989): 	at kka.a(PG:108)
E/ExperimentLoader( 2989): 	at czp.a(PG:19176)
E/ExperimentLoader( 2989): 	at czp.a(PG:9081)
E/ExperimentLoader( 2989): 	at czq.run(PG:1686)
E/ExperimentLoader( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2989): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2989): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2989): 	at jdm.a(PG:77)
E/ExperimentLoader( 2989): 	... 15 more
,E/ExperimentLoader( 2989): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2989): 	at fal.a(PG:38)
E/ExperimentLoader( 2989): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2989): 	... 17 more
,E/KeepSync( 3323): IOException
E/KeepSync( 3323): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3323): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3323): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3323): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3323): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3323): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3323): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3323): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3323): 	... 10 more
W/KeepSync( 3323): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 185624, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3535): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3535): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 153229, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3535): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3535): Soft error
E/BooksSync( 3535): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3535): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3535): Sync error
E/BooksSync( 3535): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3535): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3535): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 186150, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1213): run()
I/Keyboard.Facilitator( 1213): flushDynamicLanguageModels()
,I/ConfigService( 1528): onCreate
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/ConfigService( 1528): onDestroy,
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3216): 
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2989): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): 	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at blb.a(PG:3937)
E/HttpOperation( 2989): 	at czp.a(PG:18188)
E/HttpOperation( 2989): 	at czp.a(PG:9081)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125)
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 12 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089)
E/HttpOperation( 2989): 	... 14 more
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2989): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): 	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at hec.a(PG:42)
E/HttpOperation( 2989): 	at hee.a(PG:102)
E/HttpOperation( 2989): 	at czr.a(PG:65)
E/HttpOperation( 2989): 	at kka.a(PG:108)
E/HttpOperation( 2989): 	at czp.a(PG:19176)
E/HttpOperation( 2989): 	at czp.a(PG:9081)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125)
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 15 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089)
E/HttpOperation( 2989): 	... 17 more
E/ExperimentLoader( 2989): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2989): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2989): 	at jdm.a(PG:82)
E/ExperimentLoader( 2989): 	at jcs.o(PG:406)
E/ExperimentLoader( 2989): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2989): 	at jcs.i(PG:143)
E/ExperimentLoader( 2989): 	at hec.a(PG:42)
E/ExperimentLoader( 2989): 	at hee.a(PG:102)
E/ExperimentLoader( 2989): 	at czr.a(PG:65)
E/ExperimentLoader( 2989): 	at kka.a(PG:108)
E/ExperimentLoader( 2989): 	at czp.a(PG:19176)
E/ExperimentLoader( 2989): 	at czp.a(PG:9081)
E/ExperimentLoader( 2989): 	at czq.run(PG:1686)
E/ExperimentLoader( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2989): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2989): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2989): 	at jdm.a(PG:77)
E/ExperimentLoader( 2989): 	... 15 more
E/ExperimentLoader( 2989): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2989): 	at fal.a(PG:38)
E/ExperimentLoader( 2989): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2989): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 245546, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,V/GoogleAuthProtoRequest( 3291): [338] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 36320(1595KB) AllocSpace objects, 11(741KB) LOS objects, 32% free, 33MB/49MB, paused 1.518ms total 72.821ms
,W/ExperimentUpdateService( 3291): [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3291): [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3291): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3291): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3291): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Coordinator is now connected to the server!
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/BooksSync( 3535): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3535): GmsCore Version = 7.8.99 (2134222-430)
,I/art     ( 1528): Explicit concurrent mark sweep GC freed 50702(2MB) AllocSpace objects, 10(1026KB) LOS objects, 36% free, 27MB/43MB, paused 1.549ms total 67.945ms
,V/KeepSync( 3323): Connecting to GoogleApiClient
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3323): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,E/BooksAccountManager( 3535): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3535): Soft error
E/BooksSync( 3535): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3535): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3535): Sync error
E/BooksSync( 3535): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3535): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3535): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 277494, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3323): IOException
E/KeepSync( 3323): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3323): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3323): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3323): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3323): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3323): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3323): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3323): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3323): 	... 10 more
W/KeepSync( 3323): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 276815, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2989): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): ,	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at blb.a(PG:3937)
E/HttpOperation( 2989): 	,at czp.a(PG:18188)
E/HttpOperation( 2989): 	at czp.a(PG:9081)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125),
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 12 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089),
E/HttpOperation( 2989): 	... 14 more
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2989): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): 	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at hec.a(PG:42)
E/HttpOperation( 2989): 	at hee.a(PG:102)
E/HttpOperation( 2989): 	at czr.a(PG:65)
E/HttpOperation( 2989): 	at kka.a(PG:108)
E/HttpOperation( 2989): 	at czp.a(PG:19176)
E/HttpOperation( 2989): 	at czp.a(PG:9081)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125)
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 15 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089)
E/HttpOperation( 2989): 	... 17 more
,E/ExperimentLoader( 2989): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2989): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2989): 	at jdm.a(PG:82)
E/ExperimentLoader( 2989): 	at jcs.o(PG:406)
E/ExperimentLoader( 2989): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2989): 	at jcs.i(PG:143)
E/ExperimentLoader( 2989): 	at hec.a(PG:42)
E/ExperimentLoader( 2989): 	at hee.a(PG:102)
E/ExperimentLoader( 2989): 	at czr.a(PG:65)
E/ExperimentLoader( 2989): 	at kka.a(PG:108)
E/ExperimentLoader( 2989): 	at czp.a(PG:19176)
E/ExperimentLoader( 2989): 	at czp.a(PG:9081)
E/ExperimentLoader( 2989): 	at czq.run(PG:1686)
E/ExperimentLoader( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2989): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2989): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2989): 	at jdm.a(PG:77)
E/ExperimentLoader( 2989): 	... 15 more
E/ExperimentLoader( 2989): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2989): 	at fal.a(PG:38)
E/ExperimentLoader( 2989): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2989): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 338202, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector command called,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"7C:F9:0E:34:8A
I/jxcore-log( 3216): Start now : testSendData.js
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): check server
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): serverPort is 40740
I/jxcore-log( 3216): 
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): initialize: F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT4432
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3216): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): setState: INITIALIZED
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT4432","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): start: OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): setState: RUNNING
I/jxcore-log( 3216): StartBroadcasting started ok
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:55:57.080Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Waiting for incoming connections...
I/jxcore-log( 3216): 2015-11-30T10:55:57.080Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:55:57.080Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 2015-11-30T10:55:57.088Z SendDataTCPServer.js: TCP/IP server is bound to port: 40740
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onWifiStateChanged: State changed to 2
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...,
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 5
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1,
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:9D:93:0B 34:FC:EF:9D:93:0B 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
,I/jxcore-log( 3216): 2015-11-30T10:55:57.783Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:55:57.784Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:55:57.785Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,V/GoogleAuthProtoRequest( 3291): [339] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3291): [339] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3291): [339] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3291): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3291): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3291): 	at com.a.a.k.run(SourceFile:110)
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3216): 2015-11-30T10:56:02.787Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:56:02.788Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): 2015-11-30T10:56:07.793Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:56:07.794Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:56:07.796Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:56:07.796Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10,
D/        ( 3272): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp,
,V/KeepSync( 3323): Connecting to GoogleApiClient
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3323): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3323): IOException
E/KeepSync( 3323): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3323): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3323): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3323): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3323): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3323): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3323): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3323): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3323): 	... 10 more
W/KeepSync( 3323): Sync result 2
,D/btif_config( 3272): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 430935, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/ActivityManager(  822): Start proc 3988:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,D/BluetoothManagerService(  822): Message: 20
,D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d912418:true
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0,
D/BluetoothAdapterProperties( 3272): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,I/ActivityManager(  822): Killing 3566:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Outgoing connection initialized (thread ID: 340),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 340),
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesRead: Read 77 bytes successfully (thread ID: 340)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Handshake succeeded with [34:FC:EF:9D:93:0B LGE-LG-D802_PT5756 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT5756 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 340)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT5756 34:FC:EF:9D:93:0B]
,I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, LGE-LG-D802_PT5756
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 54870
,I/BtConnectorHelper( 3216): Request socket is using : 54870
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :54870
,I/jxcore-log( 3216): 2015-11-30T10:56:11.114Z SendDataConnector.js: CLIENT connected to 54870, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:56:11.115Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 54870
,I/BtToRequestSocket( 3216): Set local streams
,I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-30T10:56:11.139Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1392
,I/jxcore-log( 3216): 2015-11-30T10:56:11.757Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:56:11.820Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:56:11.934Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:56:12.041Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:56:12.150Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:56:12.242Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:56:12.332Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:56:12.426Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:56:12.514Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3272): dm_pm_timer expires
W/bt-btif ( 3272): dm_pm_timer expires 0
W/bt-btif ( 3272): proc dm_pm_timer expires
,I/BooksSync( 3535): Starting books sync for 61035162, extras: ade
,I/art     (  822): Explicit concurrent mark sweep GC freed 34420(1477KB) AllocSpace objects, 7(300KB) LOS objects, 32% free, 33MB/49MB, paused 2.947ms total 102.471ms
,I/BooksConfig( 3535): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3535): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 3535): Soft error
E/BooksSync( 3535): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3535): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3535): Sync error
E/BooksSync( 3535): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3535): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3535): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 431787, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1528): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1528): ,	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1528): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1528): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1528): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1528): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
,W/GLSActivity( 1528): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3809): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3809): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3809): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3809): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3809): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3809): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3809): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3809): Ignoring header User-Agent because its value was null.
,I/jxcore-log( 3216): 2015-11-30T10:57:02.515Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:57:02.517Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:57:02.523Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:57:02.524Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:57:02.525Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3216): 
I/BtToSocketBase( 3216): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3216): Disconnect outgoing peer: LGE-LG-D802_PT5756
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Close LocalOutputStream,
,I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): 2015-11-30T10:57:07.524Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:57:07.525Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/ActivityManager(  822): Start proc 4028:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,D/BluetoothManagerService(  822): Message: 20
,D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b86c58e:true
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  822): Start proc 4054:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test's G2
,I/ActivityManager(  822): Killing 3707:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3727:com.google.android.deskclock/u0a44 (adj 15): empty #17
,I/jxcore-log( 3216): 2015-11-30T10:57:12.529Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:57:12.530Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:57:12.530Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:57:12.531Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test's G2
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,D/btif_config( 3272): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1,
E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c,
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State,
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
D/BluetoothAdapterProperties( 3272): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Outgoing connection initialized (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesRead: Read 77 bytes successfully (thread ID: 345),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Handshake succeeded with [34:FC:EF:9D:93:0B LGE-LG-D802_PT5756 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT5756 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 345)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT5756 34:FC:EF:9D:93:0B]
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, LGE-LG-D802_PT5756
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3216): mHTTPPort  set to : 53685
I/BtConnectorHelper( 3216): Request socket is using : 53685
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :53685
,I/jxcore-log( 3216): 2015-11-30T10:57:14.681Z SendDataConnector.js: CLIENT connected to 53685, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:57:14.682Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 53685
,I/BtToRequestSocket( 3216): Set local streams
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-30T10:57:14.697Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3272): dm_pm_timer expires
,W/bt-btif ( 3272): dm_pm_timer expires 0
W/bt-btif ( 3272): proc dm_pm_timer expires
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2989): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): 	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at blb.a(PG:3937)
E/HttpOperation( 2989): 	at czp.a(PG:18188)
E/HttpOperation( 2989): 	at czp.a(PG:9081)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125)
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 12 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089)
E/HttpOperation( 2989): 	... 14 more
,I/art     ( 1528): Explicit concurrent mark sweep GC freed 48289(2MB) AllocSpace objects, 11(1212KB) LOS objects, 36% free, 27MB/43MB, paused 1.006ms total 30.068ms
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2989): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): 	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at hec.a(PG:42)
E/HttpOperation( 2989): 	at hee.a(PG:102)
E/HttpOperation( 2989): 	at czr.a(PG:65)
E/HttpOperation( 2989): 	at kka.a(PG:108)
E/HttpOperation( 2989): 	at czp.a(PG:19176)
E/HttpOperation( 2989): 	at czp.a(PG:9081)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125)
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 15 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089)
E/HttpOperation( 2989): 	... 17 more
E/ExperimentLoader( 2989): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2989): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2989): 	at jdm.a(PG:82)
E/ExperimentLoader( 2989): 	at jcs.o(PG:406)
E/ExperimentLoader( 2989): 	at jcn.a(PG:1379),
E/ExperimentLoader( 2989): 	at jcs.i(PG:143)
E/ExperimentLoader( 2989): 	at hec.a(PG:42)
E/ExperimentLoader( 2989): 	at hee.a(PG:102)
E/ExperimentLoader( 2989): 	at czr.a(PG:65)
E/ExperimentLoader( 2989): 	at kka.a(PG:108)
E/ExperimentLoader( 2989): 	at czp.a(PG:19176)
E/ExperimentLoader( 2989): 	at czp.a(PG:9081)
E/ExperimentLoader( 2989): 	at czq.run(PG:1686)
E/ExperimentLoader( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2989): 	at jdj.a(PG:4091),
E/ExperimentLoader( 2989): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2989): 	at jdm.a(PG:77)
E/ExperimentLoader( 2989): 	... 15 more
E/ExperimentLoader( 2989): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2989): 	at fal.a(PG:38)
E/ExperimentLoader( 2989): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2989): 	... 17 more,
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 493273, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3216): 2015-11-30T10:58:04.781Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:58:04.782Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:58:04.783Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:58:04.784Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:58:04.785Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3216): 
I/BtToSocketBase( 3216): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3216): Disconnect outgoing peer: LGE-LG-D802_PT5756
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3216): Close bt out
,I/BtToSocketBase( 3216): Close bt socket
,I/BtToRequestSocket( 3216): Close server socket
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive,
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test's G2
,I/jxcore-log( 3216): 2015-11-30T10:58:09.786Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:58:09.787Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:58:14.792Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:58:14.793Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:58:14.794Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:58:14.795Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3272): info:x10,
D/        ( 3272): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test's G2
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,D/btif_config( 3272): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
D/BluetoothAdapterProperties( 3272): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Outgoing connection initialized (thread ID: 350)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 350)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 350)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesRead: Read 77 bytes successfully (thread ID: 350)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Handshake succeeded with [34:FC:EF:9D:93:0B LGE-LG-D802_PT5756 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT5756 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 350)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT5756 34:FC:EF:9D:93:0B]
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, LGE-LG-D802_PT5756
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 60413
,I/BtConnectorHelper( 3216): Request socket is using : 60413
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :60413
,I/jxcore-log( 3216): 2015-11-30T10:58:17.667Z SendDataConnector.js: CLIENT connected to 60413, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:58:17.668Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 60413
I/BtToRequestSocket( 3216): Set local streams
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-30T10:58:17.679Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3272): dm_pm_timer expires
W/bt-btif ( 3272): dm_pm_timer expires 0
W/bt-btif ( 3272): proc dm_pm_timer expires
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): 2015-11-30T10:59:07.747Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:59:07.748Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:59:07.750Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:59:07.751Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:59:07.752Z SendDataConnector.js: ----------------- closeClientSocket,
I/jxcore-log( 3216): 
I/BtToSocketBase( 3216): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3216): Disconnect outgoing peer: LGE-LG-D802_PT5756
I/BtToSocketBase( 3216): Stop ReceivingThread
,I/BtToSocketBase( 3216): Stop SendingThread
,I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test's G2,
,I/jxcore-log( 3216): 2015-11-30T10:59:12.752Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:59:12.752Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:59:17.756Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:59:17.757Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T10:59:17.757Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:59:17.758Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test's G2
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,D/btif_config( 3272): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0,
D/BluetoothAdapterProperties( 3272): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Outgoing connection initialized (thread ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesRead: Read 77 bytes successfully (thread ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Handshake succeeded with [34:FC:EF:9D:93:0B LGE-LG-D802_PT5756 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT5756 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 355)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT5756 34:FC:EF:9D:93:0B]
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, LGE-LG-D802_PT5756
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 47428
I/BtConnectorHelper( 3216): Request socket is using : 47428
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :47428
,I/jxcore-log( 3216): 2015-11-30T10:59:19.648Z SendDataConnector.js: CLIENT connected to 47428, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T10:59:19.649Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 47428
,I/BtToRequestSocket( 3216): Set local streams
I/BtToRequestSocket( 3216): rin ended ---------------------------;
I/jxcore-log( 3216): 2015-11-30T10:59:19.661Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3272): dm_pm_timer expires,
W/bt-btif ( 3272): dm_pm_timer expires 0
W/bt-btif ( 3272): proc dm_pm_timer expires
,V/GoogleAuthProtoRequest( 3291): [340] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3291): [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3291): [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3291): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3291): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3291): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): 2015-11-30T11:00:09.720Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:00:09.721Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:00:09.723Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:00:09.730Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:00:09.730Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:00:09.733Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/BtConnectorHelper( 3216): Disconnect outgoing peer: 34:FC:EF:9D:93:0B
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3216): 2015-11-30T11:00:09.739Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:00:09.746Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:00:09.746Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:00:09.747Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/jxcore-log( 3216): 2015-11-30T11:00:09.753Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:9D:93:0B done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f23eb4 rs_disc_pending=1
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND,
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f23eb4 rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): info:x10,
D/        ( 3272): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp,
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f23eb4 rs_disc_pending=1,
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,D/btif_config( 3272): btif_get_device_type: Device [b0:c5:59:3f:75:69] type 1,
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1,
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3272): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 3272): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=0
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Outgoing connection initialized (thread ID: 360)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 360)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 360)
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f23eb4 rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=1
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesRead: Read 82 bytes successfully (thread ID: 360)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 360)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, samsung-SM-G900F_PT9998
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 60008
,I/BtConnectorHelper( 3216): Request socket is using : 60008
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :60008,
,I/jxcore-log( 3216): 2015-11-30T11:00:14.590Z SendDataConnector.js: CLIENT connected to 60008, error: null
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:00:14.590Z SendDataConnector.js: CLIENT starting client 
,I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 60008
,I/BtToRequestSocket( 3216): Set local streams
I/jxcore-log( 3216): 2015-11-30T11:00:14.601Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=0,
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3216): 2015-11-30T11:00:15.345Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-30T11:00:15.408Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:00:15.469Z SendDataConnector.js: CLIENT is data received : 30000
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:00:15.481Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:00:15.526Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:00:15.600Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:00:15.642Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:00:15.682Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-30T11:00:15.758Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3272): dm_pm_timer expires
W/bt-btif ( 3272): dm_pm_timer expires 0
,W/bt-btif ( 3272): proc dm_pm_timer expires
,I/ActivityManager(  822): Start proc 4134:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,V/KeepSync( 3323): Connecting to GoogleApiClient
,I/GAv4    ( 4134): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4134):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4134):   adb logcat -s GAv4
,W/GAv4    ( 4134): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GAv4    ( 4134): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 4134): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/ClientConnectionOperation( 1781): Handling authorization failure
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
,V/KeepSync( 3323): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,I/art     (  822): Explicit concurrent mark sweep GC freed 31327(1443KB) AllocSpace objects, 6(378KB) LOS objects, 32% free, 33MB/49MB, paused 1.569ms total 67.202ms
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3323): IOException,
E/KeepSync( 3323): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
,E/KeepSync( 3323): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3323): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3323): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3323): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3323): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3323): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3323): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3323): 	,at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3323): 	... 10 more
W/KeepSync( 3323): Sync result 2
D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 686901, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Killing 3641:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,E/libprocessgroup(  822): failed to kill 1 processes for processgroup 3641
,I/jxcore-log( 3216): 2015-11-30T11:01:05.758Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:01:05.759Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:05.760Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-30T11:01:05.765Z SendDataConnector.js: tryAgain afer: 5000 ms.
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:01:05.766Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3216): 
,I/BtToSocketBase( 3216): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3216): Disconnect outgoing peer: samsung-SM-G900F_PT9998
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
,I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0,
,I/jxcore-log( 3216): 2015-11-30T11:01:10.766Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:01:10.766Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 3216): 2015-11-30T11:01:15.771Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:01:15.772Z SendDataConnector.js: Connect (retry count 1) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:01:15.772Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:01:15.773Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [b0:c5:59:3f:75:69]: 6, f, 4106
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Outgoing connection initialized (thread ID: 365)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 365)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 365)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesRead: Read 82 bytes successfully (thread ID: 365)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 365)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, samsung-SM-G900F_PT9998
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 39551
,I/BtConnectorHelper( 3216): Request socket is using : 39551
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :39551
,I/jxcore-log( 3216): 2015-11-30T11:01:17.951Z SendDataConnector.js: CLIENT connected to 39551, error: null
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:01:17.952Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 39551
,I/BtToRequestSocket( 3216): Set local streams
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-30T11:01:17.962Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3272): dm_pm_timer expires
,W/bt-btif ( 3272): dm_pm_timer expires 0
,W/bt-btif ( 3272): proc dm_pm_timer expires
,I/BooksSync( 3535): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3535): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3535): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3535): Soft error,
E/BooksSync( 3535): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3535): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3535): Sync error
E/BooksSync( 3535): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3535): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3535): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 718883, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f24244 rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,D/btif_config( 3272): btif_get_device_type: Device [7c:f9:0e:37:96:ab] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
D/BluetoothAdapterProperties( 3272): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Incoming connection initialized (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 369)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): onBytesRead: Read 83 bytes successfully (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT5840 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): removeThreadFromList: Removing thread with ID 369
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Handshake thread disposed (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT5840 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 369)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT5840 7C:F9:0E:37:96:AB]
,I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, samsung-SM-A500FU_PT5840
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket,
I/BtToRequestSocket( 3216): Creating BTConnectedThread
,I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.,
I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 40740
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-30T11:01:43.496Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f24244 rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3216): 2015-11-30T11:01:45.624Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:45.634Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:45.646Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:45.660Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:45.663Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:47.465Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): dm_pm_timer expires
,W/bt-btif ( 3272): dm_pm_timer expires 0
W/bt-btif ( 3272): proc dm_pm_timer expires
,I/jxcore-log( 3216): 2015-11-30T11:01:47.857Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:47.893Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:47.921Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:47.926Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:47.931Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:47.937Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:47.945Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:47.973Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.004Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.010Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.017Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.023Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.063Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.088Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.098Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.102Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.110Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.143Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.181Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.213Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.269Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.277Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-30T11:01:48.286Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.323Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.356Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.372Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.380Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.413Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.448Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.456Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.463Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.472Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.503Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.538Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.545Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.551Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.557Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3216): 2015-11-30T11:01:48.593Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.620Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-30T11:01:48.627Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:01:48.631Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3216): 
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): 2015-11-30T11:02:08.019Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:02:08.020Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:02:08.022Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:02:08.022Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:02:08.024Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3216): 
,I/BtToSocketBase( 3216): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3216): Disconnect outgoing peer: samsung-SM-G900F_PT9998
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log( 3216): 2015-11-30T11:02:13.024Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:02:13.025Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:02:18.032Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:02:18.032Z SendDataConnector.js: Connect (retry count 2) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:02:18.033Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:02:18.033Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2989): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): 	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at blb.a(PG:3937)
E/HttpOperation( 2989): 	at czp.a(PG:18188)
E/HttpOperation( 2989): 	at czp.a(PG:9081)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125)
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 12 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089)
E/HttpOperation( 2989): 	... 14 more
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2989): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): 	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at hec.a(PG:42)
E/HttpOperation( 2989): 	at hee.a(PG:102)
E/HttpOperation( 2989): 	at czr.a(PG:65)
E/HttpOperation( 2989): 	at kka.a(PG:108)
E/HttpOperation( 2989): 	at czp.a(PG:19176)
E/HttpOperation( 2989): 	at czp.a(PG:9081)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125)
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 15 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089)
E/HttpOperation( 2989): 	... 17 more
E/ExperimentLoader( 2989): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2989): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2989): 	at jdm.a(PG:82)
E/ExperimentLoader( 2989): 	at jcs.o(PG:406)
E/ExperimentLoader( 2989): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2989): 	at jcs.i(PG:143)
E/ExperimentLoader( 2989): 	at hec.a(PG:42)
E/ExperimentLoader( 2989): 	at hee.a(PG:102)
E/ExperimentLoader( 2989): 	at czr.a(PG:65)
E/ExperimentLoader( 2989): 	at kka.a(PG:108)
E/ExperimentLoader( 2989): 	at czp.a(PG:19176)
E/ExperimentLoader( 2989): 	at czp.a(PG:9081)
E/ExperimentLoader( 2989): 	at czq.run(PG:1686)
E/ExperimentLoader( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2989): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2989): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2989): 	at jdm.a(PG:77)
E/ExperimentLoader( 2989): 	... 15 more
E/ExperimentLoader( 2989): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2989): 	at fal.a(PG:38)
E/ExperimentLoader( 2989): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2989): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 781683, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=1
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3272): L2CAP - unknown CID: 0x0042
,W/bt-l2cap( 3272): L2CAP - unknown CID: 0x0042
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Outgoing connection initialized (thread ID: 374)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 374)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 374)
,W/bt-btif ( 3272): invalid rfc slot id: 4
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT5840
,I/BtToSocketBase( 3216): Stop ReceivingThread
,I/BtToSocketBase( 3216): Stop SendingThread
,I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3216): 2015-11-30T11:02:38.926Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=1,
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesRead: Read 82 bytes successfully (thread ID: 374)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 374)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, samsung-SM-G900F_PT9998
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 35419
,I/BtConnectorHelper( 3216): Request socket is using : 35419
I/BtToRequestSocket( 3216): Now accepting connections
,W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x45
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :35419
,I/jxcore-log( 3216): 2015-11-30T11:02:39.947Z SendDataConnector.js: CLIENT connected to 35419, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:02:39.948Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 35419
I/BtToRequestSocket( 3216): Set local streams
,I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-30T11:02:39.960Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: A5-1
,W/bt-btif ( 3272): dm_pm_timer expires
W/bt-btif ( 3272): dm_pm_timer expires 0
W/bt-btif ( 3272): proc dm_pm_timer expires
,W/bt-btif ( 3272): info:x10,
D/        ( 3272): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3,
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: A5-1
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Incoming connection initialized (thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 378)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): onBytesRead: Read 83 bytes successfully (thread ID: 378)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT5840 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): removeThreadFromList: Removing thread with ID 378
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Handshake thread disposed (thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT5840 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 378)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT5840 7C:F9:0E:37:96:AB]
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, samsung-SM-A500FU_PT5840
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 40740
,I/jxcore-log( 3216): 2015-11-30T11:02:50.585Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-30T11:02:50.969Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:02:51.023Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:02:51.029Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:02:51.037Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:02:51.052Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3272): dm_pm_timer expires
W/bt-btif ( 3272): dm_pm_timer expires 0,
W/bt-btif ( 3272): proc dm_pm_timer expires
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,W/bt-btif ( 3272): invalid rfc slot id: 13
I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): Disconnect outgoing peer: samsung-SM-G900F_PT9998
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3216): Close LocalOutputStream
,I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive,
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 3216): 2015-11-30T11:03:30.029Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:03:30.030Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:03:30.030Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:03:30.031Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:03:30.032Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:03:35.033Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:03:35.034Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:03:35.034Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:03:40.039Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:03:40.039Z SendDataConnector.js: Connect (retry count 3) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:03:40.040Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:03:40.041Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=1
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,W/bt-btif ( 3272): invalid rfc slot id: 12
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT5840
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed,
I/jxcore-log( 3216): 2015-11-30T11:03:41.417Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Outgoing connection initialized (thread ID: 383)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 383)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 383)
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesRead: Read 82 bytes successfully (thread ID: 383)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 383)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, samsung-SM-G900F_PT9998
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3216): mHTTPPort  set to : 54638
I/BtConnectorHelper( 3216): Request socket is using : 54638
I/BtToRequestSocket( 3216): Now accepting connections
,W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x49
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :54638
,I/jxcore-log( 3216): 2015-11-30T11:03:42.040Z SendDataConnector.js: CLIENT connected to 54638, error: null
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:03:42.041Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 54638
,I/BtToRequestSocket( 3216): Set local streams
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-30T11:03:42.053Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 4028): Bluetooth Device Name: A5-1
,W/bt-btif ( 3272): dm_pm_timer expires
W/bt-btif ( 3272): dm_pm_timer expires 0
W/bt-btif ( 3272): proc dm_pm_timer expires
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: A5-1,
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Incoming connection initialized (thread ID: 387)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 387)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): onBytesRead: Read 83 bytes successfully (thread ID: 387)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT5840 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 387)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): removeThreadFromList: Removing thread with ID 387
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Handshake thread disposed (thread ID: 387)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT5840 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 387)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT5840 7C:F9:0E:37:96:AB]
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, samsung-SM-A500FU_PT5840,
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 40740
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-30T11:03:52.219Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:03:52.588Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:03:52.596Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:03:52.639Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:03:52.643Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:03:52.647Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:03:52.654Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3272): dm_pm_timer expires
W/bt-btif ( 3272): dm_pm_timer expires 0
,W/bt-btif ( 3272): proc dm_pm_timer expires
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=0
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,W/bt-btif ( 3272): dm_pm_timer expires
,W/bt-btif ( 3272): dm_pm_timer expires 0
,W/bt-btif ( 3272): proc dm_pm_timer expires
,I/jxcore-log( 3216): 2015-11-30T11:04:32.119Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:04:32.120Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:32.121Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:04:32.122Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:04:32.123Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3216): 
I/BtToSocketBase( 3216): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3216): Disconnect outgoing peer: samsung-SM-G900F_PT9998
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-btm  ( 3272): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=2
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,D/btif_config( 3272): btif_get_device_type: Device [80:01:84:8a:b3:68] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State,
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
D/BluetoothAdapterProperties( 3272): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524],
I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Incoming connection initialized (thread ID: 391)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 391)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): onBytesRead: Read 84 bytes successfully (thread ID: 391),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Got valid identity from [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT2983 80:01:84:8A:B3:68],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 391)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): removeThreadFromList: Removing thread with ID 391
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Handshake thread disposed (thread ID: 391)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onIncomingConnectionConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT2983 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 391)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT2983 80:01:84:8A:B3:68]
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT2983
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): Creating BTConnectedThread
I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 40740
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-30T11:04:36.564Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.124Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.125Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.239Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.242Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.246Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.249Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.254Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.257Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-30T11:04:37.262Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.293Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.298Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.334Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.339Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.356Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.383Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.388Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.399Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.433Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.435Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.441Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.473Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.528Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.563Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.567Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.604Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.608Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:37.643Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3216): 2015-11-30T11:04:42.128Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:04:42.128Z SendDataConnector.js: Connect (retry count 4) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:04:42.129Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:42.130Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): invalid rfc slot id: 14
I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT5840
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
,I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT5840
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
,I/jxcore-log( 3216): 2015-11-30T11:04:42.923Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Outgoing connection initialized (thread ID: 396)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 396)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 396)
,W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x4d
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesRead: Read 82 bytes successfully (thread ID: 396)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 396)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, samsung-SM-G900F_PT9998
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 37022
,I/BtConnectorHelper( 3216): Request socket is using : 37022
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :37022
,I/jxcore-log( 3216): 2015-11-30T11:04:44.439Z SendDataConnector.js: CLIENT connected to 37022, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:04:44.440Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 37022
I/BtToRequestSocket( 3216): Set local streams
,I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-30T11:04:44.453Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): dm_pm_timer expires
,W/bt-btif ( 3272): dm_pm_timer expires 0
W/bt-btif ( 3272): proc dm_pm_timer expires
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=0
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): dm_pm_timer expires
W/bt-btif ( 3272): dm_pm_timer expires 0
,W/bt-btif ( 3272): proc dm_pm_timer expires
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test's G2,
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3272): dm_pm_timer expires
,W/bt-btif ( 3272): dm_pm_timer expires 0
W/bt-btif ( 3272): proc dm_pm_timer expires
,W/bt-btif ( 3272): invalid rfc slot id: 16
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT2983
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket,
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3216): 2015-11-30T11:05:27.909Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
,W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x4f
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3216): 2015-11-30T11:05:34.519Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:34.520Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:05:34.522Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:34.526Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:05:34.531Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:34.532Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/BtConnectorHelper( 3216): Disconnect outgoing peer: B0:C5:59:3F:75:69
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
,I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
,I/BtToRequestSocket( 3216): Close server socket
I/jxcore-log( 3216): 2015-11-30T11:05:34.550Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- gotta redo : B0:C5:59:3F:75:69, try count now: 1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:34.555Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:05:34.556Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:05:34.557Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 2015-11-30T11:05:34.566Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B0:C5:59:3F:75:69 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,D/btif_config( 3272): btif_get_device_type: Device [44:80:eb:7b:5a:05] type 1,
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
D/BluetoothAdapterProperties( 3272): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Outgoing connection initialized (thread ID: 401)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 401)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 401)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesRead: Read 81 bytes successfully (thread ID: 401)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 401)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
,I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, motorola-XT1072_PT6826
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 50200
,I/BtConnectorHelper( 3216): Request socket is using : 50200
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :50200
,I/jxcore-log( 3216): 2015-11-30T11:05:41.694Z SendDataConnector.js: CLIENT connected to 50200, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:41.696Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 50200
I/BtToRequestSocket( 3216): Set local streams
,I/BtToRequestSocket( 3216): rin ended ---------------------------;
I/jxcore-log( 3216): 2015-11-30T11:05:41.710Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23852
,I/jxcore-log( 3216): 2015-11-30T11:05:42.344Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/btif_config( 3272): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,D/        ( 3272): cod is 0, set as unclassified,
,I/BluetoothBondStateMachine( 3272): sspRequestCallback: [B@261cf346 name: [B@3a971907 cod: 7936 pairingVariant 0 passkey: 450418
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/jxcore-log( 3216): 2015-11-30T11:05:44.445Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13952
,I/jxcore-log( 3216): 2015-11-30T11:05:44.607Z SendDataConnector.js: CLIENT is data received : 30000,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:44.888Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): ,
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4052
,I/jxcore-log( 3216): 2015-11-30T11:05:45.383Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,W/bt-btm  ( 3272): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=2
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 3216): 2015-11-30T11:05:45.899Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:46.141Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:46.373Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:46.744Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [80:01:84:8a:b3:68]: 7, f, 610c
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Incoming connection initialized (thread ID: 405)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 405)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): onBytesRead: Read 84 bytes successfully (thread ID: 405)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Got valid identity from [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT2983 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 405)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): removeThreadFromList: Removing thread with ID 405
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Handshake thread disposed (thread ID: 405)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onIncomingConnectionConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT2983 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 405)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT2983 80:01:84:8A:B3:68]
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT2983
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 40740
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-30T11:05:50.506Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:50.913Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:50.915Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:50.934Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:50.937Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:50.954Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:05:50.973Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): dm_pm_timer expires
W/bt-btif ( 3272): dm_pm_timer expires 0
W/bt-btif ( 3272): proc dm_pm_timer expires
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f245d4 rs_disc_pending=0
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,W/bt-btif ( 3272): dm_pm_timer expires
,W/bt-btif ( 3272): dm_pm_timer expires 0
W/bt-btif ( 3272): proc dm_pm_timer expires
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f2440c rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,W/bt-btm  ( 3272): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f23eb4 rs_disc_pending=2,
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 9 Address: 34:FC:EF:9D:93:0B newState: 0
E/bt-btm  ( 3272): Device not in IRK list
D/BluetoothAdapterProperties( 3272): Failed to remove device: 34:FC:EF:9D:93:0B
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
E/bt-btif ( 3272): Do not find the bg connection mask for the remote device
I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
D/BluetoothMapService( 3272): onReceive
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 3272): dm_pm_timer expires
W/bt-btif ( 3272): dm_pm_timer expires 0
,W/bt-btif ( 3272): proc dm_pm_timer expires
,D/GCM     ( 1528): Message class com.google.f.a.a.i
,I/jxcore-log( 3216): 2015-11-30T11:06:36.744Z SendDataConnector.js: Receiving data timeout now,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:06:36.745Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:06:36.746Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:06:36.747Z SendDataConnector.js: tryAgain afer: 5000 ms.,
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:06:36.749Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3216): 
I/BtToSocketBase( 3216): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3216): Disconnect outgoing peer: motorola-XT1072_PT6826
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
,I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,W/bt-btif ( 3272): invalid rfc slot id: 17
I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT2983
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
,I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
,I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close bt in
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3216): Close bt out
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT2983
I/BtToSocketBase( 3216): Close bt socket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
,I/jxcore-log( 3216): 2015-11-30T11:06:40.940Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:06:41.748Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:06:41.749Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
,W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x4a
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3216): 2015-11-30T11:06:46.754Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:06:46.754Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:06:46.755Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:06:46.756Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): cancel: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
,E/bt-btif ( 3272): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:21, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Cancelled: Connection timeout [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
I/jxcore-log( 3216): 2015-11-30T11:07:16.767Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:07:16.768Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:07:16.771Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
W/jxcore-log( 3216): $$jxcore_callback_28 wasn't registered
W/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:07:21.772Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:07:21.773Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:07:26.777Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:07:26.778Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:07:26.779Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:07:26.780Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:2, scn:-188929868
W/bt-btif ( 3272): invalid rfc slot id: 22
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
,I/jxcore-log( 3216): 2015-11-30T11:07:26.806Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:07:26.808Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:07:26.808Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:07:31.810Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:07:31.810Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:07:36.815Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:07:36.816Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:07:36.816Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:07:36.817Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: XT1072 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:2, scn:-188929868
W/bt-btif ( 3272): invalid rfc slot id: 23
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): ,	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
I/jxcore-log( 3216): 2015-11-30T11:07:36.839Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:07:36.840Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:07:36.840Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:07:41.842Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:07:41.844Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x49
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 21
,I/jxcore-log( 3216): 2015-11-30T11:07:46.851Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:07:46.852Z SendDataConnector.js: Connect (retry count 4) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:07:46.853Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:07:46.853Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,V/GoogleAuthProtoRequest( 3291): [341] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3291): [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3291): [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3291): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3291): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3291): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): cancel: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
E/bt-btif ( 3272): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:24, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Cancelled: Connection timeout [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315),
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
,I/jxcore-log( 3216): 2015-11-30T11:08:16.866Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:16.867Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:16.871Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:16.872Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:08:16.876Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 1
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:08:16.880Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:16.880Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:16.882Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address F8:95:C7:87:3C:51
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [44:80:EB:7B:5A:05 motorola-XT1072_PT6826 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 44:80:EB:7B:5A:05 done with result: Connection to 44:80:EB:7B:5A:05 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: socket closed
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: socket closed,
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:300)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
I/jxcore-log( 3216): 2015-11-30T11:08:16.889Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3216): 
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: socket closed
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
I/jxcore-log( 3216): 2015-11-30T11:08:16.890Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:16.890Z SendDataConnector.js: tryAgain afer: 5000 ms.,
I/jxcore-log( 3216): 
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: socket closed [F8:95:C7:87:3C:51 F8:95:C7:87:3C:51 F8:95:C7:87:3C:51]
W/jxcore-log( 3216): $$jxcore_callback_36 wasn't registered
W/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:08:21.890Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:21.891Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:08:26.895Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:08:26.896Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:26.896Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:26.897Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback,
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:2, scn:-188929868
W/bt-btif ( 3272): invalid rfc slot id: 25
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [F8:95:C7:87:3C:51 F8:95:C7:87:3C:51 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
,I/jxcore-log( 3216): 2015-11-30T11:08:26.922Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:26.923Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:26.923Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:08:31.925Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:08:31.925Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:08:36.928Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:36.929Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:08:36.930Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:36.930Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:2, scn:-188929868
W/bt-btif ( 3272): invalid rfc slot id: 26
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [F8:95:C7:87:3C:51 F8:95:C7:87:3C:51 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
I/jxcore-log( 3216): 2015-11-30T11:08:36.950Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:36.950Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:36.950Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:08:41.951Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:41.952Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x4b
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 24
,I/jxcore-log( 3216): 2015-11-30T11:08:46.955Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:46.956Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:08:46.957Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:08:46.957Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/KeepSync( 3323): Connecting to GoogleApiClient
,I/art     (  822): Explicit concurrent mark sweep GC freed 45449(2MB) AllocSpace objects, 6(284KB) LOS objects, 32% free, 33MB/49MB, paused 1.388ms total 115.237ms
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1528): Explicit concurrent mark sweep GC freed 72001(3MB) AllocSpace objects, 13(1434KB) LOS objects, 36% free, 27MB/43MB, paused 1.743ms total 73.626ms
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
,V/KeepSync( 3323): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3323): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3323): IOException
E/KeepSync( 3323): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3323): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3323): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3323): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3323): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3323): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3323): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3323): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3323): 	... 10 more
W/KeepSync( 3323): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1198465, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
,E/bt-btif ( 3272): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:27, channel:7
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Cancelled: Connection timeout
,W/bt-btif ( 3272): invalid rfc slot id: 27
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Cancelled: Connection timeout [F8:95:C7:87:3C:51 F8:95:C7:87:3C:51 F8:95:C7:87:3C:51]
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
I/jxcore-log( 3216): 2015-11-30T11:09:16.969Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:09:16.970Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:09:16.971Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [F8:95:C7:87:3C:51 F8:95:C7:87:3C:51 F8:95:C7:87:3C:51]
W/jxcore-log( 3216): $$jxcore_callback_42 wasn't registered
W/jxcore-log( 3216): 
,D/btif_config( 3272): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1,
E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0,
D/BluetoothAdapterProperties( 3272): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,I/jxcore-log( 3216): 2015-11-30T11:09:21.972Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:09:21.973Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3216): 2015-11-30T11:09:26.977Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:09:26.978Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:09:26.979Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:09:26.979Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: G4-1 F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Cancelled: Connection timeout [F8:95:C7:87:3C:51 F8:95:C7:87:3C:51 F8:95:C7:87:3C:51]
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3272): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:28, channel:-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
,I/jxcore-log( 3216): 2015-11-30T11:09:56.992Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:09:56.992Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:09:56.996Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:09:56.999Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): ---- round done--------,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): ---- gotta redo : F8:95:C7:87:3C:51, try count now: 1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: 7C:F9:0E:51:18:22
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): 2015-11-30T11:09:57.003Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:09:57.003Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:09:57.003Z SendDataConnector.js: do connect now,
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address 7C:F9:0E:51:18:22
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [F8:95:C7:87:3C:51 F8:95:C7:87:3C:51 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:3C:51 done with result: Connection to F8:95:C7:87:3C:51 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 3216): 2015-11-30T11:09:57.009Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:09:57.010Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:09:57.010Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: socket closed
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: socket closed
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:300)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: socket closed
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: socket closed [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
W/jxcore-log( 3216): $$jxcore_callback_46 wasn't registered
W/jxcore-log( 3216): 
,I/BooksSync( 3535): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3535): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3535): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3535): Soft error
E/BooksSync( 3535): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3535): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3535): Sync error
E/BooksSync( 3535): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3535): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3535): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1262636, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3216): 2015-11-30T11:10:02.010Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:10:02.011Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): 2015-11-30T11:10:07.015Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:10:07.016Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:10:07.016Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:10:07.017Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...,
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:2, scn:-188929868
W/bt-btif ( 3272): invalid rfc slot id: 29
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	,at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
,I/jxcore-log( 3216): 2015-11-30T11:10:07.038Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:10:07.039Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:10:07.039Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0,
,I/jxcore-log( 3216): 2015-11-30T11:10:12.040Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:10:12.041Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:10:17.045Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:10:17.046Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:10:17.047Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:10:17.047Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:2, scn:-188929868
,W/bt-btif ( 3272): invalid rfc slot id: 30
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
I/jxcore-log( 3216): 2015-11-30T11:10:17.073Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:10:17.074Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:10:17.074Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:10:22.075Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:10:22.076Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x4c
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 28
,I/jxcore-log( 3216): 2015-11-30T11:10:27.080Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:10:27.081Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:10:27.081Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:10:27.082Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: G4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
E/bt-btif ( 3272): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:31, channel:-1
,I/jxcore-log( 3216): 2015-11-30T11:10:57.095Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:10:57.096Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:10:57.097Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
,W/jxcore-log( 3216): $$jxcore_callback_52 wasn't registered
W/jxcore-log( 3216): 
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x22  CID 0x40
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 31
,I/jxcore-log( 3216): 2015-11-30T11:11:02.097Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:11:02.098Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2989): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): 	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at blb.a(PG:3937)
E/HttpOperation( 2989): 	at czp.a(PG:18188)
E/HttpOperation( 2989): 	at czp.a(PG:9081)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125)
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 12 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089)
E/HttpOperation( 2989): 	... 14 more
,I/GLSUser ( 1528): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1528): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1528): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1528): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2989): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2989): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2989): 	at jdm.a(PG:82)
E/HttpOperation( 2989): 	at jcs.o(PG:406)
E/HttpOperation( 2989): 	at jcn.a(PG:1379)
E/HttpOperation( 2989): 	at jcs.i(PG:143)
E/HttpOperation( 2989): 	at hec.a(PG:42)
E/HttpOperation( 2989): 	at hee.a(PG:102)
E/HttpOperation( 2989): 	at czr.a(PG:65)
E/HttpOperation( 2989): 	at kka.a(PG:108)
E/HttpOperation( 2989): 	at czp.a(PG:19176)
E/HttpOperation( 2989): 	at czp.a(PG:9081)
E/HttpOperation( 2989): 	at czq.run(PG:1686)
E/HttpOperation( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2989): 	at jdj.a(PG:4091)
E/HttpOperation( 2989): 	at jdj.a(PG:1125)
E/HttpOperation( 2989): 	at jdm.a(PG:77)
E/HttpOperation( 2989): 	... 15 more
E/HttpOperation( 2989): Caused by: faj: BadAuthentication
E/HttpOperation( 2989): 	at fal.a(PG:38)
E/HttpOperation( 2989): 	at jdj.a(PG:4089)
E/HttpOperation( 2989): 	... 17 more
E/ExperimentLoader( 2989): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2989): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2989): 	at jdm.a(PG:82)
E/ExperimentLoader( 2989): 	at jcs.o(PG:406)
E/ExperimentLoader( 2989): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2989): 	at jcs.i(PG:143)
E/ExperimentLoader( 2989): 	at hec.a(PG:42)
E/ExperimentLoader( 2989): 	at hee.a(PG:102)
E/ExperimentLoader( 2989): 	at czr.a(PG:65)
E/ExperimentLoader( 2989): 	at kka.a(PG:108)
E/ExperimentLoader( 2989): 	at czp.a(PG:19176)
E/ExperimentLoader( 2989): 	at czp.a(PG:9081)
E/ExperimentLoader( 2989): 	at czq.run(PG:1686),
E/ExperimentLoader( 2989): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2989): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2989): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2989): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2989): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2989): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2989): 	at jdm.a(PG:77)
E/ExperimentLoader( 2989): ,	... 15 more
E/ExperimentLoader( 2989): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2989): 	at fal.a(PG:38)
E/ExperimentLoader( 2989): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2989): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1327824, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3216): 2015-11-30T11:11:07.102Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:11:07.103Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:11:07.103Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:11:07.104Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...,
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): cancel: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
E/bt-btif ( 3272): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:32, channel:-1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
I/jxcore-log( 3216): 2015-11-30T11:11:37.115Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:11:37.116Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:11:37.120Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:11:37.125Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- gotta redo : 7C:F9:0E:51:18:22, try count now: 1
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:11:37.130Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:11:37.132Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:11:37.133Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:51:18:22 done with result: Connection to 7C:F9:0E:51:18:22 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: socket closed
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: socket closed
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:300)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: socket closed
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread,
I/jxcore-log( 3216): 2015-11-30T11:11:37.142Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:11:37.142Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:11:37.143Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: socket closed [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
,W/jxcore-log( 3216): $$jxcore_callback_56 wasn't registered
W/jxcore-log( 3216): 
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x22  CID 0x41
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 32
,I/jxcore-log( 3216): 2015-11-30T11:11:42.143Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:11:42.144Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:11:47.148Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:11:47.149Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:11:47.150Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:11:47.150Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: ,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback,
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/BTLD    ( 3272): ######################################################################
E/BTLD    ( 3272): #
E/BTLD    ( 3272): # WARNING : BTU HCI(id=0) command timeout. opcode=0x41d
E/BTLD    ( 3272): #
E/BTLD    ( 3272): ######################################################################
W/bt-hci  ( 3272): HCI Cmd timeout counter 1
,I/EventLogService( 1781): Opted in for usage reporting
,I/EventLogService( 1781): Aggregate from 1448880104200 (log), 1448880104200 (data)
,W/EventLogAggregator( 1781): Unknown tag: snet_gcore
W/EventLogAggregator( 1781): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1781): dumping service [account]
,E/BTLD    ( 3272): ######################################################################
,E/BTLD    ( 3272): #
E/BTLD    ( 3272): # WARNING : BTU HCI(id=0) command timeout. opcode=0x41b
E/BTLD    ( 3272): #
E/BTLD    ( 3272): ######################################################################
E/bt-hci  ( 3272): Num consecutive HCI Cmd tout =2 Restarting BT process
,D/BluetoothManagerService(  822): BluetoothServiceConnection, disconnected: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  822): BluetoothServiceConnection, disconnected: com.android.bluetooth.gatt.GattService
D/BluetoothA2dp( 1065): Proxy object disconnected
,D/BluetoothInputDevice( 1065): Proxy object disconnected
D/BluetoothManagerService(  822): Message: 41
D/BluetoothPan( 1065): BluetoothPAN Proxy object disconnected
D/BluetoothMap( 1065): Proxy object disconnected
,E/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED: 1
D/BluetoothManagerService(  822): Calling onBluetoothServiceDown callbacks
,D/BluetoothA2dp(  822): Proxy object disconnected
D/BluetoothManagerService(  822): Broadcasting onBluetoothServiceDown() to 8 receivers.
,W/BluetoothManagerService(  822): Profile service for profile: ComponentInfo{com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService} died.
D/BluetoothHeadset(  822): Proxy object disconnected
D/BluetoothHeadset( 1065): Proxy object disconnected
D/BluetoothHeadset(  822): Proxy object disconnected
D/BluetoothHeadset( 1279): Proxy object disconnected
D/BluetoothHeadset(  822): Proxy object disconnected
,D/BluetoothManagerService(  822): Bluetooth State Change Intent: 12 -> 13
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1,
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:91)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	,at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onIncomingConnectionFailed: Socket is null
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onServerStopped: Restarting the server...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): startListeningForIncomingConnections: Starting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Shutting down...
,I/jxcore-log( 3216): 2015-11-30T11:12:03.400Z SendDataConnector.js: CLIENT connected to -1, error: Connection to  failed
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
I/jxcore-log( 3216): 2015-11-30T11:12:03.400Z SendDataConnector.js: CLIENT Can not Connect: Connection to  failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:12:03.400Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Socket is null
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
W/jxcore-log( 3216): $$jxcore_callback_58 wasn't registered
W/jxcore-log( 3216): 
,W/jxcore-log( 3216): $$jxcore_callback_58 wasn't registered
W/jxcore-log( 3216): 
,I/ActivityManager(  822): Process com.android.bluetooth (pid 3272) has died
,W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.hfp.HeadsetService in 1000ms
,W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.hid.HidService in 1000ms
W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.pan.PanService in 1000ms
,W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMapService in 1000ms
,W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 1000ms
W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.gatt.GattService in 10999ms
,W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.hdp.HealthService in 20999ms
W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.opp.BluetoothOppService in 20998ms
,W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.a2dp.A2dpService in 20997ms
,D/BluetoothManagerService(  822): Broadcasting onBluetoothStateChange(false) to 13 receivers.
D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 1065): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1065): 1015840052: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1065): 1015840052: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1065): 1015840052: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback,
E/BluetoothSocket( 3216): bindListen fail, reason: bluetooth is off
D/BluetoothA2dp( 1065): onBluetoothStateChange: up=false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): Failed to create the socket listener thread: Error: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): java.io.IOException: Error: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): 	at android.bluetooth.BluetoothAdapter.createNewRfcommSocketAndRecord(BluetoothAdapter.java:1212)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): 	at android.bluetooth.BluetoothAdapter.listenUsingInsecureRfcommWithServiceRecord(BluetoothAdapter.java:1159)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): 	,at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.<init>(BluetoothServerThread.java:73)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector.startListeningForIncomingConnections(BluetoothConnector.java:136)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector.onServerStopped(BluetoothConnector.java:312)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:123)
,D/BluetoothMap( 1065): onBluetoothStateChange: up=false
W/ContextImpl( 3988): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothHeadset( 1065): onBluetoothStateChange: up=false
,D/BluetoothHeadsetClient( 1065): onBluetoothStateChange: up=false
E/BluetoothHeadsetClient( 1065): 
E/BluetoothHeadsetClient( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@35dbf03c
E/BluetoothHeadsetClient( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1065): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1065): ,	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothA2dpSink( 1065): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1065): 
E/BluetoothA2dpSink( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@3c3fc1c5
E/BluetoothA2dpSink( 1065): 	,at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1065): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1065): 	,at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothAvrcpController( 1065): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1065): 
E/BluetoothAvrcpController( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@378db71a
E/BluetoothAvrcpController( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1065): ,	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1065): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1279): onBluetoothStateChange: up=false
D/BluetoothA2dp(  822): onBluetoothStateChange: up=false
,I/ActivityManager(  822): Start proc 4369:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,D/BluetoothManagerService(  822): Bluetooth State Change Intent: 13 -> 10
D/BluetoothManagerService(  822): Message: 41
D/BluetoothAdapter( 3988): 339689666: getState() :  mService = null. Returning STATE_OFF
E/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED: 2
,D/BluetoothAdapter( 1065): 1015840052: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1065): 1015840052: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1065): 1015840052: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/LocalBluetoothProfileManager( 3988): Adding local MAP profile
,D/BluetoothMap( 3988): Create BluetoothMap proxy object
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/LocalBluetoothProfileManager( 3988): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3988): finishStartingService: stopping service
,W/ResourcesManager( 4369): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  822): Message: 42
D/BluetoothManagerService(  822): MESSAGE_RESTART_BLUETOOTH_SERVICE: Restart IBluetooth service
,D/AdapterServiceConfig( 4369): Adding HeadsetService
,D/AdapterServiceConfig( 4369): Adding A2dpService
D/AdapterServiceConfig( 4369): Adding HidService
D/AdapterServiceConfig( 4369): Adding HealthService
D/AdapterServiceConfig( 4369): Adding PanService
D/AdapterServiceConfig( 4369): Adding GattService
D/AdapterServiceConfig( 4369): Adding BluetoothMapService
,D/BluetoothManagerService(  822): Message: 20,
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@135198ab:true
D/BluetoothAdapterState( 4369): make
,I/bluedroid( 4369): init
I/BluetoothAdapterState( 4369): Entering OffState
,I/bte_conf( 4369): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 4369): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 4369): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 4369): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 4369): get_profile_interface socket
I/bluedroid( 4369): get_profile_interface map_client
,I/GKI_LINUX( 4369): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothManagerService(  822): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  822): Message: 40
,D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/BtGatt.JNI( 4369): classInitNative(L873): classInitNative: Success!
I/bluedroid( 4369): config_hci_snoop_log
,D/BluetoothAdapterProperties( 4369): Address is:F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  822): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  822): Broadcasting onBluetoothServiceUp() to 9 receivers.
W/BluetoothProfileService( 4369): onCreate, null mAdapterService
D/BluetoothAdapterProperties( 4369): Name is: Nexus 6
,D/BluetoothManagerService(  822): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  822): Stored Bluetooth name: Nexus 6
D/BluetoothManagerService(  822): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  822): Message: 40
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothAdapterState( 4369): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 4369): Setting state to 11
I/BluetoothAdapterState( 4369): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  822): Bluetooth State Change Intent: 10 -> 11
D/BluetoothPbap( 3988): Proxy object connected
D/BluetoothBondStateMachine( 4369): make
,D/PbapServerProfile( 3988): Bluetooth service connected
I/BluetoothBondStateMachine( 4369): StableState(): Entering Off State
,D/BluetoothPbap( 3988): Proxy object disconnected
D/PbapServerProfile( 3988): Bluetooth service disconnected
,I/ActivityManager(  822): Start proc 4395:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/BluetoothAdapterService( 4369): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/HeadsetService( 4369): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 4369): classInitNative: succeeds
D/HeadsetStateMachine( 4369): make
,D/HeadsetStateMachine( 4369): max_hf_connections = 1
I/bluedroid( 4369): get_profile_interface handsfree
,D/HeadsetStateMachine( 4369): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 4369): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/A2dpService( 4369): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 4369): classInitNative: succeeds
I/bluedroid( 4369): get_profile_interface avrcp
,I/BluetoothAdapterState( 4369): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false,
,E/RemoteController( 4369): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 4369): classInitNative: succeeds
D/A2dpStateMachine( 4369): make
,I/bluedroid( 4369): get_profile_interface a2dp
,I/GKI_LINUX( 4369): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/A2dpStateMachine( 4369): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 4369): classInitNative: succeeds
,D/BluetoothAdapterService( 4369): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/HidService( 4369): Received start request. Starting profile...
I/bluedroid( 4369): get_profile_interface hidhost
,D/BluetoothInputDevice( 3988): Proxy object connected
,D/HidProfile( 3988): Bluetooth service connected
,I/BluetoothHealthServiceJni( 4369): classInitNative: succeeds
,D/BluetoothAdapterService( 4369): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4,
D/HealthService( 4369): Received start request. Starting profile...
I/bluedroid( 4369): get_profile_interface health
,D/HeadsetStateMachine( 4369): Proxy object connected
I/BluetoothPanServiceJni( 4369): classInitNative(L105): succeeds
D/BluetoothAdapterService( 4369): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/PanService( 4369): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 4369): initializeNative(L110): pan
I/bluedroid( 4369): get_profile_interface pan
D/BluetoothPan( 3988): BluetoothPAN Proxy object connected
D/PanProfile( 3988): Bluetooth service connected
,D/BtGatt.DebugUtils( 4369): handleDebugAction() action=null
D/BtGatt.GattService( 4369): Received start request. Starting profile...
D/BtGatt.GattService( 4369): start()
,I/bluedroid( 4369): get_profile_interface gatt
D/BluetoothAdapterService( 4369): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
D/BtGatt.AdvertiseManager( 4369): advertise manager created
,D/HeadsetStateMachine( 4369): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 4369): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 4369): Disconnected process message: 11, size: 0
D/BluetoothAdapterService( 4369): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/BluetoothMap( 3988): Proxy object connected
D/BluetoothMapService( 4369): Received start request. Starting profile...
D/BluetoothMapService( 4369): start()
D/MapProfile( 3988): Bluetooth service connected
D/BluetoothMap( 3988): getConnectedDevices()
,D/BluetoothMap( 3988): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 4369): Found 0 applications
D/BluetoothMapEmailAppObserver( 4369): createReceiver()
,D/BluetoothMapEmailAppObserver( 4369): initObservers()
D/BluetoothMapEmailAppObserver( 4369): getEnabledAccountItems()
,D/StrictMode( 4395): StrictMode policy violation; ~duration=237 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4395): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4395): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4395): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4395): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4395): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4395): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4395): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 4395): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 4395): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4395): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4395): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4395): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4395): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4395): StrictMode policy violation; ~duration=236 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4395): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4395): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4395): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4395): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4395): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4395): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4395): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4395): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4395): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 4395): StrictMode policy violation; ~duration=234 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
D/StrictMode( 4395): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4395): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4395): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165),
D/StrictMode( 4395): ,	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4395): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4395): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4395): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4395): ,	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 4395): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 4395): ,	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4395): 	,at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012),
D/StrictMode( 4395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4395): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4395): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4395): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4395): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4395): 	,at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4395): ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4395): StrictMode policy violation; ~duration=228 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4395): ,	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4395): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 4395): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 4395): ,	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
,D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4395): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4395): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
,D/StrictMode( 4395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4395): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4395): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4395): 	,at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4395): StrictMode policy violation; ~duration=198 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4395): ,	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4395): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4395): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4395): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4395): 	,at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4395): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4395): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80),
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4395): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
,D/StrictMode( 4395): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4395): 	at android.os.Looper.loop(Looper.java:135),
D/StrictMode( 4395): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
,D/StrictMode( 4395): 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 4395): StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 4395): 	,at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4395): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 4395): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 4395): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 4395): 	,at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 4395): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 4395): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 4395): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 4395): 	,at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 4395): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 4395): # via Binder call with stack:
D/StrictMode( 4395): android.os.StrictMode$LogStackTrace
D/StrictMode( 4395): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 4395): 	,at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 4395): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 4395): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 4395): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 4395): 	,at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 4395): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 4395): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 4395): 	,at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 4395): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
,D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4395): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4395): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4395): ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4395): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4395): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4395): 	,at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 4395): StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4395): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4395): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4395): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4395): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4395): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4395): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4395): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 4395): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4395): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4395): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4395): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4395): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 4395): StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4395): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4395): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4395): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4395): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4395): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4395): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4395): ,	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4395): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4395): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4395): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4395): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4395): StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4395): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4395): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4395): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4395): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4395): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4395): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4395): ,	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4395): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4395): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4395): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4395): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 4395): StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4395): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4395): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4395): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4395): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4395): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4395): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4395): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 4395): 	at com.google.p.j.a(PG:121)
D/StrictMode( 4395): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 4395): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 4395): 	at com.google.p.e.a(PG:170)
D/StrictMode( 4395): 	at com.google.p.e.b(PG:21)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4395): 	,at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4395): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4395): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4395): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4395): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4395): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4395): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/ActivityThread( 4395): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/com.google.a.a.a.b.a( 4395): Application name is not set. Call Builder#setApplicationName.
D/BluetoothManagerService(  822): Message: 20
,D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2521ed68:true
,D/AuthorizationBluetoothService( 1528): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3988): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
,D/DockEventReceiver( 3988): finishStartingService: stopping service
,D/AuthorizationBluetoothService( 1528): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/AuthorizationBluetoothService( 1528): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/art     (  822): Explicit concurrent mark sweep GC freed 31621(1533KB) AllocSpace objects, 11(364KB) LOS objects, 32% free, 33MB/49MB, paused 2.290ms total 111.859ms
,I/art     ( 1752): Explicit concurrent mark sweep GC freed 18505(1106KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.226ms total 41.479ms
,V/Herrevad( 1781): NQAS connected
,E/DataBuffer( 1752): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@5916895)
,E/DataBuffer( 1752): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@25051daa)
,D/HeadsetStateMachine( 4369): Disconnected process message: 10, size: 0
,D/BluetoothManagerService(  822): Message: 401
,D/BluetoothHeadset(  822): Proxy object connected,
,D/BluetoothHeadset( 1065): Proxy object connected
,D/BluetoothHeadset(  822): Proxy object connected
D/BluetoothHeadset( 1279): Proxy object connected
,D/BluetoothHeadset(  822): Proxy object connected
,I/jxcore-log( 3216): 2015-11-30T11:12:08.401Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:08.402Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
,D/BluetoothAdapterState( 4369): CURRENT_STATE=PENDING, MESSAGE = START_TIMEOUT, isTurningOn=true, isTurningOff=false
,E/BluetoothAdapterState( 4369): Error enabling Bluetooth
D/BluetoothAdapterProperties( 4369): Setting state to 10
I/BluetoothAdapterState( 4369): Bluetooth adapter state changed: 11-> 10
D/BluetoothManagerService(  822): Message: 60
,D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=10
I/BluetoothAdapterState( 4369): Entering OffState
D/BluetoothManagerService(  822): Broadcasting onBluetoothStateChange(false) to 17 receivers.
,D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothHeadset(  822): Proxy object disconnected
D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothHeadset(  822): Proxy object disconnected
,D/BluetoothInputDevice( 1065): onBluetoothStateChange: up=false
,E/BluetoothInputDevice( 1065): 
E/BluetoothInputDevice( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@fb4b8d2
E/BluetoothInputDevice( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothInputDevice( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothInputDevice( 1065): 	,at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothInputDevice( 1065): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:216)
E/BluetoothInputDevice( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothA2dp( 1065): onBluetoothStateChange: up=false
E/BluetoothA2dp( 1065): 
E/BluetoothA2dp( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dp$2@202f575d
E/BluetoothA2dp( 1065): 	,at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dp( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dp( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dp( 1065): 	,at android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange(BluetoothA2dp.java:126)
E/BluetoothA2dp( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dp( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothMap( 1065): onBluetoothStateChange: up=false
E/BluetoothMap( 1065): 
E/BluetoothMap( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@4aedda3
E/BluetoothMap( 1065): 	,at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothMap( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothMap( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothMap( 1065): 	,at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
E/BluetoothMap( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadset( 1065): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1065): Proxy object disconnected
D/BluetoothInputDevice( 3988): onBluetoothStateChange: up=false
D/BluetoothHeadsetClient( 1065): onBluetoothStateChange: up=false
,E/BluetoothHeadsetClient( 1065): 
E/BluetoothHeadsetClient( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@35dbf03c
E/BluetoothHeadsetClient( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1065): ,	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1065): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1065): 	at android.os.Binder.execTransact(Binder.java:446),
E/BluetoothPan( 1065): 
E/BluetoothPan( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@150e38a0
E/BluetoothPan( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothPan( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothPan( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothPan( 1065): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:199)
E/BluetoothPan( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothPbap( 3988): onBluetoothStateChange: up=false
D/BluetoothA2dpSink( 1065): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1065): 
E/BluetoothA2dpSink( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@3c3fc1c5
E/BluetoothA2dpSink( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1065): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothAvrcpController( 1065): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1065): 
E/BluetoothAvrcpController( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@378db71a
E/BluetoothAvrcpController( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1065): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothHeadset(  822): Proxy object disconnected
D/BluetoothHeadset( 1279): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1279): Proxy object disconnected
D/BluetoothA2dp(  822): onBluetoothStateChange: up=false
,E/BluetoothA2dp(  822): 
E/BluetoothA2dp(  822): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dp$2@2f53c4e6
E/BluetoothA2dp(  822): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dp(  822): ,	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dp(  822): 	at android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange(BluetoothA2dp.java:126)
E/BluetoothA2dp(  822): 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:710)
E/BluetoothA2dp(  822): 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:1386)
E/BluetoothA2dp(  822): 	at com.android.server.BluetoothManagerService.access$3300(BluetoothManagerService.java:61)
E/BluetoothA2dp(  822): 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1113)
E/BluetoothA2dp(  822): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/BluetoothA2dp(  822): 	at android.os.Looper.loop(Looper.java:135)
E/BluetoothA2dp(  822): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/BluetoothA2dp(  822): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,D/BluetoothMap( 3988): onBluetoothStateChange: up=false
D/BluetoothManagerService(  822): Bluetooth State Change Intent: 11 -> 10
E/BluetoothManagerService(  822): recoverBluetoothServiceFromError
D/BluetoothMapService( 4369): onReceive
,W/ContextImpl( 3988): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3988): finishStartingService: stopping service
,D/AuthorizationBluetoothService( 1528): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  822): Sending off request.
,D/BluetoothAdapterState( 4369): CURRENT_STATE=OFF, MESSAGE = USER_TURN_OFF
,D/BluetoothManagerService(  822): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  822): Broadcasting onBluetoothServiceDown() to 10 receivers.
,I/GKI_LINUX( 4369): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 4369): GKI_exit_task 1 done
I/GKI_LINUX( 4369): GKI_shutdown(): task [BTIF] terminated
I/GKI_LINUX( 4369): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 4369): GKI_exit_task 2 done
I/BluetoothServiceJni( 4369): cleanupNative: return from cleanup,
,I/art     ( 4369): System.exit called, status: 0,
,I/AndroidRuntime( 4369): VM exiting with result code 0, cleanup skipped.,
,W/BluetoothManagerService(  822): Profile service for profile: ComponentInfo{com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService} died.
I/ActivityManager(  822): Process com.android.bluetooth (pid 4369) has died
,W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMapService in 1000ms
,W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.hdp.HealthService in 1000ms
W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.hid.HidService in 1000ms
,W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.hfp.HeadsetService in 1000ms
,W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.pan.PanService in 1000ms
,W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.gatt.GattService in 43996ms
W/ActivityManager(  822): Scheduling restart of crashed service com.android.bluetooth/.a2dp.A2dpService in 1000ms
,I/ActivityManager(  822): Killing 2656:com.google.android.talk/u0a61 (adj 15): empty #17
,D/BluetoothManagerService(  822): Message: 42
D/BluetoothManagerService(  822): MESSAGE_RESTART_BLUETOOTH_SERVICE: Restart IBluetooth service
,I/ActivityManager(  822): Start proc 4437:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,W/ResourcesManager( 4437): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  822): Message: 401
,D/AdapterServiceConfig( 4437): Adding HeadsetService
,D/AdapterServiceConfig( 4437): Adding A2dpService
D/AdapterServiceConfig( 4437): Adding HidService
D/AdapterServiceConfig( 4437): Adding HealthService
D/AdapterServiceConfig( 4437): Adding PanService
D/AdapterServiceConfig( 4437): Adding GattService
D/AdapterServiceConfig( 4437): Adding BluetoothMapService
,D/BluetoothManagerService(  822): Message: 20,
D/BluetoothAdapterState( 4437): make
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15ce18ae:true
,I/bluedroid( 4437): init,
I/BluetoothAdapterState( 4437): Entering OffState
,I/bte_conf( 4437): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
I/bte_conf( 4437): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 4437): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory,
,I/bte_conf( 4437): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,I/bluedroid( 4437): get_profile_interface socket
,I/bluedroid( 4437): get_profile_interface map_client,
,I/GKI_LINUX( 4437): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothManagerService(  822): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  822): Message: 40
,D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1,
D/BluetoothAdapterProperties( 4437): Address is:F8:CF:C5:D9:E5:61,
I/bluedroid( 4437): config_hci_snoop_log
D/BluetoothManagerService(  822): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  822): Stored Bluetooth name: Nexus 6
D/BluetoothAdapterProperties( 4437): Name is: Nexus 6
D/BluetoothManagerService(  822): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  822): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/BluetoothAdapterState( 4437): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 4437): Setting state to 11
I/BluetoothAdapterState( 4437): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  822): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 4437): make
,I/BluetoothBondStateMachine( 4437): StableState(): Entering Off State
,D/BluetoothAdapterService( 4437): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/HeadsetService( 4437): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 4437): classInitNative: succeeds
D/HeadsetStateMachine( 4437): make
,D/HeadsetStateMachine( 4437): max_hf_connections = 1
,I/bluedroid( 4437): get_profile_interface handsfree
,D/HeadsetStateMachine( 4437): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 4437): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
I/BluetoothAdapterState( 4437): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/A2dpService( 4437): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 4437): classInitNative: succeeds
I/bluedroid( 4437): get_profile_interface avrcp
,E/RemoteController( 4437): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 4437): classInitNative: succeeds
D/A2dpStateMachine( 4437): make
,I/bluedroid( 4437): get_profile_interface a2dp
,I/GKI_LINUX( 4437): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 4437): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 4437): classInitNative: succeeds
,D/BluetoothAdapterService( 4437): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/HidService( 4437): Received start request. Starting profile...
,I/bluedroid( 4437): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 4437): classInitNative: succeeds
D/BluetoothAdapterService( 4437): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
D/HealthService( 4437): Received start request. Starting profile...
,I/bluedroid( 4437): get_profile_interface health
,I/BluetoothPanServiceJni( 4437): classInitNative(L105): succeeds
D/BluetoothAdapterService( 4437): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/PanService( 4437): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 4437): initializeNative(L110): pan
I/bluedroid( 4437): get_profile_interface pan,
,I/BtGatt.JNI( 4437): classInitNative(L873): classInitNative: Success!,
,D/BluetoothAdapterService( 4437): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4,
,D/BtGatt.DebugUtils( 4437): handleDebugAction() action=null
,D/BtGatt.GattService( 4437): Received start request. Starting profile...
,D/BtGatt.GattService( 4437): start()
,I/bluedroid( 4437): get_profile_interface gatt
,D/BluetoothAdapterService( 4437): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/BtGatt.AdvertiseManager( 4437): advertise manager created
,D/HeadsetStateMachine( 4437): Proxy object connected
,D/BluetoothAdapterService( 4437): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@105867a4
,D/BluetoothMapService( 4437): Received start request. Starting profile...
D/BluetoothMapService( 4437): start()
,D/BluetoothMapEmailSettingsLoader( 4437): Found 0 applications
D/BluetoothMapEmailAppObserver( 4437): createReceiver()
D/BluetoothMapEmailAppObserver( 4437): initObservers()
,D/BluetoothMapEmailAppObserver( 4437): getEnabledAccountItems()
D/HeadsetStateMachine( 4437): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 4437): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 4437): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 4437): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 4437): enable
I/GKI_LINUX( 4437): gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 4437): btu_task pending for preload complete event
I/bt_hci_bdroid( 4437): init
I/bt_vendor( 4437): init
,I/bt_vnd_conf( 4437): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 4437): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,D/bt_userial( 4437): userial_init
,D/AuthorizationBluetoothService( 1528): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/bt_userial_vendor( 4437): userial vendor open: opening /dev/ttyHS0,
,I/bt_userial_vendor( 4437): device fd = 53 open,
D/bt_userial( 4437): Entering userial_read_thread()
,I/bt_hwcfg( 4437): bt vendor lib: set UART baud 3000000,
,D/bt_hwcfg( 4437): Chipset BCM4354A2,
D/bt_hwcfg( 4437): Target name = [BCM4354A2]
I/bt_hwcfg( 4437): Found patchfile: /vendor/firmware//bcm4354A2.hcd,
,I/bt_hwcfg( 4437): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 4437): Settlement delay -- 100 ms
,I/bt_hwcfg( 4437): Setting fw settlement delay to 100 
,I/bt_hwcfg( 4437): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg( 4437): Setting local bd addr to F8:CF:C5:D9:E5:61,
,I/jxcore-log( 3216): 2015-11-30T11:12:13.406Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:13.407Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:13.407Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:12:13.408Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/bt_hwcfg( 4437): vendor lib fwcfg completed
E/BluetoothServiceJni( 4437): Socket connection failed: 2
I/bt-btu  ( 4437): btu_task received preload complete event
E/BluetoothAdapterService(274229156)( 4437): Failed to connect socket
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Either the socket connection or the construction of a handshake thread failed: bt socket connect failed
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): java.io.IOException: bt socket connect failed
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:309)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: bt socket connect failed
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: bt socket connect failed [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): shutdown
I/jxcore-log( 3216): 2015-11-30T11:12:13.432Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:13.433Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:12:13.434Z SendDataConnector.js: tryAgain afer: 5000 ms.
,I/jxcore-log( 3216): 
,I/        ( 4437): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 4437): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 4437): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 4437): BTE_InitTraceLevels -- TRC_AVDT
,I/        ( 4437): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 4437): BTE_InitTraceLevels -- TRC_A2D
I/        ( 4437): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 4437): BTE_InitTraceLevels -- TRC_BTM
,I/        ( 4437): BTE_InitTraceLevels -- TRC_GAP
,I/        ( 4437): BTE_InitTraceLevels -- TRC_PAN
I/        ( 4437): BTE_InitTraceLevels -- TRC_SDP
I/        ( 4437): BTE_InitTraceLevels -- TRC_GATT
I/        ( 4437): BTE_InitTraceLevels -- TRC_SMP
I/        ( 4437): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 4437): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 4437): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2dac085 ,
E/bt-btm  ( 4437): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2dac085 
,D/BluetoothAdapterProperties( 4437): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 4437): Calling BTA_HhEnable
,E/bt-btif ( 4437): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 4437): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothAdapterProperties( 4437): Name is: Nexus 6
,D/BluetoothAdapterProperties( 4437): Scan Mode:20
,D/BluetoothAdapterProperties( 4437): Discoverable Timeout:120
D/bte_conf( 4437): Device ID record 1 : primary
D/bte_conf( 4437):   vendorId            = 000f
D/bte_conf( 4437):   vendorIdSource      = 0001
D/bte_conf( 4437):   product             = 1200
D/bte_conf( 4437):   version             = 1436
D/bte_conf( 4437):   clientExecutableURL = 
D/bte_conf( 4437):   serviceDescription  = 
D/bte_conf( 4437):   documentationURL    = 
D/bte_conf( 4437): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 4437): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 4437): ScanMode =  20
D/BluetoothAdapterProperties( 4437): State =  11
D/BluetoothAdapterProperties( 4437): Setting state to 12
I/BluetoothAdapterState( 4437): Bluetooth adapter state changed: 11-> 12
,D/BluetoothPanServiceJni( 4437): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,I/BluetoothAdapterState( 4437): Entering On State
D/BluetoothAdapterProperties( 4437): Scan Mode:21
D/BluetoothManagerService(  822): Broadcasting onBluetoothStateChange(true) to 17 receivers.
D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
,D/BluetoothAdapterProperties( 4437): Discoverable Timeout:120
D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
,D/BluetoothPan( 3988): onBluetoothStateChange(on) call bindService
,W/bt-btm  ( 4437): Stopping oneshot timer,
E/bt_h4   ( 4437): vendor lib postload completed
,D/BluetoothInputDevice( 1065): onBluetoothStateChange: up=true,
D/BluetoothPan( 3988): BluetoothPAN Proxy object connected
D/PanProfile( 3988): Bluetooth service connected
,D/BluetoothA2dp( 1065): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 1065): Proxy object connected
,D/BluetoothMap( 1065): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1065): Proxy object connected
,D/BluetoothMap( 1065): Proxy object connected
D/BluetoothHeadset( 1065): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 3988): onBluetoothStateChange: up=true
,W/bt-btm  ( 4437): Stopping oneshot timer
,D/BluetoothInputDevice( 3988): Proxy object connected
D/HidProfile( 3988): Bluetooth service connected
,D/BluetoothHeadsetClient( 1065): onBluetoothStateChange: up=true
W/bt-btm  ( 4437): Stopping oneshot timer
,E/BluetoothHeadsetClient( 1065): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
W/bt-btm  ( 4437): Stopping oneshot timer
D/BluetoothPan( 1065): onBluetoothStateChange(on) call bindService
,D/BluetoothManagerService(  822): Bluetooth Adapter name changed to Nexus 6
,D/BluetoothManagerService(  822): Stored Bluetooth name: Nexus 6
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onBluetoothAdapterScanModeChanged: Mode changed to 20
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onBluetoothAdapterScanModeChanged: Bluetooth disabled, stopping...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onBluetoothAdapterScanModeChanged: Mode changed to 21
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onBluetoothAdapterScanModeChanged: Bluetooth enabled, restarting...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): startListeningForIncomingConnections: Starting...
D/BluetoothPan( 1065): BluetoothPAN Proxy object connected
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/bt-btm  ( 4437): Stopping oneshot timer
,D/BluetoothPbap( 3988): onBluetoothStateChange: up=true
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): start: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): setState: RUNNING
,D/BluetoothA2dpSink( 1065): onBluetoothStateChange: up=true
E/BluetoothA2dpSink( 1065): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Waiting for incoming connections...
D/BluetoothAvrcpController( 1065): onBluetoothStateChange: up=true
E/BluetoothAvrcpController( 1065): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1279): onBluetoothStateChange: up=true
D/BluetoothA2dp(  822): onBluetoothStateChange: up=true
D/BluetoothA2dp(  822): Proxy object connected
D/BluetoothMap( 3988): onBluetoothStateChange: up=true
,D/BluetoothMap( 3988): Proxy object connected
D/MapProfile( 3988): Bluetooth service connected
D/BluetoothManagerService(  822): Bluetooth State Change Intent: 11 -> 12
D/BluetoothMap( 3988): getConnectedDevices()
,W/BluetoothManagerService(  822): bluetooth is recovered from error
D/BluetoothManagerService(  822): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  822): Message: 40
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
W/bt-btm  ( 4437): Stopping oneshot timer
,W/bt-btm  ( 4437): Stopping oneshot timer,
D/BluetoothMapService( 4437): onReceive
,D/BluetoothMapService( 4437): STATE_ON
D/BluetoothMapMasInstance( 4437): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 4437): MAS initSocket()
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 4437): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3988): Adding local A2DP profile
D/BluetoothMapMasInstance( 4437): Accepting socket connection...
,D/BluetoothManagerService(  822): Message: 30
,D/LocalBluetoothProfileManager( 3988): Adding local HEADSET profile
,D/BluetoothManagerService(  822): Message: 30
,W/ContextImpl( 3988): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothA2dp( 3988): Proxy object connected
D/A2dpProfile( 3988): Bluetooth service connected
,D/DockEventReceiver( 3988): finishStartingService: stopping service
,D/BluetoothPbap( 3988): Proxy object connected
,D/PbapServerProfile( 3988): Bluetooth service connected
,D/BluetoothManagerService(  822): Message: 400
D/BluetoothHeadset(  822): Proxy object connected
D/BluetoothManagerService(  822): Message: 400
D/BluetoothHeadset(  822): Proxy object connected
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 4437): getBluetoothService() called with no BluetoothManagerCallback
D/AuthorizationBluetoothService( 1528): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 4437): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 4437): Accept thread started.
,D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset( 1065): Proxy object connected
,D/BluetoothManagerService(  822): Message: 400
D/BluetoothHeadset(  822): Proxy object connected
D/BluetoothManagerService(  822): Message: 400
D/BluetoothHeadset( 1279): Proxy object connected
,D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset( 3988): Proxy object connected,
,D/HeadsetProfile( 3988): Bluetooth service connected
,V/GLSActivity( 1528): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3216): 2015-11-30T11:12:18.435Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:18.436Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
,W/bt-btif ( 4437): info:x10
D/        ( 4437): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 4437): aclStateChangeCallback: Device is NULL
,D/btif_config( 4437): btif_get_device_type: Device [b4:ce:f6:ab:a4:6a] type 1
,I/BluetoothBondStateMachine( 4437): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
,E/bt-btif ( 4437): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4437): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 4437): Entering PendingCommandState State
,W/BluetoothEventManager( 3988): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3988): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 4437): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
D/BluetoothAdapterProperties( 4437): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 4437): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,W/BluetoothEventManager( 3988): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3988): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 4437): StableState(): Entering Off State
,W/bt-btif ( 4437): new conn_srvc id:26, app_id:255
,W/bt-btif ( 4437): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4437): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Incoming connection accepted,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Incoming connection initialized (thread ID: 428)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 428)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): onBytesRead: Read 84 bytes successfully (thread ID: 428)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Got valid identity from [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT9907 B4:CE:F6:AB:A4:6A]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 428)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): removeThreadFromList: Removing thread with ID 428
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Handshake thread disposed (thread ID: 428)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onIncomingConnectionConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT9907 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 428)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT9907 B4:CE:F6:AB:A4:6A]
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT9907
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): Creating BTConnectedThread
I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 40740
,I/BtToRequestSocket( 3216): --DoOneRunRound ended,
,I/jxcore-log( 3216): 2015-11-30T11:12:22.832Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.439Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.440Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:12:23.440Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:12:23.441Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnecting: null E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Trying to connect...
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4437): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 4437): tBTM_SEC_DEV:0xa2f23eb4 rs_disc_pending=1
,W/bt-btif ( 4437): bta_dm_check_av:0
W/bt-btif ( 4437): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3216): 2015-11-30T11:12:23.664Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.668Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.673Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.677Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.684Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.689Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.694Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.700Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.733Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.738Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.742Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.756Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.793Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:23.931Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:24.067Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:24.202Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:24.337Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:24.472Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:24.610Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:24.662Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:24.724Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data,
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-30T11:12:24.763Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:24.779Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:24.813Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:24.819Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:24.854Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:24.862Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:12:24.868Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3216): 
,W/bt-btif ( 4437): info:x10
,D/        ( 4437): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 4437): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4437): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=1
,W/bt-btif ( 4437): bta_dm_check_av:0
W/bt-btif ( 4437): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 4437): process_service_search_attr_rsp
,W/bt-btif ( 4437): invalid rfc slot id: 1
I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9907
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
,I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close localHostSocket
,I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close bt in
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9907
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt socket
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
,I/jxcore-log( 3216): 2015-11-30T11:12:25.777Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,W/bt-rfcomm( 4437): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 4437): RFCOMM_DisconnectInd LCID:0x42
,D/btif_config( 4437): btif_get_device_type: Device [e0:db:10:1f:c9:5e] type 1
,I/BluetoothBondStateMachine( 4437): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
,E/bt-btif ( 4437): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 4437): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 4437): Entering PendingCommandState State
W/BluetoothEventManager( 3988): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 3988): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 4437): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 4437): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 4437): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
W/BluetoothEventManager( 3988): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 3988): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 4437): StableState(): Entering Off State
,E/bt-btm  ( 4437): tBTM_SEC_DEV:0xa2f23eb4 rs_disc_pending=0
,W/bt-btif ( 4437): bta_dm_check_av:0
W/bt-btif ( 4437): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4437): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=0
W/bt-btif ( 4437): bta_dm_check_av:0
W/bt-btif ( 4437): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4437): new conn_srvc id:26, app_id:1
,W/bt-btif ( 4437): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4437): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Outgoing connection initialized (thread ID: 433)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesWritten: 82 bytes successfully written (thread ID: 433)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Entering thread (ID: 433)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): onBytesRead: Read 82 bytes successfully (thread ID: 433)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3216): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7811 E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7811 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3216): Exiting thread (ID: 433)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7811 E0:DB:10:1F:C9:5E]
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, samsung-SM-N9005_PT7811
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3216): mHTTPPort  set to : 53521
I/BtConnectorHelper( 3216): Request socket is using : 53521
,I/BtToRequestSocket( 3216): Now accepting connections
,E/bt-btm  ( 4437): tBTM_SEC_DEV:0xa2f23eb4 rs_disc_pending=1
,W/bt-btif ( 4437): bta_dm_check_av:0
W/bt-btif ( 4437): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :53521
,I/jxcore-log( 3216): 2015-11-30T11:12:27.162Z SendDataConnector.js: CLIENT connected to 53521, error: null
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:12:27.162Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 53521
,I/BtToRequestSocket( 3216): Set local streams
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-30T11:12:27.174Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
,E/bt-btm  ( 4437): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4437): onReceive
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: HTC Desire 820
,D/btif_config_util( 4437): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 4437): dm_pm_timer expires
,W/bt-btif ( 4437): dm_pm_timer expires 0
W/bt-btif ( 4437): proc dm_pm_timer expires
,I/jxcore-log( 3216): timeout now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): dun
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): weAreDoneNow , resultArray.length: 0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): done, now sending data to server
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -- RESULT DATA {"name:":"motorola-Nexus 6_PT4432","time":1000062,"result":"TIMEOUT","sendList":[{"connections":1,"name":"E0:DB:10:1F:C9:5E","time":0,"result":"Fail"},{"connections":0,"name":"58:2A:F7:ED:96:BE","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"50:2E:6C:AC:21:50","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,
,I/jxcore-log( 3216): sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Results list does not contain any items
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): sendList failed peers count : 6 [100 %]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : E0:DB:10:1F:C9:5E, Tried : 1,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : B0:C5:59:3F:75:69, Tried : 1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): - Peer ID : 44:80:EB:7B:5A:05, Tried : 1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : F8:95:C7:87:3C:51, Tried : 1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : 7C:F9:0E:51:18:22, Tried : 1,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): sendList never tried peers count : 15 [71.42857142857143 %]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): - Peer ID : 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : 58:3F:54:73:64:C0,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : 08:EC:A9:50:75:41
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : 80:01:84:8A:B3:68
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : 50:2E:6C:AC:21:50
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): - Peer ID : 08:EC:A9:50:76:27
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:12:37.145Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): 2015-11-30T11:12:37.145Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-30T11:12:37.145Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
I/BtConnectorHelper( 3216): Disconnect outgoing peer: E0:DB:10:1F:C9:5E,
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
,I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
I/jxcore-log( 3216): 2015-11-30T11:12:37.148Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 4437): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=1
W/bt-btif ( 4437): bta_dm_check_av:0
W/bt-btif ( 4437): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 4437): unknown send() error, sent:-1, p_buf->len:3,  errno:32
W/bt-btif ( 4437): invalid rfc slot id: 6
,W/bt-btif ( 4437): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,E/bt-btm  ( 4437): tBTM_SEC_DEV:0xa2f2407c rs_disc_pending=0
W/bt-btif ( 4437): bta_dm_check_av:0
,W/bt-btif ( 4437): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4437): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4437): onReceive
,I/BTConnectionReceiver( 4028): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4028): Bluetooth Device Name: Note3-1
,D/HeadsetStateMachine( 4437): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4437): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4437): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4437): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4437): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4437): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): DBG, CoordinatorConnector command called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3216): 
I/jxcore-log( 3216): stop tests now !
I/jxcore-log( 3216): 
I/jxcore-log( 3216): stop current!
I/jxcore-log( 3216): 
I/jxcore-log( 3216): testSendData stopped
I/jxcore-log( 3216): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): setState: INITIALIZED
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:91)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onIncomingConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3216): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3216): onServerStopped
I/jxcore-log( 3216): StopBroadcasting went ok
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-30T11:15:57.042Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3216): 
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onConnectionFailed: Socket is null
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
W/jxcore-log( 3216): $$jxcore_callback_62 wasn't registered
W/jxcore-log( 3216): 
W/jxcore-log( 3216): $$jxcore_callback_62 wasn't registered
W/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector command called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:9D:93:0B\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"B0:C5:59:3F:75:69\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"44:80:EB:7B:5A:05\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"F8:95:C7:87:3C:51\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"7C:F9:0E:51:18:22\",\"time\":0,\"result\":\"Fail\"}],\"notTriedList\":[{\"connections\":0,\"name\":\"58:2A:F7:ED:96:BE\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"34:FC:EF:11:B1:66\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"34:FC:EF:11:AE:67\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"F8:95:C7:87:85:54\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"E0:DB:10:14:E2:C0\",\"tim
I/jxcore-log( 3216): ****TEST TOOK:  ms ****
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3216): 
I/jxcore-log( 3216): stop tests now !
I/jxcore-log( 3216): 
I/jxcore-log( 3216): end, event received
I/jxcore-log( 3216): 
I/jxcore-log( 3216): CoordinatorConnector close called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): The Coordinator has disconnected!
I/jxcore-log( 3216): 
I/jxcore-log( 3216): The Coordinator has closed!
I/jxcore-log( 3216): 
I/jxcore-log( 3216): stop tests now !
I/jxcore-log( 3216): 
I/jxcore-log( 3216): turning Radios off
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Toggling radios to false
I/jxcore-log( 3216): 
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  822): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@d191b5d mBinding = false
,D/BluetoothManagerService(  822): Message: 2
D/BluetoothManagerService(  822): Sending off request.
D/WifiService(  822): setWifiEnabled: false pid=3216, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterState( 4437): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 4437): Setting state to 13
I/BluetoothAdapterState( 4437): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 4437): onBluetoothDisable()
D/BluetoothManagerService(  822): Message: 60
I/BluetoothAdapterState( 4437): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  822): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 4437): onReceive
D/BluetoothMapService( 4437): STATE_TURNING_OFF
D/BluetoothMapService( 4437): MAP Service closeService in
D/BluetoothMapMasInstance( 4437): MAP Service shutdown
,V/BluetoothMapMasInstance( 4437): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 4437): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 4437): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 4437): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 4437): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 4437): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 4437): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 4437): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,D/BluetoothAdapterProperties( 4437): Scan Mode:20
D/BluetoothAdapterState( 4437): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/BtOppRfcommListener( 4437): stopping Accept Thread
W/bt-btif ( 4437): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
E/BtOppRfcommListener( 4437): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 4437): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4437): L2CAP - PSM: 0x0017 not found for deregistration
I/BtOppRfcommListener( 4437): BluetoothSocket listen thread finished
D/btif_config_util( 4437): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/ContextImpl( 3988): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/jxcore-log( 3216): Radios toggled
I/jxcore-log( 3216): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onBluetoothAdapterScanModeChanged: Mode changed to 20
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onBluetoothAdapterScanModeChanged: Bluetooth disabled, stopping...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
D/DockEventReceiver( 3988): finishStartingService: stopping service
E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
D/BluetoothPbap( 3988): Proxy object disconnected
D/PbapServerProfile( 3988): Bluetooth service disconnected
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  822): do suspend true
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63),
D/AuthorizationBluetoothService( 1528): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1528): Read error: ssl=0x9cd50c00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1528): SSL shutdown failed: ssl=0x9cd50c00: I/O error during system call, Broken pipe
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011,
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  822): scanCount==0 - aborting
,D/WifiScanningService(  822): SCAN_AVAILABLE : 1
D/RttService(  822): SCAN_AVAILABLE : 1
D/RttService(  822): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  822): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  822): DefaultState
D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3216): onWifiStateChanged: State changed to 1
E/native  (  822): do suspend true
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,I/ActivityManager(  822): Start proc 4553:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,E/WifiStateMachine(  822): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  822): MasterInitialState.processMessage what=3
,I/art     (  369): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 202us total 15.211ms
,I/NetworkMonitor( 3458): type=WIFI subType= reason=null isConnected=false
,D/Tethering(  822): MasterInitialState.processMessage what=3
E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
I/art     (  369): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 196us total 12.228ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 8.849ms
,I/wpa_supplicant( 3289): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3289): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/PhoneInterfaceManager( 1279): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1279): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,W/ResourcesManager( 4553): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,D/PhoneInterfaceManager( 1279): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1279): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,D/AndroidRuntime( 4541): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4541): CheckJNI is OFF
,D/bt_userial( 4437): RX termination
W/bt_userial( 4437): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 4437): Leaving userial_read_thread()
D/bt_userial( 4437): userial_close_reader Joined userial reader thread: 0
W/bt-btif ( 4437): ag scb idx 1 not allocated
E/bt-btif ( 4437): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 4437): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4437): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 4437): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4437): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 4437): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 4437): L2CAP - PSM: 0x0017 not found for deregistration
,D/bt_hwcfg( 4437): hw_epilog_process
I/bt_userial_vendor( 4437): device fd = 53 close
,I/Babel_SMS( 4553): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4553): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4553): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 4553): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4553): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4553): MmsConfig.loadFromResources
,E/Babel_SMS( 4553): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4553): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,D/AndroidRuntime( 4541): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  822): Killing 3216:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/Settings( 4553): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/PackageSettings(  822): Skipping PackageSetting{324c3a63 com.example.hello/10272} due to missing metadata
,I/GKI_LINUX( 4437): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 4437): GKI_exit_task 0 done
I/GKI_LINUX( 4437): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 4437): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,I/Babel_Crash( 4553): startup - clean
,I/wpa_supplicant( 3289): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  822): InitialState.processMessage what=4
,E/WifiMonitor(  822): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/Babel   ( 4553): deleted: false for 0
,I/WindowState(  822): WIN DEATH: Window{37e540b9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  822): Client connection lost with reason: 4
,W/ActivityManager(  822): Force removing ActivityRecord{357575c6 u0 com.test.thalitest/.MainActivity t24}: app died, no saved state
,V/ActivityManager(  822): Display changed displayId=0
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,D/HeadsetService( 4437): Received stop request...Stopping profile...
,D/Tethering(  822): sendTetherStateChangedBroadcast 0, 0, 0
,D/HeadsetStateMachine( 4437): Exit Disconnected: -1
,D/TaskPersister(  822): removeObsoleteFile: deleting file=24_task.xml
W/ActivityManager(  822): Spurious death for ProcessRecord{2746ef64 3216:com.test.thalitest/u0a265}, curProc for 3216: null
D/A2dpService( 4437): Received stop request...Stopping profile...
D/A2dpStateMachine( 4437): Exit Disconnected: -1
W/art     ( 4437): No such thread id for suspend: 17
D/BluetoothA2dp( 3988): Proxy object disconnected
D/A2dpProfile( 3988): Bluetooth service disconnected
,D/HidService( 4437): Received stop request...Stopping profile...
,D/BluetoothAdapterState( 4437): Stopping profile services that were post enabled
D/HeadsetStateMachine( 4437): Unbinding service...
D/BluetoothInputDevice( 3988): Proxy object disconnected
D/HidProfile( 3988): Bluetooth service disconnected
W/BluetoothHeadsetServiceJni( 4437): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 4437): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 4437): Received stop request...Stopping profile...
D/PanService( 4437): Received stop request...Stopping profile...
I/Keyboard.Facilitator( 1213): resetDictionaries() : en_US
,W/Settings( 1752): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GKI_LINUX( 4437): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 4437): GKI_exit_task 2 done
I/GKI_LINUX( 4437): GKI_shutdown(): task [A2DP-MEDIA] terminated
I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1213): run()
,D/BtGatt.DebugUtils( 4437): handleDebugAction() action=null
D/BluetoothPan( 3988): BluetoothPAN Proxy object disconnected
D/PanProfile( 3988): Bluetooth service disconnected
D/BtGatt.GattService( 4437): Received stop request...Stopping profile...
D/BtGatt.GattService( 4437): stop()
D/BtGatt.AdvertiseManager( 4437): advertise clients cleared
I/art     ( 1065): Explicit concurrent mark sweep GC freed 73633(3MB) AllocSpace objects, 0(0B) LOS objects, 17% free, 73MB/89MB, paused 742us total 40.107ms
,I/Decoder ( 1213): createOrResetDecoder
D/BluetoothMapService( 4437): Received stop request...Stopping profile...
D/BluetoothMapService( 4437): stop()
,D/BluetoothA2dp( 1065): Proxy object disconnected
D/BluetoothInputDevice( 1065): Proxy object disconnected
D/BluetoothPan( 1065): BluetoothPAN Proxy object disconnected
,D/BluetoothMapEmailAppObserver( 4437): deinitObservers()
D/BluetoothMapEmailAppObserver( 4437): removeReceiver()
,W/BluetoothHidServiceJni( 4437): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 4437): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 4437): Cleaning up Bluetooth GID callback object
D/BluetoothMap( 3988): Proxy object disconnected
W/BluetoothHealthServiceJni( 4437): Cleaning up Bluetooth Health Interface...
D/MapProfile( 3988): Bluetooth service disconnected
W/BluetoothHealthServiceJni( 4437): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 4437): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 4437): Cleaning up Bluetooth PAN callback object
,D/BluetoothMapService( 4437): MAP Service closeService in
D/BluetoothMap( 1065): Proxy object disconnected
D/BluetoothAdapterState( 4437): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 4437): Setting state to 10
I/BluetoothAdapterState( 4437): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 4437): cleanup()
D/BluetoothMapService( 4437): MAP Service closeService in
D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
I/BluetoothAdapterState( 4437): Entering OffState
D/BluetoothManagerService(  822): Broadcasting onBluetoothStateChange(false) to 19 receivers.
D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothHeadset(  822): Proxy object disconnected
D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothHeadset(  822): Proxy object disconnected
,D/BluetoothInputDevice( 1065): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1065): onBluetoothStateChange: up=false
,D/BluetoothMap( 1065): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1065): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1065): Proxy object disconnected
D/BluetoothInputDevice( 3988): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3988): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3988): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3988): Proxy object disconnected
,D/HeadsetProfile( 3988): Bluetooth service disconnected
D/BluetoothHeadsetClient( 1065): onBluetoothStateChange: up=false
E/BluetoothHeadsetClient( 1065): 
E/BluetoothHeadsetClient( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@35dbf03c
E/BluetoothHeadsetClient( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1065): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothPbap( 3988): onBluetoothStateChange: up=false
,D/BluetoothA2dpSink( 1065): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1065): 
E/BluetoothA2dpSink( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@3c3fc1c5
E/BluetoothA2dpSink( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1065): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothAvrcpController( 1065): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1065): 
E/BluetoothAvrcpController( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@378db71a
E/BluetoothAvrcpController( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1065): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothHeadset(  822): Proxy object disconnected
,D/BluetoothHeadset( 1279): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1279): Proxy object disconnected
,D/BluetoothA2dp(  822): onBluetoothStateChange: up=false
D/BluetoothMap( 3988): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  822): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  822): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService(  822): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@d191b5d mBinding = false
D/BluetoothManagerService(  822): Sending unbind request.
,D/BluetoothManagerService(  822): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1065): 1015840052: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1065): 1015840052: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 4437): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 4437): GKI_exit_task 1 done
I/GKI_LINUX( 4437): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 4437): cleanupNative: return from cleanup
D/BluetoothAdapter( 1065): 1015840052: getState() :  mService = null. Returning STATE_OFF
I/art     ( 4437): System.exit called, status: 0
I/AndroidRuntime( 4437): VM exiting with result code 0, cleanup skipped.
,I/Babel_telephony( 4553): TeleModule.launchCompleted
,W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user
,I/art     (  822): Explicit concurrent mark sweep GC freed 30682(1798KB) AllocSpace objects, 5(268KB) LOS objects, 32% free, 33MB/49MB, paused 1.556ms total 100.423ms
I/art     (  822): WaitForGcToComplete blocked for 93.815ms for cause Explicit
,I/Babel_telephony( 4553): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 4553): BAM#gBA: invalid account id: -1
W/Babel   ( 4553): BAM#gBA: invalid account id: -1
I/Babel_telephony( 4553): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user
,W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3216 uid 10265
,I/Keyboard.Facilitator( 1213): onFinishInput()
,I/ActivityManager(  822): Process com.android.bluetooth (pid 4437) has died
,I/ConfigService( 1528): onCreate
,D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1213): run()
,I/art     ( 1326): Explicit concurrent mark sweep GC freed 5052(368KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 690us total 27.088ms
,V/MusicLeanback( 3458): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1213): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = contacts
,I/art     (  822): Explicit concurrent mark sweep GC freed 6369(326KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 2.809ms total 133.207ms
,I/ActivityManager(  822): Start proc 4611:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1213): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1213): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1213): run()
I/StatsUtilsManager( 1213): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1213): shouldRecordStats() = Too Soon
,W/VideoCapabilities( 4553): Unrecognized profile 2130706433 for video/avc
,D/SprintDMReceiver( 4611): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,I/VideoCapabilities( 4553): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4553): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4553): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4553): Unrecognized profile 2130706433 for video/avc
,D/SprintDMHelper( 4611): simOperator:  IMSI: null
D/SprintDMReceiver( 4611): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1781): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
W/VideoCapabilities( 4553): Unrecognized profile 2130706433 for video/avc
,D/SystemUpdateService( 1781): onCreate
W/Settings( 4553): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/vclib   ( 4553): onServiceConnected
W/Babel   ( 4553): Attempted to change video mute state without an active call.
,D/SystemUpdateService( 1781): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/LocationOracleImpl( 4028): Best location was null
,I/VS.Container( 4028): create_recognizer
,I/SystemUpdateService( 1781): active receiver: enabled
,I/iu.Environment( 1781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 1781): num queued entries: 0
I/iu.UploadsManager( 1781): num updated entries: 0
I/iu.SyncManager( 1781): NEXT; no task
,D/Launcher.Workspace( 1326): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1326): 11683562 - stripEmptyScreens()
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 4541): System.exit called, status: 0
I/AndroidRuntime( 4541): VM exiting with result code 0.
,I/ActivityManager(  822): Start proc 4642:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 4553): connection state changed from UNKNOWN to DISCONNECTED
,I/SystemUpdateService( 1781): showing system update notification
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1781): retry (wakeup: false) in 3599912 ms
,D/SystemUpdateService( 1781): onDestroy
,I/ActivityManager(  822): Killing 3662:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/HotwordRecognitionRnr( 4028): Starting hotword detection.
,I/MicrophoneInputStream( 4028): mic_starting com.google.android.apps.gsa.speech.audio.u@a08f4cb
,I/AudioFlinger(  358): AudioFlinger's thread 0xb4d50000 ready to run
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 4028): mic_started com.google.android.apps.gsa.speech.audio.u@a08f4cb
,D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
,D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
,I/GAv4    ( 4642): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4642):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4642):   adb logcat -s GAv4
,I/HotwordWorker( 4028): onReady
,W/GAv4    ( 4642): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Search.SharedPreferencesProto( 4028): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,W/FileUtils( 4028): Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/FileBytesWriter( 4028): Failed to write new file: loracle.new
W/LocationOracleImpl( 4028): Best location was null
,E/SharedPreferencesImpl( 4642): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4642): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/Icing   ( 1781): Received bad json for section weights override -- ignoring.
W/Icing   ( 1781): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 1781): Received bad json for section weights override -- ignoring.
W/Icing   ( 1781): Received bad json for corpus context scoring override -- ignoring.
,E/SharedPreferencesImpl( 4642): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/FileUtils( 4028): Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/FileBytesWriter( 4028): Failed to write new file: loracle.new
W/LocationOracleImpl( 4028): Best location was null
,W/GAv4    ( 4642): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4642): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4642): Failed to open database '/data/data/com.google.android.apps.magazines/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4642): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4642): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4642): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.analytics.internal.zzj$zza.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.analytics.internal.zzj.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.analytics.internal.zzj.zzb(Unknown Source)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.analytics.internal.zzj.zzie(Unknown Source)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.analytics.internal.zzj.isEmpty(Unknown Source)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.analytics.internal.zzl.zzis(Unknown Source)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.analytics.internal.zzl$3.run(Unknown Source)
E/SQLiteDatabase( 4642): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4642): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4642): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4642): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4642): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.measurement.MeasurementService$zzc.run(Unknown Source)
E/GAv4    ( 4642): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 4642): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4642): Failed to open database '/data/data/com.google.android.apps.magazines/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4642): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4642): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4642): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4642): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.analytics.internal.zzj$zza.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.analytics.internal.zzj.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.analytics.internal.zzj.zzb(Unknown Source)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.analytics.internal.zzj.zzie(Unknown Source)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.analytics.internal.zzj.isEmpty(Unknown Source)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.analytics.internal.zzl.zzis(Unknown Source)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.analytics.internal.zzl$3.run(Unknown Source)
E/SQLiteDatabase( 4642): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4642): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4642): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4642): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4642): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4642): 	at com.google.android.gms.measurement.MeasurementService$zzc.run(Unknown Source)
E/GAv4    ( 4642): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4642): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4642): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/GAv4    ( 4642): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4642): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 4642): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4642): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4642): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4642): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4642): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/NSDepend( 4642): Could not load library: pdflib.dex.jar
E/NSDepend( 4642): java.io.FileNotFoundException: /data/data/com.google.android.apps.magazines/app_dex/pdflib.dex.jar: open failed: EROFS (Read-only file system)
E/NSDepend( 4642): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/NSDepend( 4642): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/NSDepend( 4642): 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:202)
E/NSDepend( 4642): 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:190)
E/NSDepend( 4642): 	at com.google.common.io.ByteSink.writeFrom(ByteSink.java:138)
E/NSDepend( 4642): 	at com.google.apps.dots.android.newsstand.NSDepend.dynamicallyLoadLibrary(NSDepend.java:1368)
E/NSDepend( 4642): 	at com.google.apps.dots.android.newsstand.NSDepend.getClassLoaderForJar(NSDepend.java:1315)
E/NSDepend( 4642): 	at com.google.apps.dots.android.newsstand.NSDepend$3.doInBackground(NSDepend.java:1348)
E/NSDepend( 4642): 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:56)
E/NSDepend( 4642): 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:52)
E/NSDepend( 4642): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/NSDepend( 4642): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/NSDepend( 4642): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/NSDepend( 4642): 	at com.google.android.libraries.bind.async.Queue$3$1.run(Queue.java:103)
E/NSDepend( 4642): 	at java.lang.Thread.run(Thread.java:818)
E/NSDepend( 4642): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/NSDepend( 4642): 	at libcore.io.Posix.open(Native Method)
E/NSDepend( 4642): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/NSDepend( 4642): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/NSDepend( 4642): 	... 14 more
,I/WebViewFactory( 4642): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,E/QMI_FW  (  822): xport_send: Sendto failed for port 4096
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1659516179
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/LibraryLoader( 4642): Time to load native libraries: 1 ms (timestamps 9793-9794)
,I/LibraryLoader( 4642): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4642): Binding Chromium to main looper Looper (main, tid 1) {9c6752a},
I/LibraryLoader( 4642): Expected native library version number "",actual native library version number ""
,I/chromium( 4642): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4642): Initializing chromium process, singleProcess=true
,W/art     ( 4642): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4642): ApplicationContext is null in ApplicationStatus
,W/chromium( 4642): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4642): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4642): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 4642): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 4642): Requires BLUETOOTH permission
,I/NSApplication( 4642): Starting up...
,E/SQLiteLog( 2989): (3850) statement aborts at 61: [UPDATE media_record SET upload_state=? WHERE upload_account_id != -1 AND upload_state = 200] disk I/O error
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,I/ActivityManager(  822): Start proc 4713:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver

```
