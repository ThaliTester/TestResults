#### Test 50650278e3ff7c2_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 26021(1388KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.602ms total 48.847ms
I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2662): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2662): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2662): [1] 5.onFinished: Scheduling replication attempt 4.
D/AndroidRuntime( 3147): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3147): CheckJNI is OFF
D/AndroidRuntime( 3147): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  826): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  826): addAppToken: AppWindowToken{218a8400 token=Token{349ba83 ActivityRecord{96f7d32 u0 com.test.thalitest/.MainActivity t26}}} to stack=1 task=26 at 0
D/AndroidRuntime( 3147): Shutting down VM
I/HotwordDetector( 1506): Closing mic
I/MicrophoneInputStream( 1506): mic_close com.google.android.apps.gsa.speech.audio.u@3e20661b
V/WindowManager(  826): Adding window Window{4cc0af5 u0 Starting com.test.thalitest} at 2 of 7 (after Window{38fd798a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  826): Start proc 3162:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1506): Hotword detection finished
I/HotwordRecognitionRnr( 1506): Stopping hotword detection.
I/ActivityManager(  826): Killing 2621:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  826): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1700975891
E/LocSvc_IzatApiV02(  826): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  826): Killing 2753:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/kickstart(  873): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  873): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  873): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3162): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3162): Time to load native libraries: 2 ms (timestamps 7378-7380)
,I/LibraryLoader( 3162): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3162): Binding Chromium to main looper Looper (main, tid 1) {3a7c8cb5}
,I/LibraryLoader( 3162): Expected native library version number "",actual native library version number ""
,I/chromium( 3162): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3162): Initializing chromium process, singleProcess=true
,W/art     ( 3162): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3162): ApplicationContext is null in ApplicationStatus
,W/chromium( 3162): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3162): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3162): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3162): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3162): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  826): Message: 20
D/BluetoothManagerService(  826): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c769b65:true
,D/BluetoothAdapter( 3162): 329350039: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3162): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3162): onDetachedFromWindow called when already detached. Ignoring,
,I/art     (  826): Explicit concurrent mark sweep GC freed 18926(875KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.384ms total 56.755ms
,D/SystemWebViewEngine( 3162): CordovaWebView is running on device made by: motorola
,W/art     ( 3162): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3162): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3162): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3162): Validating map...
,V/WindowManager(  826): Adding window Window{3ede27d5 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{4cc0af5 u0 Starting com.test.thalitest})
,W/chromium( 3162): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,I/OpenGLRenderer( 3162): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3162): Enabling debug mode 0
,I/ActivityManager(  826): Displayed com.test.thalitest/.MainActivity: +942ms
I/Keyboard.Facilitator( 1209): onFinishInput()
,W/BindingManager( 3162): Cannot call determinedVisibility() - never saw a connection for the pid: 3162
,D/JsMessageQueue( 3162): Set native->JS mode to OnlineEventsBridgeMode
,I/kickstart(  873): STATUS: Received file 'm9kefs2'
I/kickstart(  873): STATUS: 950272 bytes transferred in 0.994059 seconds
I/kickstart(  873): STATUS: Successfully downloaded files from target 
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  873): STATUS: Sahara protocol completed
,D/jxcore_app_log( 3162): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576265600
D/JX-Cordova( 3162): jxcore cordova android initializing
,W/jxcore-log( 3162): Initializing JXcore engine
W/jxcore-log( 3162): JXcore engine is ready
,W/jxcore-log( 3162): Starting JXcore engine
,W/.test.thalitest( 3162): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12926]" dev="sockfs" ino=12926 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3162): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3162): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10526]" dev="sockfs" ino=10526 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3162): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21854]" dev="sockfs" ino=21854 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3162): Platform android
W/jxcore-log( 3162): 
W/jxcore-log( 3162): Process ARCH arm
W/jxcore-log( 3162): 
,I/jxcore-log( 3162): JXcore Cordova bridge is ready!
I/jxcore-log( 3162): 
W/jxcore-log( 3162): JXcore engine is started
,I/Choreographer( 3162): Skipped 130 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3162): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3162): Toggling radios to true
I/jxcore-log( 3162): 
,D/BluetoothManagerService(  826): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  826): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  826): Message: 1
D/BluetoothManagerService(  826): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  826): setWifiEnabled: true pid=3162, uid=10265
E/WifiService(  826): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  826): New client listening to asynchronous messages
,D/SoftapController(  354): Softap fwReload - Ok
I/jxcore-log( 3162): Radios toggled
I/jxcore-log( 3162): 
,D/CommandListener(  354): Setting iface cfg
D/CommandListener(  354): Trying to bring down wlan0
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,E/WifiMonitor(  826): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown,
,I/ActivityManager(  826): Start proc 3220:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
D/BluetoothManagerService(  826): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/WifiMonitor(  826): startMonitoring(wlan0) with mConnected = false
I/jxcore-log( 3162): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3162): 
,I/jxcore-log( 3162): Perf Test app loaded loaded
I/jxcore-log( 3162): 
,I/Choreographer( 3162): Skipped 66 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3162): check test folder
I/jxcore-log( 3162): 
,I/jxcore-log( 3162): found test : ./testFindPeers.js
I/jxcore-log( 3162): 
,I/wpa_supplicant( 3219): Successfully initialized wpa_supplicant
,I/jxcore-log( 3162): found test : ./testSendData.js
I/jxcore-log( 3162): 
,I/ActivityManager(  826): Start proc 3236:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,W/ResourcesManager( 3220): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3219): rfkill: Cannot open RFKILL control device
,I/chromium( 3162): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  826): Start proc 3263:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  826): Killing 2786:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/AdapterServiceConfig( 3220): Adding HeadsetService
D/AdapterServiceConfig( 3220): Adding A2dpService
D/AdapterServiceConfig( 3220): Adding HidService
D/AdapterServiceConfig( 3220): Adding HealthService
D/AdapterServiceConfig( 3220): Adding PanService
D/AdapterServiceConfig( 3220): Adding GattService
D/AdapterServiceConfig( 3220): Adding BluetoothMapService
,D/BluetoothManagerService(  826): Message: 20
D/BluetoothManagerService(  826): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@339b045:true
,D/BluetoothAdapterState( 3220): make
,I/bluedroid( 3220): init
I/BluetoothAdapterState( 3220): Entering OffState
,I/bte_conf( 3220): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3220): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3220): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,I/bte_conf( 3220): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3220): get_profile_interface socket
I/bluedroid( 3220): get_profile_interface map_client
I/GKI_LINUX( 3220): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3220): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  826): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  826): Stored Bluetooth name: Nexus 6
,D/BluetoothManagerService(  826): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  826): Message: 40
D/BluetoothManagerService(  826): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 3220): Name is: Nexus 6
I/bluedroid( 3220): config_hci_snoop_log
,D/BluetoothManagerService(  826): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  826): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3220): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3220): Setting state to 11
I/BluetoothAdapterState( 3220): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  826): Message: 60
D/BluetoothManagerService(  826): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  826): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3220): make
,I/BluetoothBondStateMachine( 3220): StableState(): Entering Off State
,I/BluetoothAdapterState( 3220): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e53f4a
,D/HeadsetService( 3220): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3220): classInitNative: succeeds
D/HeadsetStateMachine( 3220): make
,D/HeadsetStateMachine( 3220): max_hf_connections = 1
I/bluedroid( 3220): get_profile_interface handsfree
,D/HeadsetStateMachine( 3220): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e53f4a
,D/BluetoothA2dp(  826): Proxy object connected
D/BluetoothA2dp( 1060): Proxy object connected
D/A2dpService( 3220): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3220): classInitNative: succeeds
I/bluedroid( 3220): get_profile_interface avrcp
,E/RemoteController( 3220): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 3220): classInitNative: succeeds
D/A2dpStateMachine( 3220): make
,I/bluedroid( 3220): get_profile_interface a2dp
,I/GKI_LINUX( 3220): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothHidServiceJni( 3220): classInitNative: succeeds
,D/BluetoothAdapterService( 3220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e53f4a
D/A2dpStateMachine( 3220): Enter Disconnected: -2
,D/BluetoothInputDevice( 1060): Proxy object connected
,D/HidService( 3220): Received start request. Starting profile...
,I/bluedroid( 3220): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3220): classInitNative: succeeds
D/BluetoothAdapterService( 3220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e53f4a
D/HealthService( 3220): Received start request. Starting profile...
,I/bluedroid( 3220): get_profile_interface health
,I/BluetoothPanServiceJni( 3220): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e53f4a
D/BluetoothPan( 1060): BluetoothPAN Proxy object connected
D/PanService( 3220): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3220): initializeNative(L110): pan
I/bluedroid( 3220): get_profile_interface pan
I/BtGatt.JNI( 3220): classInitNative(L873): classInitNative: Success!
,D/BluetoothAdapterService( 3220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e53f4a
D/BtGatt.DebugUtils( 3220): handleDebugAction() action=null
,D/BtGatt.GattService( 3220): Received start request. Starting profile...
D/BtGatt.GattService( 3220): start()
I/bluedroid( 3220): get_profile_interface gatt
D/BluetoothAdapterService( 3220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e53f4a
D/BtGatt.AdvertiseManager( 3220): advertise manager created
,D/BluetoothAdapterService( 3220): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e53f4a
,D/BluetoothMap( 1060): Proxy object connected
D/BluetoothMapService( 3220): Received start request. Starting profile...
D/BluetoothMapService( 3220): start()
,D/BluetoothMapEmailSettingsLoader( 3220): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3220): createReceiver()
,D/BluetoothMapEmailAppObserver( 3220): initObservers()
,D/BluetoothMapEmailAppObserver( 3220): getEnabledAccountItems()
,D/HeadsetStateMachine( 3220): Proxy object connected
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3220): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 3220): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3220): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3220): enable
I/bt_hci_bdroid( 3220): init
I/GKI_LINUX( 3220): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3220): btu_task pending for preload complete event
,I/bt_vendor( 3220): init
I/bt_vnd_conf( 3220): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3220): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3220): userial_init
,I/bt_userial_vendor( 3220): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3220): device fd = 53 open
D/bt_userial( 3220): Entering userial_read_thread()
,I/bt_hwcfg( 3220): bt vendor lib: set UART baud 3000000
,I/ActivityManager(  826): Start proc 3306:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  826): Killing 2720:com.google.android.gm/u0a78 (adj 15): empty #17
,D/bt_hwcfg( 3220): Chipset BCM4354A2
D/bt_hwcfg( 3220): Target name = [BCM4354A2]
I/bt_hwcfg( 3220): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,D/Tethering(  826): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3219): rfkill: Cannot open RFKILL control device
,E/wpa_supplicant( 3219): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  826): Loading config and enabling all networks 
,D/WifiService(  826): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1d528c6}
,I/ActivityManager(  826): Killing 2300:com.google.android.calendar/u0a37 (adj 15): empty #17
,E/WifiConfigStore(  826): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  826): Setting external_sim to 1
,W/Settings( 2576): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  826): Setting OUI to 92-68-C3
,I/WifiNative-HAL(  826): startHal
,D/wifi    (  826): setting scan oui 0xaee8d4f0
D/WifiHAL (  826): Sending mac address OUI
,I/bt_hwcfg( 3220): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3220): Settlement delay -- 100 ms
I/bt_hwcfg( 3220): Setting fw settlement delay to 100 
,I/ActivityManager(  826): Start proc 3324:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,E/WifiStateMachine(  826): cancelDelayedScan -> 1
,W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
,D/WifiScanningService(  826): SCAN_AVAILABLE : 3
D/RttService(  826): SCAN_AVAILABLE : 3
,D/WifiScanningService(  826): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  826): startHal
D/wifi    (  826): getting scan capabilities on interface[0] = 0xaee8d4f0
D/WifiHAL (  826): Creating message to get scan capablities; iface = 5
D/WifiHAL (  826): In GetCapabilities::handleResponse
,D/WifiHAL (  826): Id = 0, subcmd = 0, len = 28, expected len = 32
,D/WifiScanningService(  826): StartedState
,D/RttService(  826): DefaultState got{ when=-4ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 352us total 29.921ms
,D/CommandListener(  354): Setting iface cfg
E/WifiP2pService(  826): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  826): startMonitoring(p2p0) with mConnected = true
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 435us total 18.883ms
,I/wpa_supplicant( 3219): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/bt_hwcfg( 3220): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3220): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 347us total 17.826ms,
D/WifiNative-HAL(  826): p2pGetDeviceAddress
,E/native  (  826): do suspend false
,D/WifiNative-HAL(  826): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/bt_hwcfg( 3220): vendor lib fwcfg completed
I/bt-btu  ( 3220): btu_task received preload complete event
,I/        ( 3220): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 3220): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3220): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3220): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3220): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3220): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3220): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3220): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3220): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3220): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3220): BTE_InitTraceLevels -- TRC_SDP
,I/        ( 3220): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3220): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3220): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3220): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3220): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2df3085 ,
E/bt-btm  ( 3220): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2df3085 
,I/PowerManagerService(  826): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  826): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/StrictMode( 3324): StrictMode policy violation; ~duration=188 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3324): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3324): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3324): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3324): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3324): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3324): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3324): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3324): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3324): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3324): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3324): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3324): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3324): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3324): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3324): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3324): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3324): StrictMode policy violation; ~duration=188 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3324): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3324): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3324): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3324): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3324): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3324): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3324): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3324): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3324): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3324): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3324): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3324): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3324): StrictMode policy violation; ~duration=186 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3324): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3324): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3324): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3324): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3324): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3324): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3324): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3324): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3324): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3324): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3324): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3324): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3324): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3324): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3324): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3324): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3324): StrictMode policy violation; ~duration=182 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3324): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3324): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3324): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3324): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3324): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3324): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3324): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3324): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3324): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3324): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3324): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3324): StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3324): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3324): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3324): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3324): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3324): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoade,r.java:77)
D/StrictMode( 3324): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3324): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3324): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3324): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3324): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3324): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3324): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3324): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3324): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3324): StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3324): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3324): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3324): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3324): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3324): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3324): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3324): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3324): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3324): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3324): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3324): # via Binder call with stack:
D/StrictMode( 3324): android.os.StrictMode$LogStackTrace
D/StrictMode( 3324): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3324): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3324): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3324): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3324): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3324): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3324): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3324): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3324): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3324): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java,:1012)
D/StrictMode( 3324): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3324): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3324): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3324): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3324): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3324): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3324): StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3324): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3324): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3324): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3324): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3324): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3324): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3324): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3324): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3324): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3324): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3324): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3324): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3324): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3324): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3324): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3324): StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3324): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3324): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3324): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3324): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3324): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3324): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication,.onCreate(PG:84)
D/StrictMode( 3324): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3324): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3324): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3324): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3324): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3324): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3324): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3324): StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3324): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3324): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3324): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3324): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3324): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3324): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3324): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3324): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3324): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3324): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3324): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3324): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3324): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3324): StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3324): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3324): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3324): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3324): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3324): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3324): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3324): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3324): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3324): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3324): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3324): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3324): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3324): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3324): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3324): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3324): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3324): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3324): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3324): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3324): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3324): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3324): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/PermissionCache(  262): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (156 us)
W/com.google.a.a.a.b.a( 3324): Application name is not set. Call Builder#setApplicationName.
D/BluetoothAdapterProperties( 3220): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
E/bt-btif ( 3220): Calling BTA_HhEnable
E/bt-btif ( 3220): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3220): Address is:F8:CF:C5:D9:E5:61
D/BluetoothAdapterProperties( 3220): Name is: Nexus 6
D/BluetoothManagerService(  826): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  826): Stored Bluetooth name: Nexus 6
D/BluetoothAdapterProperties( 3220): Scan Mode:20
D/BluetoothAdapterProperties( 3220): Discoverable Timeout:120
,D/bte_conf( 3220): Device ID record 1 : primary
D/bte_conf( 3220):   vendorId            = 000f
D/bte_conf( 3220):   vendorIdSource      = 0001
D/bte_conf( 3220):   product             = 1200
D/bte_conf( 3220):   version             = 1436
D/bte_conf( 3220):   clientExecutableURL = 
D/bte_conf( 3220):   serviceDescription  = 
D/bte_conf( 3220):   documentationURL    = 
D/bte_conf( 3220): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3220): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3220): ScanMode =  20
D/BluetoothAdapterProperties( 3220): State =  11
D/BluetoothPanServiceJni( 3220): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 3220): Setting state to 12
I/BluetoothAdapterState( 3220): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  826): Message: 60
D/BluetoothManagerService(  826): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  826): Broadcasting onBluetoothStateChange(true) to 13 receivers.
I/BluetoothAdapterState( 3220): Entering On State
D/BluetoothAdapterProperties( 3220): Scan Mode:21
D/BluetoothAdapterProperties( 3220): Discoverable Timeout:120
D/BluetoothHeadset( 1268): onBluetoothStateChange: up=true
D/BluetoothManagerService(  826): Creating new ProfileServiceConnections object for profile: 1
D/BluetoothAvrcpController( 1060): onBluetoothStateChange: up=true
E/BluetoothAvrcpController( 1060): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothA2dp(  826): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1060): onBluetoothStateChange: up=true
D/BluetoothHeadsetClient( 1060): onBluetoothStateChange: up=true
E/BluetoothHeadsetClient( 1060): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
D/BluetoothMap( 1060): onBluetoothStateChange: up=true
D/BluetoothA2dpSink( 1060): onBluetoothStateChange: up=true
E/BluetoothA2dpSink( 1060): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
D/BluetoothInputDevice( 1060): onBluetoothStateChange: up=true
D/BluetoothHeadset(  826): onBluetoothStateChange: up=true
D/BluetoothPan( 1060): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset(  826): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1060): onBluetoothStateChange: up=true
D/BluetoothHeadset(  826): onBluetoothStateChange: up=true
D/BluetoothManagerService(  826): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  826): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 3220): onReceive
D/BluetoothMapService( 3220): STATE_ON
D/BluetoothMapMasInstance( 3220): Map Service startRfcommSocketListener
D/BluetoothManagerService(  826): Message: 40
D/BluetoothManagerService(  826): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapMasInstance( 3220): MAS initSocket()
D/BluetoothManagerService(  826): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
E/bt_h4   ( 3220): vendor lib postload completed
W/bt-btm  ( 3220): Stopping oneshot timer
W/BluetoothAdapter( 3220): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothMapMasInstance( 3220): Accepting socket connection...
D/BluetoothManagerService(  826): Message: 20
D/BluetoothManagerService(  826): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e9f4f76:true
W/bt-btm  ( 3220): Stopping oneshot timer
I/ActivityManager(  826): Killing 2820:com.google.android.music:main/u0a66 (adj 15): empty #17
W/bt-btm  ( 3220): Stopping oneshot timer
,W/bt-btm  ( 3220): Stopping oneshot timer
,W/bt-btm  ( 3220): Stopping oneshot timer
,W/bt-btm  ( 3220): Stopping oneshot timer
,W/bt-btm  ( 3220): Stopping oneshot timer
,D/BluetoothManagerService(  826): Message: 400
,D/BluetoothHeadset( 1268): Proxy object connected
,D/BluetoothManagerService(  826): Message: 400
,D/BluetoothHeadset(  826): Proxy object connected
,D/BluetoothManagerService(  826): Message: 400
,D/BluetoothHeadset(  826): Proxy object connected
D/BluetoothManagerService(  826): Message: 400
,D/BluetoothHeadset( 1060): Proxy object connected
,D/BluetoothManagerService(  826): Message: 400
,D/BluetoothHeadset(  826): Proxy object connected
,D/AuthorizationBluetoothService( 1408): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  826): Message: 20
D/BluetoothManagerService(  826): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30000968:true
,D/BluetoothManagerService(  826): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3220): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3306): Adding local A2DP profile
,D/AuthorizationBluetoothService( 1408): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService(  826): Message: 30
,D/LocalBluetoothProfileManager( 3306): Adding local HEADSET profile
,D/BluetoothManagerService(  826): Message: 30
,D/BluetoothManagerService(  826): Message: 30
,D/BluetoothManagerService(  826): Message: 30
,D/BluetoothManagerService(  826): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/LocalBluetoothProfileManager( 3306): Adding local MAP profile
W/BluetoothAdapter( 3220): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3220): Accept thread started.
,D/BluetoothMap( 3306): Create BluetoothMap proxy object
,D/BluetoothManagerService(  826): Message: 30
,D/BluetoothManagerService(  826): Message: 30
,D/LocalBluetoothProfileManager( 3306): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3306): finishStartingService: stopping service
,D/BluetoothA2dp( 3306): Proxy object connected
,D/A2dpProfile( 3306): Bluetooth service connected
,D/BluetoothInputDevice( 3306): Proxy object connected
,D/HidProfile( 3306): Bluetooth service connected
,D/BluetoothPan( 3306): BluetoothPAN Proxy object connected
,D/PanProfile( 3306): Bluetooth service connected
D/BluetoothMap( 3306): Proxy object connected
D/MapProfile( 3306): Bluetooth service connected
D/BluetoothMap( 3306): getConnectedDevices()
,D/BluetoothPbap( 3306): Proxy object connected
,D/PbapServerProfile( 3306): Bluetooth service connected
,D/BluetoothManagerService(  826): Message: 400
,D/BluetoothHeadset( 3306): Proxy object connected
,D/HeadsetProfile( 3306): Bluetooth service connected
,I/DisplayManagerService(  826): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  826): Display changed displayId=0
,D/SurfaceFlinger(  262): Set power mode=0, type=0 flinger=0xb6082000
,D/qdhwcomposer(  262): hwc_setPowerMode: Setting mode 0 on display: 0
,I/qdhwcomposer(  262): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  262): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  826): Excessive delay in setPowerMode(): 268ms
,I/DreamManagerService(  826): Entering dreamland.
,I/PowerManagerService(  826): Dozing...
,I/DreamController(  826): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  826): cancelDelayedScan -> 4,
,E/native  (  826): do suspend false
,I/Keyboard.Facilitator( 1209): onFinishInput()
,E/WifiStateMachine(  826): cancelDelayedScan -> 6
,E/native  (  826): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  826): WifiStateMachine Disconnected CMD_START_SCAN source -2 5, 6 -> obsolete
,I/art     (  826): Explicit concurrent mark sweep GC freed 27656(1449KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 3.083ms total 96.412ms
,I/wpa_supplicant( 3219): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 3219): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 3219): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 3219): wlan0: Failed to initiate AP scan
,I/jxcore-log( 3162): BLE supported!!
I/jxcore-log( 3162): 
,I/wpa_supplicant( 3219): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 3219): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 3219): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 3219): wlan0: Failed to initiate AP scan
,D/WifiService(  826): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1d528c6}
,I/wpa_supplicant( 3219): wlan0: Reject scan trigger since one is already pending
,W/wpa_supplicant( 3219): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 3219): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 3219): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 3219): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 3219): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 3219): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 3219): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 3219): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,I/wpa_supplicant( 3219): wlan0: Trying to associate with SSID 'NG7005g'
,E/WifiConfigStore(  826):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  826):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiConfigStore(  826): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  826): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  826): WifiStateMachine Disconnected CMD_START_SCAN source -2 2, 6 -> obsolete
,E/WifiStateMachine(  826): WifiStateMachine Disconnected CMD_START_SCAN source -2 3, 6 -> obsolete
,I/wpa_supplicant( 3219): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3219): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3219): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  826): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  826): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  826): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  826): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  826): Start Dhcp Watchdog 1
,E/WifiStateMachine(  826):  WifiLinkLayerStats: 
E/WifiStateMachine(  826):  my bss beacon rx: 1
E/WifiStateMachine(  826):  RSSI mgmt: -50
E/WifiStateMachine(  826):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  826):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  826):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  826):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  826):  on_time : 426 tx_time=75 rx_time=390 scan_time=0
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/native  (  826): do suspend false
,E/WifiStateMachine(  826): scanCount==0 - aborting
,I/dhcpcd  ( 3380): version 5.5.6 starting,
,I/dhcpcd  ( 3380): wlan0: broadcasting for a lease
,I/dhcpcd  ( 3380): wlan0: offered 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3380): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3380): wlan0: leased 192.168.1.122 for 86400 seconds
,E/native  (  826): do suspend true
,D/ConnectivityService(  826): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  826): Adding iface wlan0 to network 100
,E/WifiStateMachine(  826): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  826): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  826): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  826): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  826): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  826): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  826): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  826): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  826): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  826): Connected
,D/ConnectivityService(  826): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  826):    accepting network in place of null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  826): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  826): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  826): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  826): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  826): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100],
D/CSLegacyTypeTracker(  826): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  826): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1060): CM callback handler got msg 524290
D/ConnectivityService(  826): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  826): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1268): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1268): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,V/BackupManagerService(  826): Scheduling immediate backup pass
,D/TelephonyManager(  826): getDataEnabled: retVal=false
,D/AlarmManagerService(  826): Setting time of day to sec=1450100391
W/AlarmManagerService(  826): Unable to set rtc to 1450100391: Invalid argument
,I/ActivityManager(  826): Start proc 3418:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,D/NetworkChangeNotifierAutoDetect( 1506): Network connectivity changed, type is: 2
,V/BackupManagerService(  826): Running a backup pass
,V/BackupManagerService(  826): clearing pending backups
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  826): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 14 Dec 2015 13:39:51 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450100391815], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450100391798]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  826): Validated
D/ConnectivityService(  826): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  826): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  826): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  826): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  826): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1060): CM callback handler got msg 524290
D/ConnectivityService(  826): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/GpsLocationProvider(  826): No APN found to select.
,V/PerformBackupTask(  826): Beginning backup of 14 targets
,D/PerformBackupTask(  826): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  826): doBackup() invoked
,I/PMBA    (  826): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/BackupRestoreController(  826): Getting widget state for user: 0
,D/GpsLocationProvider(  826): NTP server returned: 1450100391798 (Mon Dec 14 14:39:51 GMT+01:00 2015) reference: 175728 certainty: 9 system time offset: -81
,W/GmsBackupTransport( 1702): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1702): starting performBackup for @pm@
,V/GmsBackupTransport( 1702): performBackup done for @pm@
,I/MusicStore( 3418): Database version: 120
,I/GoogleURLConnFactory( 1408): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1729): [CredentialSyncAdapter] Unknown sync event.
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 15679(931KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 1.009ms total 24.263ms
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1408): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1408): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1408): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/BackupManagerService(  826): Now staging backup of com.google.android.talk
,D/BackupManagerService(  826): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  826): Now staging backup of com.android.providers.settings
,W/DriveInitializer( 1729): Background init thread started
,I/ConfigService( 1408): onCreate
,I/ConfigFetchService( 1729): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1729): running network task: configservice_periodic
,E/WakeLock( 1729): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1729): launchTask
,D/BackupManagerService(  826): Now staging backup of com.android.sharedstoragebackup
,I/ConfigFetchService( 1729): service connected
,D/ConfigFetchService( 1729): ConfigApi connection successful.
,V/ConfigFetchTask( 1729): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UHPpVI85QKbBzbUdBMuil-KCj4NqO8YBmUkNyNcVzxB9iB897zyhY8RdEl48KNhMZyyltO-F1I1fHyPZ-d-EGU6na8sEmQKal9SG0wH51uLJRXwz3DszuS_0gbpcEYeJR17yy-dhl4EMG2_K11-vrmv0JvMZdiS07OoA6rg8OCGL6x4wqB9-X1uE1GP77E1E3c52M5mLGyfSiUxLzSveJ8IhR0m5eYqMwKnNoj14OB8nijBW4
,D/BackupManagerService(  826): Now staging backup of com.google.android.gm
,D/BackupManagerService(  826): Now staging backup of com.android.providers.userdictionary
,W/ResourcesManager( 3418): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3418): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/DriveInitializer( 1729): Awaiting to be initialized
,D/BackupManagerService(  826): Now staging backup of com.android.nfc
,D/BackupManagerService(  826): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  826): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  826): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  826): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  826): Now staging backup of com.android.vending
,D/BackupManagerService(  826): Now staging backup of android
,W/DriveInitializer( 1729): Background init thread ended
,D/BackupManagerService(  826): Now staging backup of com.google.android.googlequicksearchbox
,V/JNIHelp ( 3418): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GoogleURLConnFactory( 1729): Using platform SSLCertificateSocketFactory
I/GmsBackupTransport( 1702): Next backup will happen in 43199864 millis.
,I/BackupManagerService(  826): Backup pass finished.
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProviderInstaller( 3418): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3418): GMSCore installation verified
E/HttpOperation( 2926): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2926): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2926): 	at jdm.a(PG:82)
E/HttpOperation( 2926): 	at jcs.o(PG:406)
E/HttpOperation( 2926): 	at jcn.a(PG:1379)
E/HttpOperation( 2926): 	at jcs.i(PG:143)
E/HttpOperation( 2926): 	at blb.a(PG:3937)
E/HttpOperation( 2926): 	at czp.a(PG:18188)
E/HttpOperation( 2926): 	at czp.a(PG:9081)
E/HttpOperation( 2926): 	at czq.run(PG:1686)
E/HttpOperation( 2926): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2926): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2926): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2926): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2926): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2926): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2926): 	at jdj.a(PG:4091)
E/HttpOperation( 2926): 	at jdj.a(PG:1125)
E/HttpOperation( 2926): 	at jdm.a(PG:77)
E/HttpOperation( 2926): 	... 12 more
E/HttpOperation( 2926): Caused by: faj: BadAuthentication
E/HttpOperation( 2926): 	at fal.a(PG:38)
E/HttpOperation( 2926): 	at jdj.a(PG:4089)
E/HttpOperation( 2926): 	... 14 more
,I/ConfigStore( 3418): Config Database version: 1
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  826): Start proc 3480:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,E/HttpOperation( 2926): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2926): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2926): 	at jdm.a(PG:82)
E/HttpOperation( 2926): 	at jcs.o(PG:406)
E/HttpOperation( 2926): 	at jcn.a(PG:1379)
E/HttpOperation( 2926): 	at jcs.i(PG:143)
E/HttpOperation( 2926): 	at hec.a(PG:42)
E/HttpOperation( 2926): 	at hee.a(PG:102)
E/HttpOperation( 2926): 	at czr.a(PG:65)
E/HttpOperation( 2926): 	at kka.a(PG:108)
E/HttpOperation( 2926): 	at czp.a(PG:19176)
E/HttpOperation( 2926): 	at czp.a(PG:9081)
E/HttpOperation( 2926): 	at czq.run(PG:1686)
E/HttpOperation( 2926): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2926): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2926): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2926): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2926): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2926): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2926): 	at jdj.a(PG:4091)
E/HttpOperation( 2926): 	at jdj.a(PG:1125)
E/HttpOperation( 2926): 	at jdm.a(PG:77)
E/HttpOperation( 2926): 	... 15 more
E/HttpOperation( 2926): Caused by: faj: BadAuthentication
E/HttpOperation( 2926): 	at fal.a(PG:38)
E/HttpOperation( 2926): 	at jdj.a(PG:4089)
E/HttpOperation( 2926): 	... 17 more
,E/ExperimentLoader( 2926): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2926): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2926): 	at jdm.a(PG:82)
E/ExperimentLoader( 2926): 	at jcs.o(PG:406)
E/ExperimentLoader( 2926): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2926): 	at jcs.i(PG:143)
E/ExperimentLoader( 2926): 	at hec.a(PG:42)
E/ExperimentLoader( 2926): 	at hee.a(PG:102)
E/ExperimentLoader( 2926): 	at czr.a(PG:65)
E/ExperimentLoader( 2926): 	at kka.a(PG:108)
E/ExperimentLoader( 2926): 	at czp.a(PG:19176)
E/ExperimentLoader( 2926): 	at czp.a(PG:9081)
E/ExperimentLoader( 2926): 	at czq.run(PG:1686)
E/ExperimentLoader( 2926): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2926): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2926): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2926): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2926): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2926): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2926): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2926): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2926): 	at jdm.a(PG:77)
E/ExperimentLoader( 2926): 	... 15 more
E/ExperimentLoader( 2926): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2926): 	at fal.a(PG:38)
E/ExperimentLoader( 2926): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2926): 	... 17 more
,I/MediaRouter( 3418): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3418): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 3418): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  826): Start proc 3499:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,I/ConfigFetchTask( 1729): updating config table for com.google.android.gms
,I/NetworkMonitor( 3418): type=WIFI subType= reason=null isConnected=true
,W/ResourcesManager( 3499): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3499): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  826): Explicit concurrent mark sweep GC freed 47155(2MB) AllocSpace objects, 11(217KB) LOS objects, 32% free, 33MB/49MB, paused 1.197ms total 56.723ms
,V/JNIHelp ( 3499): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  826): Start proc 3524:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 36184, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigFetchService( 1729): fetch service done; releasing wakelock
,I/ConfigFetchService( 1729): stopping self
,I/ProviderInstaller( 3499): Installed default security provider GmsCore_OpenSSL
,D/DownloadManager( 1083): [73] Starting
,D/SprintDMReceiver( 3524): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityThread( 1083): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/SprintDMHelper( 3524): simOperator:  IMSI: null
D/SprintDMReceiver( 3524): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1729): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1729): onCreate
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 20812(1150KB) AllocSpace objects, 2(55KB) LOS objects, 37% free, 26MB/42MB, paused 1.881ms total 36.127ms
,D/SystemUpdateService( 1729): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/GHttpClientFactory( 3418): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3418): Using platform SSLCertificateSocketFactory
,I/SystemUpdateService( 1729): active receiver: enabled
,I/iu.SyncManager( 1729): SYNC; picasa accounts
,D/NetworkLogImpl( 1729): Loaded NetworkSpeedPredictor
,V/GoogleAuthProtoRequest( 3236): [326] a.<init>: mAccountName set to: thalitester@gmail.com
I/iu.Environment( 1729): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/iu.UploadsManager( 1729): num queued entries: 0
I/iu.UploadsManager( 1729): num updated entries: 0
I/iu.SyncManager( 1729): NEXT; no task
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1729): showing system update notification
I/CheckinService( 1729): Checking schedule, now: 1450100392799 next: 1449877159091
,I/CheckinService( 1729): active receiver: enabled
,D/ChimeraCfgMgr( 1729): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1729): Loading module com.google.android.gms.kids from APK com.google.android.gms
E/YouTube MDX( 3499): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/GcmGroups( 1729): Failed to subscribe to group.
I/GcmGroups( 1729): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 1729): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 1729): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 1729): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 1729): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 1729): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 1729): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 1729): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 1729): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 1729): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/GcmGroups( 1729): Groups upload failed, retrying in 24000:00:00
,I/ValidateNoPeople(  826): skipping global notification
,I/CheckinService( 1729): Preparing to send checkin request
I/EventLogService( 1729): Accumulating logs since 1450099096834
,V/KeepSync( 3263): Connecting to GoogleApiClient
V/SystemUpdateService( 1729): retry (wakeup: false) in 3599886 ms
,I/ActivityManager(  826): Start proc 3580:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1729): onDestroy
,I/EventLogService( 1729): Opted in for usage reporting
,W/GAV2    ( 3480): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/BooksApp( 3480): Created application version: 3.6.8 (30608)
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dex2oat ( 3569): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads467753990.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads467753990.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/BaseAppContext( 1729): Using Auth Proxy for data requests.
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
,I/Babel   ( 2576): connection state changed from DISCONNECTED to CONNECTED
,W/BaseAppContext( 1729): Using Auth Proxy for data requests.
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1408): Connected
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dex2oat ( 3569): dex2oat took 92.328ms (threads: 4) arena alloc=146KB java alloc=12KB native alloc=1222KB free=6MB
,D/GCM     ( 1408): Message class com.google.f.a.a.p
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
,V/KeepSync( 3263): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3263): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3263): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3263): (284) automatic index on blob_node(is_deleted)
,W/InstanceID/Rpc( 3499): Found 10011
,W/EventLogAggregator( 1729): Unknown tag: snet_gcore
W/EventLogAggregator( 1729): Unknown tag: snet_launch_service
,I/BooksSync( 3480): Starting books sync for 61035162, extras: ade
,W/ExperimentUpdateService( 3236): [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3236): [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3236): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3236): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3236): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3236): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3236): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3236): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3236): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3236): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3236): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3236): 	at com.a.a.k.run(SourceFile:110)
,I/GAv4    ( 3580): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3580):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3580):   adb logcat -s GAv4
,D/DownloadManager( 1083): [73] Finished with status SUCCESS
,W/GAv4    ( 3580): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3580): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3580): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1729): Explicit concurrent mark sweep GC freed 26736(1854KB) AllocSpace objects, 17(295KB) LOS objects, 35% free, 29MB/45MB, paused 2.149ms total 149.406ms
,I/art     (  826): Explicit concurrent mark sweep GC freed 20766(902KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.568ms total 48.606ms
,I/CheckinRequestBuilder( 1729): Checkin reason type: 12 attempt count: 1
,D/WifiService(  826): New client listening to asynchronous messages
,E/ActivityThread( 1729): Failed to find provider info for com.google.android.wearable.settings
,I/BooksConfig( 3480): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 3580): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3580): Time to load native libraries: 2 ms (timestamps 7249-7251)
I/LibraryLoader( 3580): Expected native library version number "",actual native library version number ""
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/WebViewChromiumFactoryProvider( 3580): Binding Chromium to main looper Looper (main, tid 1) {605a7fe}
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LibraryLoader( 3580): Expected native library version number "",actual native library version number ""
,I/chromium( 3580): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3580): Initializing chromium process, singleProcess=true
E/KeepSync( 3263): IOException
E/KeepSync( 3263): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3263): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3263): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3263): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3263): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3263): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3263): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3263): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3263): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3263): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3263): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3263): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3263): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3263): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3263): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3263): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3263): 	... 10 more
W/KeepSync( 3263): Sync result 2
W/art     ( 3580): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3580): ApplicationContext is null in ApplicationStatus
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 36187, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/chromium( 3580): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3580): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3580): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3580): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 27361(1472KB) AllocSpace objects, 5(362KB) LOS objects, 37% free, 27MB/43MB, paused 1.018ms total 32.768ms
,E/BooksAccountManager( 3480): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3480): Soft error
E/BooksSync( 3480): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3480): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3480): Sync error
E/BooksSync( 3480): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3480): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3480): Finished books sync
,W/AudioManagerAndroid( 3580): Requires BLUETOOTH permission
,I/NSApplication( 3580): Starting up...
I/GoogleURLConnFactory( 1729): Using platform SSLCertificateSocketFactory
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 36187, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  826): Killing 2870:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/ActivityManager(  826): Start proc 3713:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  826): Killing 1384:android.process.acore/u0a5 (adj 15): empty #17
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  826): Killing 3038:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/PeopleSync( 1729): onPerformSync() [5005f081]
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleDatabaseHelper( 1729): cleanUpNonGplusAccounts done.
,W/GLSActivity( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1408): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1408): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1408): 	at android.os.Binder.execTransact(Binder.java:446)
,W/SubscribedFeeds( 1729): Hard error
,W/CheckinRequestBuilder( 1729): awaiting user notification for token
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 41871, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  826): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 209257, reason: Periodic
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  826): Start proc 3741:com.google.android.calendar/u0a37 for service com.google.android.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService
,I/ActivityManager(  826): Start proc 3758:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,D/Finsky  ( 2662): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2662): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2662): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SQLiteLog( 3741): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
I/ActivityManager(  826): Killing 3059:com.android.musicfx/u0a18 (adj 15): empty #17
I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ResourcesManager( 3758): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3758): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3758): VM with version 2.1.0 has multidex support
I/MultiDex( 3758): install
I/MultiDex( 3758): VM has multidex support, MultiDex support library is disabled.
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 3758): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/Ads     ( 1729): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/ActivityManager(  826): Start proc 3780:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,I/ProviderInstaller( 3758): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 3780): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  826): Explicit concurrent mark sweep GC freed 26293(1089KB) AllocSpace objects, 4(158KB) LOS objects, 32% free, 33MB/49MB, paused 997us total 46.371ms
,I/CalendarProvider2( 3780): Created com.android.providers.calendar.CalendarAlarmManager@199250ec(com.android.providers.calendar.CalendarProvider2@3a7c8cb5)
,I/VacuumService( 1408): Vacuum at: now=1450100394520 tag=VacuumService
,V/GoogleAuthProtoRequest( 3236): [327] a.<init>: mAccountName set to: thalitester@gmail.com
,I/ActivityManager(  826): Start proc 3806:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/AnalyticsLogBase( 3741): PlayLogger.onLoggerConnected
I/AnalyticsLogBase( 3741): PlayLogger.onLoggerConnected
,I/ActivityManager(  826): Killing 1756:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WVCdm   (  358): Instantiating CDM.
,I/WVCdm   (  358): CdmEngine::OpenSession
I/WVCdm   (  358): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  358): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  358): Service_Initialize: starts!
D/QSEECOMAPI: (  358): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  358): App is not loaded in QSEE
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 3758): Using platform SSLCertificateSocketFactory
,W/ExperimentUpdateService( 3236): [327] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3236): [327] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3236): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3236): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3236): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3236): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3236): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3236): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3236): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3236): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3236): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3236): 	at com.a.a.k.run(SourceFile:110)
,I/PeopleSync( 1729): Setting subscription: result=true [5005f081]
,I/PeopleSync( 1729): Starting sync, feed=null [5005f081]
,I/GoogleURLConnFactory( 1408): Using platform SSLCertificateSocketFactory
,W/BaseAppContext( 1729): Using Auth Proxy for data requests.
,W/Uploader( 1408): No account for auth token provided
,W/BaseAppContext( 1729): Using Auth Proxy for data requests.
,D/QSEECOMAPI: (  358): Loaded image: APP id = 3
,W/ResourcesManager( 3741): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3741): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/DrmWidevineDash(  358): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3c81000
E/DrmWidevineDash(  358): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3c81000
,D/DrmLibTime(  313): got the req here! ret=0
D/DrmLibTime(  313): command id, time_cmd_id = 770
D/DrmLibTime(  313): time_getutcsec starts!
D/DrmLibTime(  313): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  313): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  313): QSEE Time Listener: seconds: 1450100394
D/DrmLibTime(  313): QSEE Time Listener: nano seconds: 945893123
D/DrmLibTime(  313): time_getutcsec returns 0, sec = 1450100394; nsec = 945893123
D/DrmLibTime(  313): time_getutcsec finished! 
D/DrmLibTime(  313): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  313): before calling ioctl to read the next time_cmd
,W/BaseAppContext( 1729): Using Auth Proxy for data requests.
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: ends! returns 0,
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: starts!
,I/PeopleSync( 1729): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  358): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: starts! SID=0xbe989520
,D/DrmWidevineDash(  358): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_GetRandom: starts! randomData=0xb4c4e230, dataLength=8
,D/DrmWidevineDash(  358): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb404f800, wrapped_rsa_key_length=1280
,V/JNIHelp ( 3741): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  358): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  358): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  358): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  358): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: starts! deviceID=0xb583ec40, idLength=0xb3fff710
,D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  358): PrepareKeyRequest: nonce=864483263
D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4d77600
D/DrmWidevineDash(  358): message_length=1599, signature=0xb4c53400, signature_length=3019896564
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleSync( 1729): Sync finished, successful=false, took 62ms
,I/ProviderInstaller( 3741): Installed default security provider GmsCore_OpenSSL
,W/AbstractGoogleClient( 3741): Application name is not set. Call Builder#setApplicationName.
I/PeopleSync( 1729): Cannot authenticate [5005f081]
I/PeopleSync( 1729): com.google.android.gms.auth.ad: BadAuthentication
I/PeopleSync( 1729): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/PeopleSync( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/PeopleSync( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:310)
I/PeopleSync( 1729): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
I/PeopleSync( 1729): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
I/PeopleSync( 1729): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
I/PeopleSync( 1729): 	at com.google.android.gms.people.service.g.b(SourceFile:171)
I/PeopleSync( 1729): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
I/PeopleSync( 1729): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
I/PeopleSync( 1729): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
I/PeopleSync( 1729): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
I/PeopleSync( 1729): 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
I/PeopleSync( 1729): 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
I/PeopleSync( 1729): 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
I/PeopleSync( 1729): 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
I/PeopleSync( 1729): 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
I/PeopleSync( 1729): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
I/PeopleSync( 1729): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  358): CdmEngine::CloseSession
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  358): L3 Terminate.
D/DrmWidevineDash(  358): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  358): Service_Uninitialize: starts!
D/QSEECOMAPI: (  358): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  358): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  358): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_Terminate: ends! returns 0
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 28639(1633KB) AllocSpace objects, 9(992KB) LOS objects, 37% free, 26MB/42MB, paused 993us total 39.879ms
,I/PeopleSync( 1729): ***Sync finished***, duration: 1082 [5005f081]
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 41879, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  826): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 211504, reason: Periodic
,E/Uploader( 1408): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1408): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1702): Uploading GCM registration ID for account#2#
,E/CalendarSyncAdapter( 3741): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 3741): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 3741): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 3741): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 3741): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 3741): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 3741): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 3741): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 3741): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:2382)
E/CalendarSyncAdapter( 3741): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1850)
E/CalendarSyncAdapter( 3741): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:1733)
E/CalendarSyncAdapter( 3741): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:503)
E/CalendarSyncAdapter( 3741): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:392)
E/CalendarSyncAdapter( 3741): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 3741): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 3741): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 3741): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 3741): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 3741): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 3741): 	... 12 more
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 41880, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  826): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 211454, reason: Periodic
I/ActivityManager(  826): Killing 3087:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/dex2oat ( 3835): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=33 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3835): dex2oat took 23.658ms (threads: 4) arena alloc=68KB java alloc=18KB native alloc=1119KB free=6MB
,I/Adreno  ( 3758): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1702): Using Auth Proxy for data requests.
,I/ActivityManager(  826): Start proc 3843:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/GLSUser ( 1702): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 209us total 16.492ms
,E/Uploader( 1408): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1408): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 193us total 10.607ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 8.924ms
,I/GLSUser ( 1702): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/ActivityManager(  826): Killing 2997:com.android.defcontainer/u0a7 (adj 15): empty #17
,D/TimeService( 3843): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450100395525
D/        ( 3843): TimeServiceNative: User Time to be set is 1450100395525
D/QC-time-services( 3843): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3843): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3843): Lib:time_genoff_operation: pargs->ts_val = 1450100395525
D/QC-time-services( 3843): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  373): Daemon: Connection accepted:time_genoff
D/QC-time-services(  373): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450100395525
D/QC-time-services(  373): Daemon:genoff_opr: Base = 2, val = 1450100395525, operation = 0
D/QC-time-services(  373): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/1/70 9:52:46
D/QC-time-services(  373): Daemon:Value read from RTC seconds = 10403566000
D/QC-time-services(  373): Daemon:new time 1450100395525 
D/QC-time-services(  373): Daemon: delta 1439696829525 genoff 1439696829525 
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696829525 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  373): Updating the TOD offset
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696829525 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  373): Daemon:Update to modem bit set
D/QC-time-services(  373): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 3843): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  373): Daemon: Base = 2, Value being sent to MODEM = 1134135595525
,I/Adreno  ( 3758): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,I/ActivityManager(  826): Killing 3306:com.android.settings/1000 (adj 15): empty #17
,E/QC-time-services(  373): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  373): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/Uploader( 1408): No account for auth token provided
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/GCoreUlr( 1702): 
E/GCoreUlr( 1702): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1702): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1702): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1702): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1702): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1702): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1702): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1702): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1702): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1702): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1702): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1702): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1702): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1702): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1702): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1702): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 41882, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  826): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 210190, reason: Periodic
,W/Uploader( 1408): No account for auth token provided
,I/ActivityManager(  826): Start proc 3867:com.google.android.gm/u0a78 for service com.google.android.gm/.provider.MailSyncAdapterService
,I/CalendarProvider2( 3780): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3780): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  826): Start proc 3885:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/ActivityManager(  826): Killing 3324:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/WVCdm   (  358): CdmEngine::OpenSession
I/WVCdm   (  358): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  358): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  358): Service_Initialize: starts!
D/QSEECOMAPI: (  358): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  358): App is not loaded in QSEE
,I/art     (  826): Explicit concurrent mark sweep GC freed 23066(1036KB) AllocSpace objects, 6(473KB) LOS objects, 32% free, 33MB/49MB, paused 1.220ms total 52.366ms,
,I/Gmail   ( 3867): getAccountsCursor
,D/ActivityThread( 3867): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  826): Start proc 3911:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,W/GAV2    ( 3867): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/Uploader( 1408): No account for auth token provided
,I/GAv4    ( 3885): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3885):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3885):   adb logcat -s GAv4
,I/ActivityManager(  826): Start proc 3936:com.google.android.apps.docs.editors.docs/u0a47 for service com.google.android.apps.docs.editors.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,W/GAv4    ( 3885): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/QSEECOMAPI: (  358): Loaded image: APP id = 3
I/Gmail   ( 3867): getAccountsCursor
,I/Exchange( 3911): EasService.onCreate
,D/DrmWidevineDash(  358): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3c81000
E/DrmWidevineDash(  358): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3c81000
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Gmail   ( 3867): Sync started for account: account:61035162
,D/DrmLibTime(  313): got the req here! ret=0
D/DrmLibTime(  313): command id, time_cmd_id = 770
D/DrmLibTime(  313): time_getutcsec starts!
D/DrmLibTime(  313): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  313): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  313): QSEE Time Listener: seconds: 1450100396
D/DrmLibTime(  313): QSEE Time Listener: nano seconds: 92991040
D/DrmLibTime(  313): time_getutcsec returns 0, sec = 1450100396; nsec = 92991040
D/DrmLibTime(  313): time_getutcsec finished! 
D/DrmLibTime(  313): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  313): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: starts!
,I/Exchange( 3911): RestartPingTask
,W/GAv4    ( 3885): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3885): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  358): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: starts! SID=0xbe989520
V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  358): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_GetRandom: starts! randomData=0xb58762d8, dataLength=8
,D/DrmWidevineDash(  358): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb404f200, wrapped_rsa_key_length=1280
E/SQLiteLog( 3867): (283) recovered 13 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  358): CdmEngine::QueryKeyControlInfo
,W/ActivityManager(  826): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/WVCdm   (  358): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  358): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  358): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: starts! deviceID=0xb583ec80, idLength=0xb3f01710
,D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  358): PrepareKeyRequest: nonce=2966326919
D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4027600
D/DrmWidevineDash(  358): message_length=1634, signature=0xb5880100, signature_length=3018856180
,I/Exchange( 3911): RestartPingsTask did not start any pings.
,I/Exchange( 3911): PSS stopIfIdle
I/Exchange( 3911): PSS has no active accounts; stopping service.
I/Exchange( 3911): onDestroy
,I/Gmail   ( 3867): Observing account changes for notifications
,I/ActivityManager(  826): Killing 1506:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,I/Gmail   ( 3867): notifyAccountChanged
,I/Gmail   ( 3867): getAccountsCursor
,I/Gmail   ( 3867): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 3867): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3867): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3867): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/WifiService(  826): Client connection lost with reason: 4
,D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  358): CdmEngine::CloseSession
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: starts! SID=1
,I/Exchange( 3911): EasService.onCreate
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  358): L3 Terminate.
D/DrmWidevineDash(  358): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  358): Service_Uninitialize: starts!
D/QSEECOMAPI: (  358): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  358): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  358): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_Terminate: ends! returns 0
,I/Exchange( 3911): RestartPingTask
,I/Exchange( 3911): RestartPingsTask did not start any pings.
I/Exchange( 3911): PSS stopIfIdle
I/Exchange( 3911): PSS has no active accounts; stopping service.
,I/Exchange( 3911): onDestroy
,I/ActivityManager(  826): Killing 3418:com.google.android.music:main/u0a66 (adj 15): empty #17
,W/Uploader( 1408): No account for auth token provided
,I/ConfigFetchService( 1729): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,D/GCM     ( 1408): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,I/Gmail   ( 3867): notifyAccountChanged
,I/DictionaryProvider:UpdateHandler( 1209): downloadFinished() : DownloadId = 73
,I/art     ( 1729): Explicit concurrent mark sweep GC freed 16679(1037KB) AllocSpace objects, 8(128KB) LOS objects, 35% free, 29MB/45MB, paused 1.417ms total 66.988ms
,I/ConfigFetchService( 1729): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1729): GmsCore config value changed; rescheduling
I/ConfigFetchService( 1729): service connected
,I/EventLogService( 1729): Opted in for usage reporting
,W/ConfigFetchService( 1729): ConfigApi client is not connected. Falling back to defaultfetch interval.
,D/ConfigFetchService( 1729): ConfigApi connection successful.
,V/Herrevad( 1729): NQAS connected
,I/ConfigFetchService( 1729): stopping self
,W/Uploader( 1408): No account for auth token provided
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 46832(2MB) AllocSpace objects, 13(1233KB) LOS objects, 36% free, 27MB/43MB, paused 979us total 32.584ms
,W/Uploader( 1408): No account for auth token provided
,D/AuthorizationBluetoothService( 1408): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1408): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1729): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/Babel   ( 2576): UserRecoverableAuthException.
E/Babel   ( 2576): eei: BadAuthentication
E/Babel   ( 2576): 	at eeg.a(Unknown Source)
E/Babel   ( 2576): 	at eeg.a(Unknown Source)
E/Babel   ( 2576): 	at eeg.a(Unknown Source)
E/Babel   ( 2576): 	at g.a(Unknown Source)
E/Babel   ( 2576): 	at cae.a(SourceFile:3089)
E/Babel   ( 2576): 	at cae.a(SourceFile:1131)
E/Babel   ( 2576): 	at cws.a(SourceFile:4333)
E/Babel   ( 2576): 	at cws.a(SourceFile:1419)
E/Babel   ( 2576): 	at crl.a(SourceFile:492)
E/Babel   ( 2576): 	at crl.a(SourceFile:1468)
E/Babel   ( 2576): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2576): 	at cas.b(SourceFile:106)
E/Babel   ( 2576): 	at cap.d(SourceFile:335)
E/Babel   ( 2576): 	at caq.run(SourceFile:81)
E/Babel   ( 2576): Error getting auth token
E/Babel   ( 2576): dvm
E/Babel   ( 2576): 	at g.a(Unknown Source)
E/Babel   ( 2576): 	at cae.a(SourceFile:3089)
E/Babel   ( 2576): 	at cae.a(SourceFile:1131)
E/Babel   ( 2576): 	at cws.a(SourceFile:4333)
E/Babel   ( 2576): 	at cws.a(SourceFile:1419)
E/Babel   ( 2576): 	at crl.a(SourceFile:492)
E/Babel   ( 2576): 	at crl.a(SourceFile:1468)
E/Babel   ( 2576): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2576): 	at cas.b(SourceFile:106)
E/Babel   ( 2576): 	at cap.d(SourceFile:335)
E/Babel   ( 2576): 	at caq.run(SourceFile:81)
,I/ActivityManager(  826): Start proc 3987:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,E/Babel   ( 2576): Account registration failed 1-Redacted-21
,E/Babel   ( 2576): cyp: null -- null
E/Babel   ( 2576): 	at cae.a(SourceFile:3121)
E/Babel   ( 2576): 	at cae.a(SourceFile:1131)
E/Babel   ( 2576): 	at cws.a(SourceFile:4333)
E/Babel   ( 2576): 	at cws.a(SourceFile:1419)
E/Babel   ( 2576): 	at crl.a(SourceFile:492)
E/Babel   ( 2576): 	at crl.a(SourceFile:1468)
E/Babel   ( 2576): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2576): 	at cas.b(SourceFile:106)
E/Babel   ( 2576): 	at cap.d(SourceFile:335)
E/Babel   ( 2576): 	at caq.run(SourceFile:81)
,I/art     ( 2576): Note: end time exceeds epoch: 
,D/LocationInitializer( 1729): Restart initialization of location
,W/ResourcesManager( 3987): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3987): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/Uploader( 1408): No account for auth token provided
,I/MultiDex( 3987): VM with version 2.1.0 has multidex support
I/MultiDex( 3987): install
I/MultiDex( 3987): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3987): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3987): Installed default security provider GmsCore_OpenSSL
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 3987): callingUid 10011, callindPid: 3987
,W/ResourcesManager( 1408): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  826): Explicit concurrent mark sweep GC freed 17269(777KB) AllocSpace objects, 3(330KB) LOS objects, 32% free, 33MB/49MB, paused 4.873ms total 82.222ms
,E/MDM     ( 1702): [124] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/Babel   ( 2576): Unexpected exception while authenticating.
E/Babel   ( 2576): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2576): 	at eeg.b(Unknown Source)
E/Babel   ( 2576): 	at eeg.b(Unknown Source)
E/Babel   ( 2576): 	at g.a(Unknown Source)
E/Babel   ( 2576): 	at cae.b(SourceFile:1146)
E/Babel   ( 2576): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2576): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2576): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2576): 	at java.lang.Thread.run(Thread.java:818)
,I/Gmail   ( 3867): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 4353, normalSync: true
,I/GAv4    ( 3936): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3936):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3936):   adb logcat -s GAv4
,W/GAv4    ( 3936): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3936): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3936): Analytics setup for ID UA-21125203-4, app name Docs, version 1.4.292.15.30
,W/GAv4    ( 3936): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/GCM     ( 1408): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/Uploader( 1408): No account for auth token provided
,D/AuthorizationBluetoothService( 1408): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/SQLiteLog( 3780): (284) automatic index on view_events(_id)
V/GmsCoreStatsServiceLauncher( 1729): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1702): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Gmail   ( 3867): getAccountsCursor
,D/LocationInitializer( 1729): Restart initialization of location
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3936): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3936): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/Uploader( 1408): No account for auth token provided
,V/JNIHelp ( 3936): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ResourcesManager( 3867): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3867): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ProviderInstaller( 3936): Installed default security provider GmsCore_OpenSSL
,I/DictionaryProvider:UpdateHandler( 1209): downloadFinished() : Success = true
,I/DictionaryProvider:UpdateHandler( 1209): downloadFinished() : Metadata Success
I/Keyboard.Facilitator( 1209): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1209): run()
V/JNIHelp ( 3867): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/Decoder ( 1209): createOrResetDecoder
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProviderInstaller( 3867): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1209): run()
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Uploader( 1408): No account for auth token provided
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1209): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Loading LM = contacts
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
,W/GLSActivity( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1408): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1408): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1408): 	at android.os.Binder.execTransact(Binder.java:446)
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  826): Start proc 4058:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,W/GLSActivity( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1408): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1408): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1408): 	at android.os.Binder.execTransact(Binder.java:446)
,I/Gmail   ( 3867): notifyAccountChanged
,I/Gmail   ( 3867): getAccountsCursor
,I/DictionaryProvider:UpdateHandler( 1209): downloadFinished() : Success = true
I/DictionaryProvider:UpdateHandler( 1209): downloadFinished() : Metadata Success
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1408): No account for auth token provided
,I/Keyboard.Facilitator( 1209): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1209): run()
,I/Decoder ( 1209): createOrResetDecoder
,I/[@@    ] SyncAdapterProxy( 1408): Delagator disabled, using the (deprecated) GData sync adapter
,I/ContactLocale( 4058): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1209): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1209): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Gmail   ( 3867): notifyAccountChanged
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Loading LM = history
W/Gmail   ( 3867): Sync complete for account: account:61035162
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Loading LM = user
I/Gmail   ( 3867): getAccountsCursor
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1209): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1209): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1209): run()
I/StatsUtilsManager( 1209): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1209): shouldRecordStats() = Too Soon
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 41890, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  826): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 211748, reason: Periodic
,W/Uploader( 1408): No account for auth token provided
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 73488(3MB) AllocSpace objects, 15(1187KB) LOS objects, 36% free, 27MB/43MB, paused 1.229ms total 38.170ms
,W/GLSActivity( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1408): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1408): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1408): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 1408): innerSync failed
D/ContactsSyncAdapter( 1408): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1408): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1408): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1408): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1408): 	at com.google.android.syncadapters.contacts.delegation.SyncAdapterProxy.onPerformLoggedSync(SyncAdapterProxy.java:123)
D/ContactsSyncAdapter( 1408): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1408): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1408): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1408): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
D/ContactsSyncAdapter( 1408): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1408): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
D/ContactsSyncAdapter( 1408): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1408): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ActivityManager(  826): Killing 3524:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/CheckinTask( 1729): Sending checkin request (10553 bytes)
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 41903, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  826): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 212811, reason: Periodic
,I/GAV2    ( 3480): Thread[GAThread,5,main]: No campaign data found.
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Uploader( 1408): No account for auth token provided
,I/ActivityManager(  826): Start proc 4086:com.google.android.apps.docs/u0a46 for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ReminderSync( 1729): AuthError [T SyncAdapterThread-1:id=232:priority=5:group=main]
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 41904, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  826): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 212869, reason: Periodic
,I/SyncAdapterService( 3580): Ignoring sync request for non-current account
,I/CheckinResponseProcessor( 1729): From server: 3 gservices updates and 0 deletes
,W/Uploader( 1408): No account for auth token provided
,I/art     (  826): Explicit concurrent mark sweep GC freed 30571(1379KB) AllocSpace objects, 5(80KB) LOS objects, 31% free, 34MB/50MB, paused 1.656ms total 48.721ms
,I/CertBlacklister(  826): Certificate blacklist changed, updating...
,I/GservicesProvider( 1408): main difference update completed
,I/CertBlacklister(  826): Certificate blacklist updated
,I/GAv4    ( 4086): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4086):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4086):   adb logcat -s GAv4
,W/Uploader( 1408): No account for auth token provided
,I/ActivityManager(  826): Start proc 4116:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,W/GAv4    ( 4086): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/CheckinRequestBuilder( 1729): Checkin reason type: 12 attempt count: 1
,W/GAv4    ( 4086): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/ActivityThread( 1729): Failed to find provider info for com.google.android.wearable.settings
,D/DelayedSyncController( 3713): Delaying sync.
,W/GAv4    ( 4086): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4086): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,W/Telecom (  826): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 2576): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 2576): BAM#gBA: invalid account id: -1
,W/Babel   ( 2576): BAM#gBA: invalid account id: -1
I/Babel_telephony( 2576): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,W/BaseAppContext( 1729): Using Auth Proxy for data requests.
,W/BaseAppContext( 1729): Using Auth Proxy for data requests.
,W/BaseAppContext( 1729): Using Auth Proxy for data requests.
,W/Uploader( 1408): No account for auth token provided
,W/ResourcesManager( 4086): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4086): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 4086): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4086): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  826): Start proc 4152:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,V/JNIHelp ( 4086): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/BaseAppContext( 1729): Using Auth Proxy for data requests.
,I/ProviderInstaller( 4086): Installed default security provider GmsCore_OpenSSL
,E/UpdateRequestReceiver( 4152): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4152): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 37030(2032KB) AllocSpace objects, 11(934KB) LOS objects, 37% free, 27MB/43MB, paused 898us total 27.753ms
,W/BaseAppContext( 1729): Using Auth Proxy for data requests.
,E/UpdateRequestReceiver( 4152): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/BaseAppContext( 1729): Using Auth Proxy for data requests.
,E/UpdateRequestReceiver( 4152): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  826): Killing 2662:com.android.vending/u0a19 (adj 15): empty #17
,D/WifiService(  826): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@22307f43}
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1408): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1408): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/BaseAppContext( 1729): Using Auth Proxy for data requests.
,I/ActivityManager(  826): Killing 3480:com.google.android.apps.books/u0a34 (adj 15): empty #17
,I/art     ( 1702): Explicit concurrent mark sweep GC freed 14055(823KB) AllocSpace objects, 6(96KB) LOS objects, 37% free, 26MB/42MB, paused 1.256ms total 49.370ms
,E/DataBuffer( 1702): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2332aa39)
,I/art     ( 1729): Explicit concurrent mark sweep GC freed 28350(3MB) AllocSpace objects, 10(159KB) LOS objects, 35% free, 29MB/45MB, paused 1.103ms total 39.412ms
,W/Uploader( 1408): No account for auth token provided
,I/ActivityManager(  826): Start proc 4191:com.google.android.music:main/u0a66 for service com.google.android.music/.sync.SyncAdapterService
,I/SystemUpdateService( 1729): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1729): onCreate
,D/SystemUpdateService( 1729): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/Uploader( 1408): No account for auth token provided
,D/GCM     ( 1408): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/SystemEventReceiver( 1729): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1729): Updating ocr activity enabled=false
,I/GCoreUlr( 1702): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1702): DispatchingService.onCreate()
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 10519(567KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 27MB/43MB, paused 1.524ms total 41.676ms
,W/Uploader( 1408): No account for auth token provided
,I/MusicStore( 4191): Database version: 120
,I/SystemUpdateService( 1729): active receiver: enabled
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/SystemUpdateService( 1729): showing system update notification
,I/ValidateNoPeople(  826): skipping global notification
,V/SystemUpdateService( 1729): retry (wakeup: false) in 3599932 ms
,I/art     (  826): Explicit concurrent mark sweep GC freed 17143(748KB) AllocSpace objects, 6(473KB) LOS objects, 32% free, 33MB/49MB, paused 972us total 48.842ms
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1702): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1408): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1408): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/ResourcesManager( 4191): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4191): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/CheckinRequestBuilder( 1729): awaiting user notification for token
,V/JNIHelp ( 4191): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1408): No account for auth token provided
,I/ProviderInstaller( 4191): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4191): GMSCore installation verified
,I/ConfigStore( 4191): Config Database version: 1
,W/GLSActivity( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1408): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1408): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1408): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DefaultHttpIssuer( 4086): Attempt to consume entity of HttpIssuer when no request is executing.
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 14453(870KB) AllocSpace objects, 3(330KB) LOS objects, 36% free, 27MB/43MB, paused 955us total 33.712ms
E/DefaultHttpIssuer( 4086): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 4086): java.io.IOException
E/DefaultHttpIssuer( 4086): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 4086): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 4086): 	at dlh.b(PG:239)
E/DefaultHttpIssuer( 4086): 	at dlh.a(PG:140)
E/DefaultHttpIssuer( 4086): 	at dqo.a(PG:224)
E/DefaultHttpIssuer( 4086): 	at dlt.run(PG:9618)
E/DefaultHttpIssuer( 4086): 	at dlr.run(PG:3031)
,E/BaseSyncManager( 4086): AuthenticatorException
E/BaseSyncManager( 4086): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BaseSyncManager( 4086): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/BaseSyncManager( 4086): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BaseSyncManager( 4086): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/BaseSyncManager( 4086): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BaseSyncManager( 4086): 	at android.os.Binder.execTransact(Binder.java:446)
,D/WifiService(  826): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@22307f43}
,W/Uploader( 1408): No account for auth token provided
,I/ActivityManager(  826): Killing 3499:com.google.android.youtube/u0a86 (adj 15): empty #17
,I/MediaRouter( 4191): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GCoreUlr( 1702): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/Uploader( 1408): No account for auth token provided
,I/GCoreUlr( 1702): Unbound from all location providers
I/GAV2    ( 3741): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  826): Start proc 4232:com.google.android.apps.cloudprint:sync/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,I/GHttpClientFactory( 4191): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 4191): Using platform SSLCertificateSocketFactory
I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 12.928ms
,I/NetworkMonitor( 4191): type=WIFI subType= reason=null isConnected=true
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 10.592ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 1.135ms total 12.533ms
,I/MusicLifecycle( 4191): Sync started
,I/GCoreUlr( 1702): DispatchingService.onDestroy()
,I/GCoreUlr( 1702): Unbound from all location providers
,I/NetworkMonitor( 4191): type=WIFI subType= reason=null isConnected=true
,W/Uploader( 1408):  no longer exists, so no auth token.
,I/GHttpClientFactory( 4191): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 4191): Using platform SSLCertificateSocketFactory
,I/art     ( 1729): Explicit concurrent mark sweep GC freed 9670(525KB) AllocSpace objects, 4(64KB) LOS objects, 35% free, 29MB/45MB, paused 1.036ms total 38.869ms
,D/SystemUpdateService( 1729): onDestroy
,I/EventLogService( 1729): Opted in for usage reporting
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/CheckinTask( 1729): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/ActivityManager(  826): Start proc 4262:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1408): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1408): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
I/CheckinService( 1729): Checking schedule, now: 1450100399709 next: 1450141542671
I/CheckinService( 1729): active receiver: disabled
,I/CheckinService( 1729): Checking schedule, now: 1450100399756 next: 1450141542671
I/CheckinService( 1729): active receiver: disabled
,I/ActivityManager(  826): Killing 2926:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,W/Uploader( 1408): No account for auth token provided
,I/ActivityManager(  826): Start proc 4280:com.google.android.apps.cloudprint/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,W/Uploader( 1408): No account for auth token provided
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 4232): Sync request not initiated by GCP app. Dropping
V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicLifecycle( 4191): Sync ended
W/MusicSyncAdapter( 4191): Sync failed due to an authentication issue.
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SyncManager(  826): handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 182883, mTimeoutStartTime 182883, mHistoryRowId 21, syncOperation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 41917, reason: Periodic
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1408): No account for auth token provided
,I/ActivityManager(  826): Killing 3263:com.google.android.keep/u0a79 (adj 15): empty #17
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 17725(910KB) AllocSpace objects, 9(992KB) LOS objects, 37% free, 26MB/42MB, paused 972us total 29.349ms
,I/ActivityManager(  826): Killing 3843:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/Uploader( 1408): No account for auth token provided
,I/ActivityManager(  826): Start proc 4312:com.google.android.apps.docs.editors.sheets/u0a48 for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
I/art     (  826): Explicit concurrent mark sweep GC freed 22223(1155KB) AllocSpace objects, 9(238KB) LOS objects, 32% free, 33MB/49MB, paused 1.884ms total 93.124ms
,I/MusicLifecycle( 4191): Sync started
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GservicesUpdateTask( 4262): Updating Gservices keys
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1408): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1408): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1408): 	at android.os.Binder.execTransact(Binder.java:446)
,E/Uploader( 1408): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1408): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 1729): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/Uploader( 1408): No account for auth token provided
,D/ChimeraCfgMgr( 1729): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1408): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1408): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1408): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1408): 	at android.os.Binder.execTransact(Binder.java:446)
,I/MusicLifecycle( 4191): Sync ended
W/MusicSyncAdapter( 4191): Sync failed due to an authentication issue.
W/Kids    ( 1729): [AccountUtils] Account not ready
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
I/MusicLeanback( 4191): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 4191): Stop autocaching.
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 41917, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  826): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 216924, reason: Periodic
,W/Uploader( 1408): No account for auth token provided
,I/MusicLeanback( 4191): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 4191): Stop autocaching.
,E/Auth.Api.Credentials( 1729): [CredentialSyncAdapter] Unknown sync event.
,W/Uploader( 1408): No account for auth token provided
,E/GmsUtils( 4191): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 4191): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 4191): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 4191): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  826): Killing 3885:com.google.android.deskclock/u0a44 (adj 15): empty #17
,W/Uploader( 1408): No account for auth token provided
,I/GAV2    ( 3867): Thread[GAThread,5,main]: No campaign data found.
,W/Uploader( 1408): No account for auth token provided
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1408): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1408): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/ActivityManager(  826): Killing 3236:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,W/Uploader( 1408): No account for auth token provided
,W/Uploader( 1408): No account for auth token provided
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1408): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1408): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1408): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1408): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1408): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1408): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GAv4    ( 4312): Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4312):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4312):   adb logcat -s GAv4
,W/GAv4    ( 4312): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4312): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4312): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4312): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.332.11.30
,I/ActivityManager(  826): Killing 3911:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  826): Killing 2576:com.google.android.talk/u0a61 (adj 15): empty #17
,W/ResourcesManager( 4312): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4312): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  826): Killing 3780:com.android.providers.calendar/u0a3 (adj 15): empty #17
,V/JNIHelp ( 4312): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4312): Installed default security provider GmsCore_OpenSSL
,E/lowmemorykiller(  258): Error opening /proc/3780/oom_score_adj; errno=2
,I/ActivityThread( 3741): Removing dead content provider:android.content.ContentProviderProxy@25a305c9
,I/ActivityManager(  826): Start proc 4389:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 4389): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 4389): Created com.android.providers.calendar.CalendarAlarmManager@199250ec(com.android.providers.calendar.CalendarProvider2@3a7c8cb5),
,I/ActivityManager(  826): Killing 3936:com.google.android.apps.docs.editors.docs/u0a47 (adj 15): empty #17
,I/ConfigService( 1408): onDestroy
,I/CalendarProvider2( 4389): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 4389): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,I/art     (  826): Explicit concurrent mark sweep GC freed 21653(1007KB) AllocSpace objects, 7(489KB) LOS objects, 31% free, 34MB/50MB, paused 1.449ms total 82.280ms
,I/MusicLeanback( 4191): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 4191): Stop autocaching.
,E/GmsUtils( 4191): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 4191): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,W/PackageSettings(  826): Skipping PackageSetting{d1f6341 com.example.hello/10272} due to missing metadata
,I/ActivityManager(  826): Killing 3580:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/ActivityManager(  826): Killing 3867:com.google.android.gm/u0a78 (adj 15): empty #18
,I/InputReader(  826): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  826): Start proc 4418:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,D/BackupManagerService(  826): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  826): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  826): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  826): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  826): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2fb3a7e0
,W/ResourcesManager( 4418): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GmsNetworkLocationProvi( 1702): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/BackupManagerService(  826): Scheduling immediate backup pass
,V/BackupManagerService(  826): Running a backup pass
,V/BackupManagerService(  826): clearing pending backups
,V/PerformBackupTask(  826): Beginning backup of 14 targets
,D/PerformBackupTask(  826): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  826): doBackup() invoked
,I/PMBA    (  826): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,V/GmsNetworkLocationProvi( 1702): DISABLE
,I/Launcher( 1294): Deferring update until onResume
,V/GmsNetworkLocationProvi( 1702): ENABLE
,V/GmsNetworkLocationProvi( 1702): SET-REQUEST
,V/GmsNetworkLocationProvi( 1702): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,I/BackupRestoreController(  826): Getting widget state for user: 0
,W/GmsBackupTransport( 1702): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1702): starting performBackup for @pm@
,V/GmsBackupTransport( 1702): performBackup done for @pm@
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1408): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1408): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1408): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/BackupManagerService(  826): Now staging backup of com.google.android.talk
,D/BackupManagerService(  826): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  826): Now staging backup of com.android.providers.settings
,I/Babel_SMS( 4418): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4418): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4418): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 4418): MmsConfig.loadFromDatabase
,D/BackupManagerService(  826): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  826): Now staging backup of com.google.android.gm
,D/BackupManagerService(  826): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  826): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  826): Now staging backup of com.android.nfc
,D/BackupManagerService(  826): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  826): Now staging backup of com.android.vending
D/BackupManagerService(  826): Now staging backup of com.google.android.calendar
D/BackupManagerService(  826): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  826): Now staging backup of android
,D/BackupManagerService(  826): Now staging backup of com.google.android.googlequicksearchbox
,E/Babel_SMS( 4418): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4418): MmsConfig.loadFromResources
,E/Babel_SMS( 4418): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4418): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,I/GmsBackupTransport( 1702): Next backup will happen in 43199960 millis.
,I/BackupManagerService(  826): Backup pass finished.
,W/Settings( 4418): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4418): startup - clean
,I/Babel   ( 4418): deleted: false for 0
,I/Babel_telephony( 4418): TeleModule.launchCompleted
,W/Telecom (  826): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 4418): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,W/Babel   ( 4418): BAM#gBA: invalid account id: -1
W/Babel   ( 4418): BAM#gBA: invalid account id: -1
,I/Babel_telephony( 4418): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,W/Telecom (  826): TelecomServiceImpl: null is not visible for the calling user
,D/PackageBroadcastService( 1729): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1729): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 4262): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1294): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3d33d184 new=com.google.android.velvet.VelvetApplication@3d33d184
,I/Icing   ( 1729): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  826): Start proc 4452:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,W/VideoCapabilities( 4418): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 4418): Unsupported profile 4 for video/mp4v-es
,I/UpdateIcingCorporaServi( 4262): UpdateCorporaTask done [took 84 ms] updated apps [took 84 ms] 
,W/VideoCapabilities( 4418): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4418): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4418): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4418): Unrecognized profile 2130706433 for video/avc
,D/Finsky  ( 4452): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/vclib   ( 4418): onServiceConnected
W/Babel   ( 4418): Attempted to change video mute state without an active call.
,W/ResourcesManager( 4418): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4418): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 4452): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,V/JNIHelp ( 4418): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4418): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  826): Start proc 4493:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 4452): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4452): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4493): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4493): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 4493): VM with version 2.1.0 has multidex support
I/MultiDex( 4493): install
I/MultiDex( 4493): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4493): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4493): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 4452): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4452): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4452): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4452): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  826): Start proc 4520:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,W/ResourcesManager( 4520): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 32134(2042KB) AllocSpace objects, 15(936KB) LOS objects, 36% free, 28MB/44MB, paused 908us total 26.703ms
,I/ActivityManager(  826): Killing 3713:com.android.chrome/u0a40 (adj 15): empty #17
,V/Finsky  ( 4452): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/GCM     ( 1408): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1408): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1729): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3987): callingUid 10011, callindPid: 3987
,D/LocationInitializer( 1729): Restart initialization of location
,E/MDM     ( 1702): [128] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/Finsky  ( 4452): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 4452): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  826): Explicit concurrent mark sweep GC freed 27402(1700KB) AllocSpace objects, 9(803KB) LOS objects, 32% free, 33MB/49MB, paused 2.440ms total 99.158ms
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4452): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4452): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4452): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4452): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 4452): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/Finsky  ( 4452): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,D/DeviceConnectionService( 1702): client connected with version: 7571000
,D/Finsky  ( 4452): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,I/ActivityManager(  826): Killing 4152:com.google.android.configupdater/u0a42 (adj 15): empty #17
,I/ActivityManager(  826): Killing 4086:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/ActivityManager(  826): Killing 4280:com.google.android.apps.cloudprint/u0a41 (adj 15): empty #17
,I/ActivityManager(  826): Start proc 4565:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,I/ActivityManager(  826): Start proc 4582:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,W/ResourcesManager( 4582): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4582): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4582): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/GoogleAuthProtoRequest( 4565): [495] a.<init>: mAccountName set to: thalitester@gmail.com
,I/ProviderInstaller( 4582): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4452): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4452): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4452): [1] 5.onFinished: Giving up after 6 failures.
,W/ExperimentUpdateService( 4565): [495] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4565): [495] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4565): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4565): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4565): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4565): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  826): Killing 4232:com.google.android.apps.cloudprint:sync/u0a41 (adj 15): empty #17
,I/dex2oat ( 4619): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads467753990.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads467753990.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4619): dex2oat took 25.704ms (threads: 4) arena alloc=201KB java alloc=12KB native alloc=1218KB free=6MB
,E/YouTube MDX( 4582): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/InstanceID/Rpc( 4582): Found 10011
,V/GoogleAuthProtoRequest( 4565): [496] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 29915(1631KB) AllocSpace objects, 18(1984KB) LOS objects, 37% free, 26MB/42MB, paused 1.118ms total 39.346ms
,W/ExperimentUpdateService( 4565): [496] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4565): [496] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4565): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4565): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4565): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4565): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  826): Killing 4116:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  826): Start proc 4681:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 361us total 20.269ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 348us total 35.643ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 345us total 15.073ms
,I/ActivityManager(  826): Start proc 4698:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/GAV2    ( 4698): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4698): Created application version: 3.6.8 (30608)
,I/art     (  826): Explicit concurrent mark sweep GC freed 22040(950KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 1.707ms total 54.188ms
,I/BooksSync( 4698): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4681): Connecting to GoogleApiClient
,I/BooksConfig( 4698): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/KeepSync( 4681): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4698): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4698): Soft error
E/BooksSync( 4698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4698): Sync error
E/BooksSync( 4698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4698): Finished books sync
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 208017, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4681): IOException
E/KeepSync( 4681): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4681): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4681): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4681): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4681): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4681): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4681): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4681): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4681): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4681): 	... 10 more
W/KeepSync( 4681): Sync result 2
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 207868, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  826): Start proc 4743:com.google.android.apps.docs/u0a46 for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 4520): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4520): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4520): 	at jdm.a(PG:82)
E/HttpOperation( 4520): 	at jcs.o(PG:406)
E/HttpOperation( 4520): 	at jcn.a(PG:1379)
E/HttpOperation( 4520): 	at jcs.i(PG:143)
E/HttpOperation( 4520): 	at blb.a(PG:3937)
E/HttpOperation( 4520): 	at czp.a(PG:18188)
E/HttpOperation( 4520): 	at czp.a(PG:9087)
E/HttpOperation( 4520): 	at czq.run(PG:1686)
E/HttpOperation( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4520): 	at jdj.a(PG:4091)
E/HttpOperation( 4520): 	at jdj.a(PG:1125)
E/HttpOperation( 4520): 	at jdm.a(PG:77)
E/HttpOperation( 4520): 	... 12 more
E/HttpOperation( 4520): Caused by: faj: BadAuthentication
E/HttpOperation( 4520): 	at fal.a(PG:38)
E/HttpOperation( 4520): 	at jdj.a(PG:4089)
E/HttpOperation( 4520): 	... 14 more
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 15346(890KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.006ms total 24.250ms
,I/ActivityManager(  826): Killing 3806:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,I/GAv4    ( 4743): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4743):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4743):   adb logcat -s GAv4
,W/GAv4    ( 4743): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 4743): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4743): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/HttpOperation( 4520): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4520): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4520): 	at jdm.a(PG:82)
E/HttpOperation( 4520): 	at jcs.o(PG:406)
E/HttpOperation( 4520): 	at jcn.a(PG:1379)
E/HttpOperation( 4520): 	at jcs.i(PG:143)
E/HttpOperation( 4520): 	at blb.a(PG:3937)
E/HttpOperation( 4520): 	at czp.a(PG:18188)
E/HttpOperation( 4520): 	at czp.a(PG:9081)
E/HttpOperation( 4520): 	at czq.run(PG:1686)
E/HttpOperation( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4520): 	at jdj.a(PG:4091)
E/HttpOperation( 4520): 	at jdj.a(PG:1125)
E/HttpOperation( 4520): 	at jdm.a(PG:77)
E/HttpOperation( 4520): 	... 12 more
E/HttpOperation( 4520): Caused by: faj: BadAuthentication
E/HttpOperation( 4520): 	at fal.a(PG:38)
E/HttpOperation( 4520): 	at jdj.a(PG:4089)
E/HttpOperation( 4520): 	... 14 more
,W/AnalyticsTrackerProxyImpl( 4743): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4520): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4520): java.io.IOException: Cannot obtain authentication token,
E/HttpOperation( 4520): 	at jdm.a(PG:82)
E/HttpOperation( 4520): 	at jcs.o(PG:406)
E/HttpOperation( 4520): 	at jcn.a(PG:1379)
E/HttpOperation( 4520): 	at jcs.i(PG:143)
E/HttpOperation( 4520): 	at hec.a(PG:42)
E/HttpOperation( 4520): 	at hee.a(PG:102)
E/HttpOperation( 4520): 	at czr.a(PG:65)
E/HttpOperation( 4520): 	at kka.a(PG:108)
,E/HttpOperation( 4520): 	at czp.a(PG:19176)
E/HttpOperation( 4520): 	at czp.a(PG:9081)
E/HttpOperation( 4520): 	at czq.run(PG:1686)
E/HttpOperation( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4520): 	at jdj.a(PG:4091)
E/HttpOperation( 4520): ,	at jdj.a(PG:1125)
E/HttpOperation( 4520): 	at jdm.a(PG:77)
E/HttpOperation( 4520): 	... 15 more
E/HttpOperation( 4520): Caused by: faj: BadAuthentication
E/HttpOperation( 4520): 	at fal.a(PG:38)
E/HttpOperation( 4520): 	at jdj.a(PG:4089)
E/HttpOperation( 4520): 	... 17 more
E/ExperimentLoader( 4520): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4520): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4520): 	at jdm.a(PG:82)
E/ExperimentLoader( 4520): ,	at jcs.o(PG:406)
E/ExperimentLoader( 4520): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4520): 	at jcs.i(PG:143)
E/ExperimentLoader( 4520): 	at hec.a(PG:42)
E/ExperimentLoader( 4520): 	at hee.a(PG:102)
E/ExperimentLoader( 4520): 	at czr.a(PG:65)
E/ExperimentLoader( 4520): 	at kka.a(PG:108)
E/ExperimentLoader( 4520): 	at czp.a(PG:19176)
E/ExperimentLoader( 4520): 	at czp.a(PG:9081)
E/ExperimentLoader( 4520): 	at czq.run(PG:1686)
E/ExperimentLoader( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
,E/ExperimentLoader( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4520): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4520): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4520): 	at jdm.a(PG:77)
E/ExperimentLoader( 4520): 	... 15 more
E/ExperimentLoader( 4520): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4520): 	at fal.a(PG:38)
E/ExperimentLoader( 4520): 	at jdj.a(PG:4089)
,E/ExperimentLoader( 4520): 	... 17 more
,W/ResourcesManager( 4743): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4743): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 4743): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4743): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4743): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  826): Killing 3758:com.google.android.gms.unstable/u0a11 (adj 15): empty #17
,I/ProviderInstaller( 4743): Installed default security provider GmsCore_OpenSSL
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 176535, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  826): Killing 4312:com.google.android.apps.docs.editors.sheets/u0a48 (adj 15): empty #17,
,I/GAV2    ( 4698): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 4452): [495] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 4452): [495] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4520): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4520): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4520): 	at jdm.a(PG:82)
E/HttpOperation( 4520): 	at jcs.o(PG:406)
E/HttpOperation( 4520): 	at jcn.a(PG:1379)
E/HttpOperation( 4520): 	at jcs.i(PG:143)
E/HttpOperation( 4520): 	at blb.a(PG:3937)
E/HttpOperation( 4520): 	at czp.a(PG:18188)
E/HttpOperation( 4520): 	at czp.a(PG:9081)
E/HttpOperation( 4520): 	at czq.run(PG:1686)
E/HttpOperation( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4520): 	at jdj.a(PG:4091)
E/HttpOperation( 4520): 	at jdj.a(PG:1125)
E/HttpOperation( 4520): 	at jdm.a(PG:77)
E/HttpOperation( 4520): 	... 12 more
E/HttpOperation( 4520): Caused by: faj: BadAuthentication
E/HttpOperation( 4520): 	at fal.a(PG:38)
E/HttpOperation( 4520): 	at jdj.a(PG:4089)
E/HttpOperation( 4520): 	... 14 more
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 4520): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 4520): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4520): 	at jdm.a(PG:82)
E/HttpOperation( 4520): 	at jcs.o(PG:406)
E/HttpOperation( 4520): 	at jcn.a(PG:1379)
E/HttpOperation( 4520): 	at jcs.i(PG:143)
E/HttpOperation( 4520): ,	at hec.a(PG:42)
E/HttpOperation( 4520): 	at hee.a(PG:102)
E/HttpOperation( 4520): 	at czr.a(PG:65)
E/HttpOperation( 4520): 	at kka.a(PG:108)
E/HttpOperation( 4520): 	at czp.a(PG:19176)
E/HttpOperation( 4520): 	at czp.a(PG:9081),
E/HttpOperation( 4520): 	at czq.run(PG:1686)
E/HttpOperation( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
,E/HttpOperation( 4520): 	at jdj.a(PG:4091)
E/HttpOperation( 4520): 	at jdj.a(PG:1125)
E/HttpOperation( 4520): 	at jdm.a(PG:77)
E/HttpOperation( 4520): 	... 15 more
E/HttpOperation( 4520): Caused by: faj: BadAuthentication
E/HttpOperation( 4520): 	at fal.a(PG:38)
E/HttpOperation( 4520): 	at jdj.a(PG:4089)
E/HttpOperation( 4520): ,	... 17 more
E/ExperimentLoader( 4520): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4520): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4520): 	at jdm.a(PG:82)
E/ExperimentLoader( 4520): 	at jcs.o(PG:406)
E/ExperimentLoader( 4520): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4520): 	at jcs.i(PG:143)
E/ExperimentLoader( 4520): 	at hec.a(PG:42)
E/ExperimentLoader( 4520): 	at hee.a(PG:102)
E/ExperimentLoader( 4520): 	at czr.a(PG:65)
E/ExperimentLoader( 4520): 	at kka.a(PG:108)
E/ExperimentLoader( 4520): 	at czp.a(PG:19176)
E/ExperimentLoader( 4520): 	at czp.a(PG:9081)
E/ExperimentLoader( 4520): 	at czq.run(PG:1686)
E/ExperimentLoader( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4520): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4520): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4520): 	at jdm.a(PG:77)
E/ExperimentLoader( 4520): 	... 15 more
E/ExperimentLoader( 4520): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4520): 	at fal.a(PG:38)
E/ExperimentLoader( 4520): 	at jdj.a(PG:4089)
,E/ExperimentLoader( 4520): 	... 17 more
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 269742, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  826): Explicit concurrent mark sweep GC freed 32521(1434KB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.666ms total 94.832ms
,V/GoogleAuthProtoRequest( 4565): [497] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4565): [497] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4565): [497] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4565): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4565): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4565): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4565): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,I/BooksSync( 4698): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4681): Connecting to GoogleApiClient
,I/BooksConfig( 4698): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4681): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4698): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4698): Soft error
E/BooksSync( 4698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4698): Sync error
E/BooksSync( 4698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4698): Finished books sync
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 297780, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 4681): IOException
E/KeepSync( 4681): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4681): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4681): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4681): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4681): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4681): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4681): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4681): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4681): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4681): 	... 10 more
,W/KeepSync( 4681): Sync result 2
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 297752, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 4520): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 4520): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4520): 	at jdm.a(PG:82)
,E/HttpOperation( 4520): 	at jcs.o(PG:406)
E/HttpOperation( 4520): 	at jcn.a(PG:1379),
E/HttpOperation( 4520): 	at jcs.i(PG:143)
E/HttpOperation( 4520): 	at blb.a(PG:3937)
E/HttpOperation( 4520): 	at czp.a(PG:18188)
E/HttpOperation( 4520): 	,at czp.a(PG:9081)
E/HttpOperation( 4520): 	at czq.run(PG:1686)
E/HttpOperation( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4520): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
,E/HttpOperation( 4520): 	at jdj.a(PG:4091)
E/HttpOperation( 4520): 	at jdj.a(PG:1125)
E/HttpOperation( 4520): 	,at jdm.a(PG:77)
,E/HttpOperation( 4520): ,	... 12 more
E/HttpOperation( 4520): Caused by: faj: BadAuthentication
E/HttpOperation( 4520): 	at fal.a(PG:38)
E/HttpOperation( 4520): 	at jdj.a(PG:4089)
E/HttpOperation( 4520): ,	... 14 more
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4520): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4520): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4520): 	at jdm.a(PG:82)
E/HttpOperation( 4520): 	at jcs.o(PG:406)
E/HttpOperation( 4520): 	at jcn.a(PG:1379)
E/HttpOperation( 4520): 	at jcs.i(PG:143)
E/HttpOperation( 4520): 	at hec.a(PG:42)
E/HttpOperation( 4520): 	at hee.a(PG:102)
E/HttpOperation( 4520): 	at czr.a(PG:65)
E/HttpOperation( 4520): 	at kka.a(PG:108)
E/HttpOperation( 4520): 	at czp.a(PG:19176)
E/HttpOperation( 4520): 	at czp.a(PG:9081)
E/HttpOperation( 4520): 	at czq.run(PG:1686)
E/HttpOperation( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4520): 	at jdj.a(PG:4091)
E/HttpOperation( 4520): 	at jdj.a(PG:1125)
E/HttpOperation( 4520): 	at jdm.a(PG:77)
E/HttpOperation( 4520): 	... 15 more
E/HttpOperation( 4520): Caused by: faj: BadAuthentication
E/HttpOperation( 4520): 	at fal.a(PG:38)
E/HttpOperation( 4520): 	at jdj.a(PG:4089)
E/HttpOperation( 4520): 	... 17 more
,E/ExperimentLoader( 4520): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4520): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4520): 	at jdm.a(PG:82)
E/ExperimentLoader( 4520): 	at jcs.o(PG:406)
E/ExperimentLoader( 4520): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4520): 	at jcs.i(PG:143)
E/ExperimentLoader( 4520): 	at hec.a(PG:42)
E/ExperimentLoader( 4520): 	at hee.a(PG:102)
E/ExperimentLoader( 4520): 	at czr.a(PG:65)
E/ExperimentLoader( 4520): 	at kka.a(PG:108)
E/ExperimentLoader( 4520): 	at czp.a(PG:19176)
E/ExperimentLoader( 4520): 	at czp.a(PG:9081)
E/ExperimentLoader( 4520): 	at czq.run(PG:1686)
E/ExperimentLoader( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4520): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4520): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4520): 	at jdm.a(PG:77)
E/ExperimentLoader( 4520): 	... 15 more
E/ExperimentLoader( 4520): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4520): 	at fal.a(PG:38)
E/ExperimentLoader( 4520): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4520): 	... 17 more
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 361843, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3162): Connected to the server!
I/jxcore-log( 3162): 
,I/chromium( 3162): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GoogleAuthProtoRequest( 4565): [498] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 4565): [498] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4565): [498] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4565): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4565): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4565): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4565): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,V/KeepSync( 4681): Connecting to GoogleApiClient
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4681): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 44339(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 27MB/43MB, paused 1.631ms total 47.280ms
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4681): IOException
E/KeepSync( 4681): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4681): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4681): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4681): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4681): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4681): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4681): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4681): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4681): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4681): 	... 10 more
W/KeepSync( 4681): Sync result 2
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 448748, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 4698): Starting books sync for 61035162, extras: ade,
,I/BooksConfig( 4698): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  826): Explicit concurrent mark sweep GC freed 32556(1393KB) AllocSpace objects, 7(300KB) LOS objects, 32% free, 33MB/49MB, paused 2.093ms total 94.785ms
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4698): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4698): Soft error
E/BooksSync( 4698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4698): Sync error
E/BooksSync( 4698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4698): Finished books sync
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 448931, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  826): Start proc 4858:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4858): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4858):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4858):   adb logcat -s GAv4
,W/GAv4    ( 4858): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4858): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4858): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  826): Killing 4389:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1408): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1408): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1408): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1408): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4452): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4452): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4452): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 4452): 	,at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4452): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 4452): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4452): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 4452): Ignoring header User-Agent because its value was null.
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4520): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4520): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4520): 	at jdm.a(PG:82)
E/HttpOperation( 4520): 	at jcs.o(PG:406)
E/HttpOperation( 4520): 	at jcn.a(PG:1379)
E/HttpOperation( 4520): 	at jcs.i(PG:143)
E/HttpOperation( 4520): 	at blb.a(PG:3937)
E/HttpOperation( 4520): 	at czp.a(PG:18188)
E/HttpOperation( 4520): 	at czp.a(PG:9081)
E/HttpOperation( 4520): 	at czq.run(PG:1686)
E/HttpOperation( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4520): 	at jdj.a(PG:4091)
E/HttpOperation( 4520): 	at jdj.a(PG:1125)
E/HttpOperation( 4520): 	at jdm.a(PG:77)
E/HttpOperation( 4520): 	... 12 more
E/HttpOperation( 4520): Caused by: faj: BadAuthentication
E/HttpOperation( 4520): 	at fal.a(PG:38)
E/HttpOperation( 4520): 	at jdj.a(PG:4089)
E/HttpOperation( 4520): 	... 14 more
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4520): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4520): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4520): 	at jdm.a(PG:82)
E/HttpOperation( 4520): 	at jcs.o(PG:406)
E/HttpOperation( 4520): 	at jcn.a(PG:1379)
E/HttpOperation( 4520): 	at jcs.i(PG:143)
E/HttpOperation( 4520): 	at hec.a(PG:42)
E/HttpOperation( 4520): 	at hee.a(PG:102)
E/HttpOperation( 4520): 	at czr.a(PG:65)
E/HttpOperation( 4520): 	at kka.a(PG:108)
E/HttpOperation( 4520): 	at czp.a(PG:19176)
E/HttpOperation( 4520): 	at czp.a(PG:9081)
E/HttpOperation( 4520): 	at czq.run(PG:1686)
E/HttpOperation( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4520): 	at jdj.a(PG:4091)
E/HttpOperation( 4520): 	at jdj.a(PG:1125)
E/HttpOperation( 4520): 	at jdm.a(PG:77)
E/HttpOperation( 4520): 	... 15 more
E/HttpOperation( 4520): Caused by: faj: BadAuthentication
E/HttpOperation( 4520): 	at fal.a(PG:38)
E/HttpOperation( 4520): 	at jdj.a(PG:4089)
E/HttpOperation( 4520): 	... 17 more
,E/ExperimentLoader( 4520): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4520): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4520): 	at jdm.a(PG:82)
E/ExperimentLoader( 4520): 	at jcs.o(PG:406)
E/ExperimentLoader( 4520): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4520): 	at jcs.i(PG:143),
E/ExperimentLoader( 4520): 	at hec.a(PG:42)
E/ExperimentLoader( 4520): 	at hee.a(PG:102)
E/ExperimentLoader( 4520): 	at czr.a(PG:65)
E/ExperimentLoader( 4520): 	at kka.a(PG:108)
E/ExperimentLoader( 4520): 	at czp.a(PG:19176)
,E/ExperimentLoader( 4520): 	at czp.a(PG:9081)
E/ExperimentLoader( 4520): 	at czq.run(PG:1686)
E/ExperimentLoader( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/ExperimentLoader( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4520): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4520): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4520): 	at jdm.a(PG:77)
E/ExperimentLoader( 4520): 	... 15 more,
E/ExperimentLoader( 4520): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4520): 	at fal.a(PG:38)
E/ExperimentLoader( 4520): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4520): 	... 17 more
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 516964, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 4565): [499] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4565): [499] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4565): [499] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4565): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4565): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4565): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4565): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,V/KeepSync( 4681): Connecting to GoogleApiClient
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4681): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4681): IOException
E/KeepSync( 4681): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4681): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4681): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4681): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4681): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4681): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4681): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4681): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4681): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4681): 	... 10 more
,W/KeepSync( 4681): Sync result 2
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 693937, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 4698): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4698): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 4698): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4698): Soft error
E/BooksSync( 4698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4698): Sync error
,E/BooksSync( 4698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4698): Finished books sync
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 694822, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/EventLogService( 1729): Opted in for usage reporting
,I/EventLogService( 1729): Aggregate from 1450100393027 (log), 1450099096834 (data)
,W/EventLogAggregator( 1729): Unknown tag: snet_gcore
,W/EventLogAggregator( 1729): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1729): dumping service [account]
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,I/art     (  826): Explicit concurrent mark sweep GC freed 37465(1706KB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 1.475ms total 84.264ms
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4520): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4520): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4520): 	at jdm.a(PG:82)
E/HttpOperation( 4520): 	at jcs.o(PG:406)
E/HttpOperation( 4520): 	at jcn.a(PG:1379)
E/HttpOperation( 4520): 	at jcs.i(PG:143)
E/HttpOperation( 4520): 	at blb.a(PG:3937)
E/HttpOperation( 4520): 	at czp.a(PG:18188)
E/HttpOperation( 4520): 	at czp.a(PG:9081)
E/HttpOperation( 4520): 	at czq.run(PG:1686)
E/HttpOperation( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4520): 	at jdj.a(PG:4091)
E/HttpOperation( 4520): 	at jdj.a(PG:1125)
E/HttpOperation( 4520): 	at jdm.a(PG:77)
E/HttpOperation( 4520): 	... 12 more
E/HttpOperation( 4520): Caused by: faj: BadAuthentication
E/HttpOperation( 4520): 	at fal.a(PG:38)
E/HttpOperation( 4520): 	at jdj.a(PG:4089)
E/HttpOperation( 4520): 	... 14 more
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 50430(2MB) AllocSpace objects, 6(661KB) LOS objects, 36% free, 27MB/43MB, paused 1.779ms total 32.150ms
,E/HttpOperation( 4520): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4520): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4520): 	at jdm.a(PG:82)
E/HttpOperation( 4520): 	at jcs.o(PG:406)
E/HttpOperation( 4520): 	at jcn.a(PG:1379)
E/HttpOperation( 4520): 	at jcs.i(PG:143)
E/HttpOperation( 4520): 	at hec.a(PG:42)
E/HttpOperation( 4520): 	at hee.a(PG:102)
E/HttpOperation( 4520): 	at czr.a(PG:65)
E/HttpOperation( 4520): 	at kka.a(PG:108)
E/HttpOperation( 4520): 	at czp.a(PG:19176)
E/HttpOperation( 4520): 	at czp.a(PG:9081)
E/HttpOperation( 4520): 	at czq.run(PG:1686)
E/HttpOperation( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4520): 	at jdj.a(PG:4091)
E/HttpOperation( 4520): 	at jdj.a(PG:1125)
E/HttpOperation( 4520): 	at jdm.a(PG:77)
E/HttpOperation( 4520): 	... 15 more
E/HttpOperation( 4520): Caused by: faj: BadAuthentication
E/HttpOperation( 4520): 	at fal.a(PG:38)
E/HttpOperation( 4520): 	at jdj.a(PG:4089)
E/HttpOperation( 4520): 	... 17 more
E/ExperimentLoader( 4520): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4520): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4520): 	at jdm.a(PG:82)
E/ExperimentLoader( 4520): 	at jcs.o(PG:406)
E/ExperimentLoader( 4520): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4520): 	at jcs.i(PG:143)
E/ExperimentLoader( 4520): 	at hec.a(PG:42)
E/ExperimentLoader( 4520): 	at hee.a(PG:102)
E/ExperimentLoader( 4520): 	at czr.a(PG:65)
E/ExperimentLoader( 4520): 	at kka.a(PG:108)
E/ExperimentLoader( 4520): 	at czp.a(PG:19176)
E/ExperimentLoader( 4520): 	at czp.a(PG:9081)
E/ExperimentLoader( 4520): 	at czq.run(PG:1686)
E/ExperimentLoader( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4520): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4520): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4520): 	at jdm.a(PG:77)
E/ExperimentLoader( 4520): 	... 15 more
E/ExperimentLoader( 4520): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4520): 	at fal.a(PG:38)
E/ExperimentLoader( 4520): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4520): 	... 17 more
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 777874, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,W/bt-btm  ( 3220): Stopping oneshot timer
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 4565): [500] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GCM     ( 1729): Message from null null
E/GCM     ( 1729): Dropping message from null
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/GCM     ( 1408): Message class com.google.f.a.a.i
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4565): [500] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4565): [500] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4565): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4565): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4565): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4565): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4565): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4565): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,V/KeepSync( 4681): Connecting to GoogleApiClient
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4681): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4681): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4681): IOException
E/KeepSync( 4681): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4681): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4681): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4681): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4681): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4681): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4681): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4681): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4681): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4681): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4681): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4681): 	... 10 more
W/KeepSync( 4681): Sync result 2
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1183762, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,I/UsageStatsService(  826): User[0] Flushing usage stats to disk
,I/BooksSync( 4698): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4698): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4698): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4698): Soft error
E/BooksSync( 4698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4698): Sync error
E/BooksSync( 4698): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4698): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4698): Finished books sync
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1214635, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4520): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4520): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4520): 	at jdm.a(PG:82)
E/HttpOperation( 4520): 	at jcs.o(PG:406)
E/HttpOperation( 4520): 	at jcn.a(PG:1379)
E/HttpOperation( 4520): 	at jcs.i(PG:143)
E/HttpOperation( 4520): 	at blb.a(PG:3937)
E/HttpOperation( 4520): 	at czp.a(PG:18188)
E/HttpOperation( 4520): 	at czp.a(PG:9081)
E/HttpOperation( 4520): 	at czq.run(PG:1686)
E/HttpOperation( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4520): 	at jdj.a(PG:4091)
E/HttpOperation( 4520): 	at jdj.a(PG:1125)
E/HttpOperation( 4520): 	at jdm.a(PG:77)
E/HttpOperation( 4520): 	... 12 more
E/HttpOperation( 4520): Caused by: faj: BadAuthentication
E/HttpOperation( 4520): 	at fal.a(PG:38)
E/HttpOperation( 4520): 	at jdj.a(PG:4089)
E/HttpOperation( 4520): 	... 14 more
,I/GLSUser ( 1408): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1408): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1408): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1408): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1408): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 4520): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4520): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4520): 	at jdm.a(PG:82)
E/HttpOperation( 4520): 	at jcs.o(PG:406)
E/HttpOperation( 4520): 	at jcn.a(PG:1379)
E/HttpOperation( 4520): 	at jcs.i(PG:143)
E/HttpOperation( 4520): 	at hec.a(PG:42)
E/HttpOperation( 4520): 	at hee.a(PG:102)
E/HttpOperation( 4520): 	at czr.a(PG:65)
E/HttpOperation( 4520): 	at kka.a(PG:108)
E/HttpOperation( 4520): 	at czp.a(PG:19176)
E/HttpOperation( 4520): 	at czp.a(PG:9081)
E/HttpOperation( 4520): 	at czq.run(PG:1686)
E/HttpOperation( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4520): 	at jdj.a(PG:4091)
E/HttpOperation( 4520): 	at jdj.a(PG:1125)
E/HttpOperation( 4520): 	at jdm.a(PG:77)
E/HttpOperation( 4520): 	... 15 more
E/HttpOperation( 4520): Caused by: faj: BadAuthentication
E/HttpOperation( 4520): 	at fal.a(PG:38)
E/HttpOperation( 4520): 	at jdj.a(PG:4089)
E/HttpOperation( 4520): 	... 17 more
E/ExperimentLoader( 4520): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4520): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4520): 	at jdm.a(PG:82)
E/ExperimentLoader( 4520): 	at jcs.o(PG:406)
E/ExperimentLoader( 4520): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4520): 	at jcs.i(PG:143)
E/ExperimentLoader( 4520): 	at hec.a(PG:42)
E/ExperimentLoader( 4520): 	at hee.a(PG:102)
E/ExperimentLoader( 4520): 	at czr.a(PG:65)
E/ExperimentLoader( 4520): 	at kka.a(PG:108)
E/ExperimentLoader( 4520): 	at czp.a(PG:19176)
E/ExperimentLoader( 4520): 	at czp.a(PG:9081)
E/ExperimentLoader( 4520): 	at czq.run(PG:1686)
E/ExperimentLoader( 4520): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4520): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4520): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4520): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4520): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4520): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4520): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4520): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4520): 	at jdm.a(PG:77)
E/ExperimentLoader( 4520): 	... 15 more
E/ExperimentLoader( 4520): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4520): 	at fal.a(PG:38)
E/ExperimentLoader( 4520): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4520): 	... 17 more
,D/SyncManager(  826): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1305671, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  826): Explicit concurrent mark sweep GC freed 44366(2MB) AllocSpace objects, 14(601KB) LOS objects, 32% free, 33MB/49MB, paused 2.737ms total 74.537ms
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,I/art     ( 1408): Explicit concurrent mark sweep GC freed 72149(3MB) AllocSpace objects, 13(1434KB) LOS objects, 36% free, 27MB/43MB, paused 1.653ms total 50.511ms
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  826): Prepared write state in 17ms
,I/ProcessStatsService(  826): Pruning old procstats: /data/system/procstats/state-2015-12-13-11-36-54.bin
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3220): Disconnected process message: 10, size: 0
,W/bt-btm  ( 3220): Stopping oneshot timer
,TIME-OUT KILL (timeout was 1800000ms)
```
