#### Test 5133502802397d9_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.01 rxSuccessRate=4.68 targetRoamBSSID=any RSSI=-44
,E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2462,5220
D/AndroidRuntime( 3512): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3512): CheckJNI is OFF
D/AndroidRuntime( 3512): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{267de1e2 token=Token{12ce3aad ActivityRecord{34b69bc4 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
V/WindowManager(  820): Adding window Window{2652f9cf u0 Starting com.test.thalitest} at 3 of 8 (after Window{2e3f50e8 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/MicrophoneInputStream( 1473): mic_close com.google.android.apps.gsa.speech.audio.u@3707b502
I/HotwordDetector( 1473): Closing mic
D/AndroidRuntime( 3512): Shutting down VM
D/audio_hw_primary(  355): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  355): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  355): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/ActivityManager(  820): Start proc 3527:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
I/HotwordRecognitionRnr( 1473): Stopping hotword detection.
I/HotwordRecognitionRnr( 1473): Hotword detection finished
I/ActivityManager(  820): Killing 2982:com.google.android.gm/u0a78 (adj 15): empty #17
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660503315
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 3527): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/kickstart(  876): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000,
I/kickstart(  876): STATUS: Wrote to /sys/power/wake_lock
V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LibraryLoader( 3527): Time to load native libraries: 1 ms (timestamps 2461-2462)
,I/LibraryLoader( 3527): Expected native library version number "",actual native library version number ""
D/Finsky  ( 2925): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2925): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2925): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ActivityManager(  820): Killing 2549:com.google.android.calendar/u0a37 (adj 15): empty #17
,V/WebViewChromiumFactoryProvider( 3527): Binding Chromium to main looper Looper (main, tid 1) {3babc6e}
I/LibraryLoader( 3527): Expected native library version number "",actual native library version number ""
,I/chromium( 3527): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3527): Initializing chromium process, singleProcess=true
,W/art     ( 3527): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3527): ApplicationContext is null in ApplicationStatus
,E/kickstart(  876): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1,
I/kickstart(  876): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,W/chromium( 3527): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3527): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3527): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3527): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@307dbcb7:true
,D/BluetoothAdapter( 3527): 773990821: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3527): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3527): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3527): CordovaWebView is running on device made by: motorola,
,W/art     ( 3527): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3527): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3527): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3527): Validating map...
,V/WindowManager(  820): Adding window Window{25ebb8f9 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{2652f9cf u0 Starting com.test.thalitest})
,W/chromium( 3527): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3527): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3527): Enabling debug mode 0
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +777ms (total +1m50s26ms)
,I/Keyboard.Facilitator( 1212): onFinishInput()
,W/BindingManager( 3527): Cannot call determinedVisibility() - never saw a connection for the pid: 3527
,D/JsMessageQueue( 3527): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3527): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576400896
D/JX-Cordova( 3527): jxcore cordova android initializing
,I/kickstart(  876): STATUS: Received file 'm9kefs1'
I/kickstart(  876): STATUS: 950272 bytes transferred in 0.996484 seconds
I/kickstart(  876): STATUS: Successfully downloaded files from target 
I/kickstart(  876): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  876): STATUS: Sahara protocol completed
,W/jxcore-log( 3527): Initializing JXcore engine
W/jxcore-log( 3527): JXcore engine is ready
,W/jxcore-log( 3527): Starting JXcore engine
,W/.test.thalitest( 3527): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12888]" dev="sockfs" ino=12888 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3527): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3527): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13056]" dev="sockfs" ino=13056 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3527): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22065]" dev="sockfs" ino=22065 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3527): Platform android
W/jxcore-log( 3527): 
,W/jxcore-log( 3527): Process ARCH arm
W/jxcore-log( 3527): 
,I/jxcore-log( 3527): JXcore Cordova bridge is ready!
I/jxcore-log( 3527): 
W/jxcore-log( 3527): JXcore engine is started
,I/Choreographer( 3527): Skipped 114 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3527): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3527): Toggling radios to true
I/jxcore-log( 3527): 
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  820): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  820): Message: 1
D/BluetoothManagerService(  820): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  820): setWifiEnabled: true pid=3527, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  820): New client listening to asynchronous messages
,I/jxcore-log( 3527): Radios toggled
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  351): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1548): Read error: ssl=0xb4888800: I/O error during system call, Connection timed out,
,V/NativeCrypto( 1548): SSL shutdown failed: ssl=0xb4888800: I/O error during system call, Broken pipe
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ActivityManager(  820): Start proc 3585:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,E/WifiStateMachine(  820): Start Disconnecting Watchdog 1
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,W/ResourcesManager( 3585): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/CommandListener(  351): Clearing all IP addresses on wlan0
,I/GoogleURLConnFactory( 1548): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524292
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state CompletedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 3110): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkChangeNotifierAutoDetect( 1473): Network connectivity changed, type is: 6
,D/Tethering(  820): MasterInitialState.processMessage what=3
,E/WifiConfigStore(  820): Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): will read network variables netId=0
V/MusicLeanback( 3110): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
E/WifiConfigStore(  820): will read network variables netId=0
,I/wpa_supplicant( 1246): wlan0: Trying to associate with SSID 'NG7005g'
W/Uploader( 1548): No account for auth token provided
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
,D/Uploader( 1548): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/ActivityManager(  820): Start proc 3611:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,D/AdapterServiceConfig( 3585): Adding HeadsetService
D/AdapterServiceConfig( 3585): Adding A2dpService
,D/AdapterServiceConfig( 3585): Adding HidService
D/AdapterServiceConfig( 3585): Adding HealthService
D/AdapterServiceConfig( 3585): Adding PanService
D/AdapterServiceConfig( 3585): Adding GattService
D/AdapterServiceConfig( 3585): Adding BluetoothMapService
,E/GpsLocationProvider(  820): No APN found to select.
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@202ec4ee:true
D/BluetoothAdapterState( 3585): make
,I/bluedroid( 3585): init
I/BluetoothAdapterState( 3585): Entering OffState
,I/bte_conf( 3585): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,I/bte_conf( 3585): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3585): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3585): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3585): get_profile_interface socket
I/bluedroid( 3585): get_profile_interface map_client
I/GKI_LINUX( 3585): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3585): Address is:F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  820): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  820): Stored Bluetooth name: Nexus 6
D/BluetoothAdapterProperties( 3585): Name is: Nexus 6
D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/SprintDMReceiver( 3611): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3611): simOperator:  IMSI: null
D/SprintDMReceiver( 3611): Not Sprint UICC, don't do anything.
,I/art     (  820): Explicit concurrent mark sweep GC freed 46509(2MB) AllocSpace objects, 11(176KB) LOS objects, 32% free, 33MB/49MB, paused 1.172ms total 49.733ms
I/SystemUpdateService( 1823): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/BluetoothManagerService(  820): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  820): Message: 40
,D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3585): config_hci_snoop_log
D/BluetoothManagerService(  820): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  820): Broadcasting onBluetoothServiceUp() to 7 receivers.
E/GpsLocationProvider(  820): No APN found to select.
,D/SystemUpdateService( 1823): onCreate
,D/BluetoothAdapterState( 3585): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3585): Setting state to 11
I/BluetoothAdapterState( 3585): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  820): Message: 60
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  820): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3585): make
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,D/SystemUpdateService( 1823): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/BluetoothAdapterService( 3585): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ffef0f
D/HeadsetService( 3585): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3585): classInitNative: succeeds
D/HeadsetStateMachine( 3585): make
,I/BluetoothAdapterState( 3585): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3585): max_hf_connections = 1
I/bluedroid( 3585): get_profile_interface handsfree
D/HeadsetStateMachine( 3585): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3585): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ffef0f
,D/BluetoothA2dp(  820): Proxy object connected
D/A2dpService( 3585): Received start request. Starting profile...
,D/BluetoothA2dp( 1064): Proxy object connected
I/BluetoothAvrcpServiceJni( 3585): classInitNative: succeeds
I/bluedroid( 3585): get_profile_interface avrcp
,E/RemoteController( 3585): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3585): classInitNative: succeeds
D/A2dpStateMachine( 3585): make
,I/bluedroid( 3585): get_profile_interface a2dp
I/GKI_LINUX( 3585): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothHidServiceJni( 3585): classInitNative: succeeds
D/A2dpStateMachine( 3585): Enter Disconnected: -2,
D/BluetoothAdapterService( 3585): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ffef0f
,D/BluetoothInputDevice( 1064): Proxy object connected
,D/HidService( 3585): Received start request. Starting profile...
I/bluedroid( 3585): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3585): classInitNative: succeeds,
D/BluetoothAdapterService( 3585): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ffef0f,
I/SystemUpdateService( 1823): active receiver: enabled,
D/HealthService( 3585): Received start request. Starting profile...
I/bluedroid( 3585): get_profile_interface health
I/BluetoothPanServiceJni( 3585): classInitNative(L105): succeeds,
D/BluetoothAdapterService( 3585): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ffef0f
D/PanService( 3585): Received start request. Starting profile...
D/BluetoothPan( 1064): BluetoothPAN Proxy object connected
,D/BluetoothPanServiceJni( 3585): initializeNative(L110): pan,
I/bluedroid( 3585): get_profile_interface pan
I/BtGatt.JNI( 3585): classInitNative(L873): classInitNative: Success!
I/iu.Environment( 1823): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 1823): num queued entries: 0
I/iu.UploadsManager( 1823): num updated entries: 0
D/BluetoothAdapterService( 3585): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ffef0f
I/iu.SyncManager( 1823): NEXT; no task
D/BtGatt.DebugUtils( 3585): handleDebugAction() action=null
D/BtGatt.GattService( 3585): Received start request. Starting profile...
D/BtGatt.GattService( 3585): start(),
I/bluedroid( 3585): get_profile_interface gatt
D/BluetoothAdapterService( 3585): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ffef0f
,D/BtGatt.AdvertiseManager( 3585): advertise manager created
,I/SystemUpdateService( 1823): showing system update notification
,D/ChimeraCfgMgr( 1823): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/BluetoothAdapterService( 3585): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26ffef0f
D/BluetoothMap( 1064): Proxy object connected
D/BluetoothMapService( 3585): Received start request. Starting profile...,
D/BluetoothMapService( 3585): start()
,D/BluetoothMapEmailSettingsLoader( 3585): Found 0 applications
D/BluetoothMapEmailAppObserver( 3585): createReceiver()
,D/BluetoothMapEmailAppObserver( 3585): initObservers()
D/BluetoothMapEmailAppObserver( 3585): getEnabledAccountItems()
,D/HeadsetStateMachine( 3585): Proxy object connected
,D/BluetoothAdapterState( 3585): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3585): enable
,I/GKI_LINUX( 3585): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3585): btu_task pending for preload complete event
,I/bt_hci_bdroid( 3585): init
,I/ValidateNoPeople(  820): skipping global notification
,I/bt_vendor( 3585): init
I/bt_vnd_conf( 3585): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3585): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3585): userial_init
D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3585): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3585): Disconnected process message: 11, size: 0
,V/SystemUpdateService( 1823): retry (wakeup: false) in 3599967 ms
,I/ActivityManager(  820): Start proc 3651:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 2831): connection state changed from UNKNOWN to DISCONNECTED
,D/SystemUpdateService( 1823): onDestroy
,I/ActivityManager(  820): Killing 2391:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/bt_userial_vendor( 3585): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3585): device fd = 53 open
,D/bt_userial( 3585): Entering userial_read_thread()
,I/bt_hwcfg( 3585): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3585): Chipset BCM4354A2
D/bt_hwcfg( 3585): Target name = [BCM4354A2]
,I/bt_hwcfg( 3585): Found patchfile: /vendor/firmware//bcm4354A2.hcd,
,I/wpa_supplicant( 1246): wlan0: Associated with c0:ff:d4:d3:aa:4a,
,I/wpa_supplicant( 1246): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1246): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  351): Setting iface cfg
,E/WifiStateMachine(  820): Start Dhcp Watchdog 2
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 573
E/WifiStateMachine(  820):  RSSI mgmt: -44
E/WifiStateMachine(  820):  BE :  rx=219 tx=148 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=4 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 19025 tx_time=220 rx_time=512 scan_time=0
,I/GAv4    ( 3651): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3651):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3651):   adb logcat -s GAv4
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,W/GAv4    ( 3651): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3651): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3651): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/WebViewFactory( 3651): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3651): Time to load native libraries: 1 ms (timestamps 6285-6286)
I/LibraryLoader( 3651): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3651): Binding Chromium to main looper Looper (main, tid 1) {2b388bad}
,I/LibraryLoader( 3651): Expected native library version number "",actual native library version number ""
I/chromium( 3651): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3651): Initializing chromium process, singleProcess=true
,W/art     ( 3651): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3651): ApplicationContext is null in ApplicationStatus,
,W/chromium( 3651): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3651): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 3651): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3651): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/dhcpcd  ( 3697): version 5.5.6 starting
,I/bt_hwcfg( 3585): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3585): Settlement delay -- 100 ms
I/bt_hwcfg( 3585): Setting fw settlement delay to 100 
,W/AudioManagerAndroid( 3651): Requires BLUETOOTH permission
,I/dhcpcd  ( 3697): wlan0: rebinding lease of 192.168.1.110
,I/NSApplication( 3651): Starting up...
,I/ActivityManager(  820): Killing 1391:android.process.acore/u0a5 (adj 15): empty #17
,I/bt_hwcfg( 3585): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3585): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3585): vendor lib fwcfg completed
,I/bt-btu  ( 3585): btu_task received preload complete event,
,I/        ( 3585): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3585): BTE_InitTraceLevels -- TRC_L2CAP
,I/        ( 3585): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3585): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3585): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3585): BTE_InitTraceLevels -- TRC_A2D
,I/        ( 3585): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3585): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3585): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3585): BTE_InitTraceLevels -- TRC_PAN
,I/        ( 3585): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3585): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3585): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3585): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3585): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3585): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2e49085 
E/bt-btm  ( 3585): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2e49085 
,D/BluetoothAdapterProperties( 3585): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3585): Calling BTA_HhEnable,
E/bt-btif ( 3585): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3585): Address is:F8:CF:C5:D9:E5:61
I/ActivityManager(  820): Start proc 3718:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
D/BluetoothManagerService(  820): Bluetooth Adapter name changed to Nexus 6
D/BluetoothAdapterProperties( 3585): Name is: Nexus 6
D/BluetoothManagerService(  820): Stored Bluetooth name: Nexus 6
W/bt-btm  ( 3585): Stopping oneshot timer
,D/BluetoothAdapterProperties( 3585): Scan Mode:20
,D/BluetoothAdapterProperties( 3585): Discoverable Timeout:120
,D/bte_conf( 3585): Device ID record 1 : primary
D/bte_conf( 3585):   vendorId            = 000f
D/bte_conf( 3585):   vendorIdSource      = 0001
D/bte_conf( 3585):   product             = 1200
D/bte_conf( 3585):   version             = 1436
D/bte_conf( 3585):   clientExecutableURL = 
D/bte_conf( 3585):   serviceDescription  = 
D/bte_conf( 3585):   documentationURL    = 
D/bte_conf( 3585): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 3585): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3585): ScanMode =  20
,D/BluetoothAdapterProperties( 3585): State =  11
D/BluetoothAdapterProperties( 3585): Setting state to 12
I/BluetoothAdapterState( 3585): Bluetooth adapter state changed: 11-> 12
D/BluetoothPanServiceJni( 3585): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService(  820): Message: 60
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  820): Broadcasting onBluetoothStateChange(true) to 13 receivers.
,D/BluetoothA2dp( 1064): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3585): Entering On State
D/BluetoothHeadset( 1064): onBluetoothStateChange: up=true
D/BluetoothManagerService(  820): Creating new ProfileServiceConnections object for profile: 1
D/BluetoothAdapterProperties( 3585): Scan Mode:21
D/BluetoothAdapterProperties( 3585): Discoverable Timeout:120
D/BluetoothPan( 1064): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1278): onBluetoothStateChange: up=true
,D/BluetoothA2dpSink( 1064): onBluetoothStateChange: up=true
E/BluetoothA2dpSink( 1064): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
,D/BluetoothHeadset(  820): onBluetoothStateChange: up=true
D/BluetoothHeadset(  820): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 1064): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  820): onBluetoothStateChange: up=true
D/BluetoothMap( 1064): onBluetoothStateChange: up=true
,D/BluetoothAvrcpController( 1064): onBluetoothStateChange: up=true
E/bt_h4   ( 3585): vendor lib postload completed
,E/BluetoothAvrcpController( 1064): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
,D/BluetoothHeadsetClient( 1064): onBluetoothStateChange: up=true
,E/BluetoothHeadsetClient( 1064): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
,D/BluetoothHeadset(  820): onBluetoothStateChange: up=true,
D/BluetoothManagerService(  820): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  820): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 3585): onReceive
D/BluetoothMapService( 3585): STATE_ON
,D/BluetoothManagerService(  820): Message: 40
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapMasInstance( 3585): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3585): MAS initSocket()
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3585): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3585): Accepting socket connection...
,D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset( 1064): Proxy object connected
,D/BluetoothManagerService(  820): Message: 400
,D/BluetoothHeadset( 1278): Proxy object connected
,D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset(  820): Proxy object connected
D/BluetoothManagerService(  820): Message: 400
,D/BluetoothHeadset(  820): Proxy object connected
,D/BluetoothManagerService(  820): Message: 400,
D/BluetoothHeadset(  820): Proxy object connected
,V/MusicLeanback( 3110): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  820): Killing 3344:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/SprintDMReceiver( 3611): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3611): simOperator:  IMSI: null
D/SprintDMReceiver( 3611): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1823): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1823): onCreate
,D/SystemUpdateService( 1823): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1823): active receiver: enabled
,I/SystemUpdateService( 1823): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,D/ChimeraCfgMgr( 1823): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1823): retry (wakeup: false) in 3599978 ms
,D/SystemUpdateService( 1823): onDestroy
,I/ActivityManager(  820): Start proc 3744:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3527): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3527): 
I/jxcore-log( 3527): my name is : motorola-Nexus 6_PT5708
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): attempting to connect to test coordinator
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): check test folder
I/jxcore-log( 3527): 
I/jxcore-log( 3527): found test : ./testFindPeers.js
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): found test : ./testReConnect.js
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): found test : ./testSendData.js
I/jxcore-log( 3527): 
,I/ActivityManager(  820): Killing 3364:com.android.musicfx/u0a18 (adj 15): empty #17
I/jxcore-log( 3527): Test app app.js loaded
I/jxcore-log( 3527): 
I/Choreographer( 3527): Skipped 123 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
I/chromium( 3527): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  820): Start proc 3765:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,I/dhcpcd  ( 3697): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/art     (  366): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 9.120ms
,I/art     (  366): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 297us total 10.303ms
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/art     (  366): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 312us total 13.005ms
,I/dhcpcd  ( 3697): wlan0: leased 192.168.1.110 for 86400 seconds
,D/StrictMode( 3765): StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3765): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3765): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3765): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3765): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3765): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3765): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3765): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3765): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3765): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3765): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3765): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3765): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3765): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3765): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3765): StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3765): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3765): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3765): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3765): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3765): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3765): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3765): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3765): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3765): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3765): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3765): StrictMode policy violation; ~duration=189 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3765): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3765): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3765): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3765): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3765): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3765): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3765): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3765): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3765): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3765): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3765): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3765): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3765): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3765): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3765): StrictMode policy violation; ~duration=185 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3765): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3765): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3765): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3765): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3765): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3765): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3765): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3765): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3765): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3765): StrictMode policy violation; ~duration=171 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3765): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3765): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3765): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3765): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3765): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3765): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3765): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3765): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3765): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3765): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3765): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3765): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3765): StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3765): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3765): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3765): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3765): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3765): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3765): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3765): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3765): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3765): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3765): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3765): # via Binder call with stack:
D/StrictMode( 3765): android.os.StrictMode$LogStackTrace
D/StrictMode( 3765): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3765): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3765): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3765): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3765): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3765): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3765): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3765): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3765): 	at com.google.b.a.by.a(PG:125)
,D/StrictMode( 3765): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3765): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3765): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3765): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3765): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3765): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3765): StrictMode policy violation; ~duration=43 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3765): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3765): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3765): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3765): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3765): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3765): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
,D/StrictMode( 3765): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3765): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3765): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3765): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3765): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3765): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3765): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3765): StrictMode policy violation; ~duration=42 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3765): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3765): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3765): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3765): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3765): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3765): 	,at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3765): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3765): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3765): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3765): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3765): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3765): StrictMode policy violation; ~duration=42 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3765): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3765): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3765): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3765): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3765): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3765): 	,at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3765): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3765): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3765): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3765): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3765): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3765): StrictMode policy violation; ~duration=41 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3765): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3765): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3765): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3765): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3765): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3765): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3765): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3765): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3765): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3765): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3765): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3765): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
,D/StrictMode( 3765): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3765): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3765): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3765): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3765): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3765): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3765): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3765): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3765): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,W/com.google.a.a.a.b.a( 3765): Application name is not set. Call Builder#setApplicationName.
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
,D/ConnectivityService(  820): Adding iface wlan0 to network 101
E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
,D/BluetoothManagerService(  820): Message: 20,
,D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f7f07d4:true
E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  820): Setting Dns servers for network 101 to [/192.168.1.1]
,I/ActivityManager(  820): Killing 3183:com.google.android.gms.wearable/u0a11 (adj 15): empty #17,
,D/AuthorizationBluetoothService( 1548): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
W/ContextImpl( 3744): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/BluetoothManagerService(  820): Message: 20
,D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1696461f:true
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
D/Tethering(  820): MasterInitialState.processMessage what=3
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/NetworkChangeNotifierAutoDetect( 1473): Network connectivity changed, type is: 2
,I/NetworkMonitor( 3110): type=WIFI subType= reason=null isConnected=true
,W/BluetoothAdapter( 3585): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1548): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/GpsLocationProvider(  820): No APN found to select.
D/LocalBluetoothProfileManager( 3744): Adding local A2DP profile
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3744): Adding local HEADSET profile
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3585): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3585): Accept thread started.
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3744): Adding local MAP profile
D/BluetoothMap( 3744): Create BluetoothMap proxy object
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3744): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3744): finishStartingService: stopping service
,D/BluetoothA2dp( 3744): Proxy object connected
,D/A2dpProfile( 3744): Bluetooth service connected
,D/BluetoothInputDevice( 3744): Proxy object connected
,D/HidProfile( 3744): Bluetooth service connected
,D/BluetoothPan( 3744): BluetoothPAN Proxy object connected
,D/PanProfile( 3744): Bluetooth service connected
D/BluetoothMap( 3744): Proxy object connected
D/MapProfile( 3744): Bluetooth service connected
,D/BluetoothMap( 3744): getConnectedDevices()
,D/BluetoothPbap( 3744): Proxy object connected
,D/PbapServerProfile( 3744): Bluetooth service connected
,V/MusicLeanback( 3110): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset( 3744): Proxy object connected
,D/HeadsetProfile( 3744): Bluetooth service connected
,D/SprintDMReceiver( 3611): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3611): simOperator:  IMSI: null
,D/SprintDMReceiver( 3611): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1823): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 24 Nov 2015 16:05:41 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448381141821], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448381141682]}
,D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Validated
,D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/SystemUpdateService( 1823): onCreate,
,D/SystemUpdateService( 1823): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,I/SystemUpdateService( 1823): active receiver: enabled
,I/SystemUpdateService( 1823): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1823): retry (wakeup: false) in 3599974 ms
,I/iu.Environment( 1823): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1823): num queued entries: 0
,I/iu.UploadsManager( 1823): num updated entries: 0,
,D/SystemUpdateService( 1823): onDestroy
,I/iu.SyncManager( 1823): NEXT; no task
,D/ChimeraCfgMgr( 1823): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1823): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 2831): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1823): [AccountUtils] Account not ready
W/Kids    ( 1823): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1823): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1823): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1823): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1823): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1823): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1823): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1823): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1823): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1823): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1823): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1823): 	at java.lang.Thread.run(Thread.java:818)
,I/art     (  820): Explicit concurrent mark sweep GC freed 31654(1483KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 1.902ms total 67.830ms
,D/GCM     ( 1548): Connected
,V/Herrevad( 1823): NQAS connected
,D/GCM     ( 1548): Message class com.google.f.a.a.p
,V/GoogleAuthProtoRequest( 3147): [318] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3147): [318] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3147): [318] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3147): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3147): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3147): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3147): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3147): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3147): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3147): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3147): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3147): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3147): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): BLE supported!!
I/jxcore-log( 3527): 
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=7.41 rxSuccessRate=8.48 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.10 rxSuccessRate=3.87 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2925): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2925): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2925): [1] 5.onFinished: Scheduling replication attempt 4.
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  264): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (220 us)
,D/SurfaceFlinger(  264): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  264): hwc_setPowerMode: Setting mode 0 on display: 0
I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  820): Display changed displayId=0
,I/qdhwcomposer(  264): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  264): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  820): Excessive delay in setPowerMode(): 276ms
,I/DreamManagerService(  820): Entering dreamland.
,I/PowerManagerService(  820): Dozing...
,I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  355): adev_set_parameters: enter: screen_state=on,
D/mot_vr_audio_hw(  355): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 12
,E/native  (  820): do suspend false
,I/Keyboard.Facilitator( 1212): onFinishInput()
,E/WifiStateMachine(  820): cancelDelayedScan -> 14
,E/native  (  820): do suspend true
,D/audio_hw_primary(  355): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  355): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1548): Explicit concurrent mark sweep GC freed 33683(1965KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 2.005ms total 66.031ms
,E/HttpOperation( 3236): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3236): 	at jdm.a(PG:82)
E/HttpOperation( 3236): 	at jcs.o(PG:406)
E/HttpOperation( 3236): 	at jcn.a(PG:1379)
E/HttpOperation( 3236): 	at jcs.i(PG:143)
E/HttpOperation( 3236): 	at blb.a(PG:3937)
E/HttpOperation( 3236): 	at czp.a(PG:18188)
E/HttpOperation( 3236): 	at czp.a(PG:9081)
E/HttpOperation( 3236): 	at czq.run(PG:1686)
E/HttpOperation( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3236): 	at jdj.a(PG:4091)
E/HttpOperation( 3236): 	at jdj.a(PG:1125)
E/HttpOperation( 3236): 	at jdm.a(PG:77)
E/HttpOperation( 3236): 	... 12 more
E/HttpOperation( 3236): Caused by: faj: BadAuthentication
E/HttpOperation( 3236): 	at fal.a(PG:38)
E/HttpOperation( 3236): 	at jdj.a(PG:4089)
E/HttpOperation( 3236): 	... 14 more
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3236): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3236): 	at jdm.a(PG:82)
E/HttpOperation( 3236): 	at jcs.o(PG:406)
E/HttpOperation( 3236): 	at jcn.a(PG:1379)
E/HttpOperation( 3236): 	at jcs.i(PG:143)
E/HttpOperation( 3236): 	at hec.a(PG:42)
E/HttpOperation( 3236): 	at hee.a(PG:102)
E/HttpOperation( 3236): 	at czr.a(PG:65)
E/HttpOperation( 3236): 	at kka.a(PG:108)
,E/HttpOperation( 3236): 	at czp.a(PG:19176)
E/HttpOperation( 3236): 	at czp.a(PG:9081)
E/HttpOperation( 3236): 	at czq.run(PG:1686)
E/HttpOperation( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3236): 	at jdj.a(PG:4091)
E/HttpOperation( 3236): 	at jdj.a(PG:1125)
E/HttpOperation( 3236): 	at jdm.a(PG:77)
E/HttpOperation( 3236): 	... 15 more
E/HttpOperation( 3236): Caused by: faj: BadAuthentication
E/HttpOperation( 3236): 	at fal.a(PG:38)
E/HttpOperation( 3236): 	at jdj.a(PG:4089)
E/HttpOperation( 3236): 	... 17 more
E/ExperimentLoader( 3236): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3236): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3236): 	at jdm.a(PG:82)
,E/ExperimentLoader( 3236): 	at jcs.o(PG:406)
E/ExperimentLoader( 3236): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3236): 	at jcs.i(PG:143)
E/ExperimentLoader( 3236): 	at hec.a(PG:42)
E/ExperimentLoader( 3236): 	at hee.a(PG:102)
E/ExperimentLoader( 3236): 	at czr.a(PG:65)
E/ExperimentLoader( 3236): 	at kka.a(PG:108)
E/ExperimentLoader( 3236): 	at czp.a(PG:19176)
E/ExperimentLoader( 3236): 	at czp.a(PG:9081)
E/ExperimentLoader( 3236): 	at czq.run(PG:1686)
E/ExperimentLoader( 3236): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3236): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3236): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3236): 	at jdm.a(PG:77)
E/ExperimentLoader( 3236): 	... 15 more
E/ExperimentLoader( 3236): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3236): 	at fal.a(PG:38)
E/ExperimentLoader( 3236): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3236): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 166717, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,D/AlarmManagerService(  820): Setting time of day to sec=1448381161
W/AlarmManagerService(  820): Unable to set rtc to 1448381161: Invalid argument
,I/ActivityManager(  820): Start proc 3865:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,E/SQLiteLog( 3865): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  820): Start proc 3885:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 3885): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3885): Created com.android.providers.calendar.CalendarAlarmManager@f9af7e9(com.android.providers.calendar.CalendarProvider2@3babc6e)
,I/ActivityManager(  820): Killing 3392:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/AnalyticsLogBase( 3865): PlayLogger.onLoggerConnected
,I/ActivityManager(  820): Start proc 3907:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,D/TimeService( 3907): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448381162451
D/        ( 3907): TimeServiceNative: User Time to be set is 1448381162452
D/QC-time-services( 3907): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3907): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3907): Lib:time_genoff_operation: pargs->ts_val = 1448381162452
D/QC-time-services( 3907): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  370): Daemon: Connection accepted:time_genoff
D/QC-time-services(  370): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448381162452
D/QC-time-services(  370): Daemon:genoff_opr: Base = 2, val = 1448381162452, operation = 0
D/QC-time-services(  370): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/11/70 12:19:4
D/QC-time-services(  370): Daemon:Value read from RTC seconds = 8684344000
D/QC-time-services(  370): Daemon:new time 1448381162452 
D/QC-time-services(  370): Daemon: delta 1439696818452 genoff 1439696818452 
D/QC-time-services(  370): Daemon:genoff_persistent_update: Writing genoff = 1439696818452 to memory
D/QC-time-services(  370): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  370): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  370): Updating the TOD offset,
D/QC-time-services(  370): Daemon:genoff_persistent_update: Writing genoff = 1439696818452 to memory
D/QC-time-services(  370): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  370): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  370): Daemon:Update to modem bit set
,E/QC-time-services( 3907): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  370): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  370): Daemon: Base = 2, Value being sent to MODEM = 1132416362452
,E/QC-time-services(  370): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  370): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40,
,I/ActivityManager(  820): Start proc 3926:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/ActivityManager(  820): Killing 3299:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/GAv4    ( 3926): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3926):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3926):   adb logcat -s GAv4
,W/GAv4    ( 3926): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3926): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3926): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  820): Killing 3465:com.google.android.apps.books/u0a34 (adj 15): empty #17
,I/CalendarProvider2( 3885): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3885): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/GAV2    ( 3865): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  820): Killing 3744:com.android.settings/1000 (adj 15): empty #17
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/art     (  820): Explicit concurrent mark sweep GC freed 31737(1570KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.485ms total 53.032ms
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2925): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2925): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2925): [1] 5.onFinished: Scheduling replication attempt 5.
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/ActivityManager(  820): Start proc 3964:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,V/KeepSync( 3435): Connecting to GoogleApiClient
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 3964): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/ClientConnectionOperation( 1823): Handling authorization failure,
E/ClientConnectionOperation( 1823): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1823): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1823): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1823): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1823): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1823): 	... 7 more
,I/BooksApp( 3964): Created application version: 3.6.8 (30608)
V/KeepSync( 3435): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
,I/BooksSync( 3964): Starting books sync for 61035162, extras: ade
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3435): IOException
E/KeepSync( 3435): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3435): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3435): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3435): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3435): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3435): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3435): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3435): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3435): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3435): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3435): 	... 10 more
W/KeepSync( 3435): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 170416, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/BooksConfig( 3964): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3964): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3964): Soft error
E/BooksSync( 3964): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3964): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3964): Sync error
,E/BooksSync( 3964): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3964): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3964): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 168538, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Killing 3765:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/GAV2    ( 3964): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2925): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2925): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2925): [1] 5.onFinished: Giving up after 6 failures.
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,D/Finsky  ( 2925): [269] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2925): [269] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1212): run()
I/Keyboard.Facilitator( 1212): flushDynamicLanguageModels()
,I/ConfigService( 1548): onCreate
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3236): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3236): 	at jdm.a(PG:82)
E/HttpOperation( 3236): 	at jcs.o(PG:406)
E/HttpOperation( 3236): 	at jcn.a(PG:1379)
E/HttpOperation( 3236): 	at jcs.i(PG:143)
E/HttpOperation( 3236): 	at blb.a(PG:3937)
E/HttpOperation( 3236): 	at czp.a(PG:18188)
E/HttpOperation( 3236): 	at czp.a(PG:9081)
E/HttpOperation( 3236): 	at czq.run(PG:1686)
E/HttpOperation( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3236): 	at jdj.a(PG:4091)
E/HttpOperation( 3236): 	at jdj.a(PG:1125)
E/HttpOperation( 3236): 	at jdm.a(PG:77)
E/HttpOperation( 3236): 	... 12 more
E/HttpOperation( 3236): Caused by: faj: BadAuthentication
E/HttpOperation( 3236): 	at fal.a(PG:38)
E/HttpOperation( 3236): 	at jdj.a(PG:4089)
E/HttpOperation( 3236): 	... 14 more
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3236): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3236): 	at jdm.a(PG:82)
E/HttpOperation( 3236): 	at jcs.o(PG:406)
E/HttpOperation( 3236): 	at jcn.a(PG:1379)
E/HttpOperation( 3236): 	at jcs.i(PG:143)
E/HttpOperation( 3236): 	at hec.a(PG:42)
E/HttpOperation( 3236): 	at hee.a(PG:102)
E/HttpOperation( 3236): 	at czr.a(PG:65)
E/HttpOperation( 3236): 	at kka.a(PG:108)
E/HttpOperation( 3236): 	at czp.a(PG:19176)
E/HttpOperation( 3236): 	at czp.a(PG:9081)
E/HttpOperation( 3236): 	at czq.run(PG:1686)
E/HttpOperation( 3236): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3236): 	at jdj.a(PG:4091)
E/HttpOperation( 3236): 	at jdj.a(PG:1125)
E/HttpOperation( 3236): 	at jdm.a(PG:77)
E/HttpOperation( 3236): 	... 15 more
E/HttpOperation( 3236): Caused by: faj: BadAuthentication
E/HttpOperation( 3236): 	at fal.a(PG:38)
E/HttpOperation( 3236): 	at jdj.a(PG:4089)
E/HttpOperation( 3236): 	... 17 more
E/ExperimentLoader( 3236): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3236): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3236): 	at jdm.a(PG:82)
E/ExperimentLoader( 3236): 	at jcs.o(PG:406)
E/ExperimentLoader( 3236): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3236): 	at jcs.i(PG:143)
E/ExperimentLoader( 3236): 	at hec.a(PG:42)
E/ExperimentLoader( 3236): 	at hee.a(PG:102)
E/ExperimentLoader( 3236): 	at czr.a(PG:65)
E/ExperimentLoader( 3236): 	at kka.a(PG:108)
E/ExperimentLoader( 3236): 	at czp.a(PG:19176)
E/ExperimentLoader( 3236): 	at czp.a(PG:9081)
E/ExperimentLoader( 3236): 	at czq.run(PG:1686)
E/ExperimentLoader( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3236): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3236): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3236): 	at jdm.a(PG:77)
E/ExperimentLoader( 3236): 	... 15 more
E/ExperimentLoader( 3236): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3236): 	at fal.a(PG:38)
E/ExperimentLoader( 3236): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3236): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 198554, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1548): onDestroy
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/art     (  820): Explicit concurrent mark sweep GC freed 27610(1165KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.646ms total 67.710ms
,I/BooksSync( 3964): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3435): Connecting to GoogleApiClient
,I/BooksConfig( 3964): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1548): Explicit concurrent mark sweep GC freed 38903(2MB) AllocSpace objects, 9(992KB) LOS objects, 37% free, 26MB/42MB, paused 1.338ms total 57.661ms
,E/ClientConnectionOperation( 1823): Handling authorization failure
E/ClientConnectionOperation( 1823): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1823): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1823): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1823): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1823): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1823): 	... 7 more
,V/KeepSync( 3435): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3964): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3964): Soft error
E/BooksSync( 3964): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3964): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3964): Sync error
E/BooksSync( 3964): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3964): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3964): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 228542, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3435): IOException
E/KeepSync( 3435): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3435): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3435): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3435): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3435): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3435): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3435): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3435): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3435): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3435): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3435): 	... 10 more
W/KeepSync( 3435): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 229926, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Coordinator is now connected to the server!
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3236): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3236): 	at jdm.a(PG:82)
E/HttpOperation( 3236): 	at jcs.o(PG:406)
E/HttpOperation( 3236): 	at jcn.a(PG:1379)
E/HttpOperation( 3236): 	at jcs.i(PG:143)
E/HttpOperation( 3236): 	at blb.a(PG:3937)
E/HttpOperation( 3236): 	at czp.a(PG:18188)
E/HttpOperation( 3236): 	at czp.a(PG:9081)
E/HttpOperation( 3236): 	at czq.run(PG:1686)
E/HttpOperation( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3236): 	at jdj.a(PG:4091)
E/HttpOperation( 3236): 	at jdj.a(PG:1125)
E/HttpOperation( 3236): 	at jdm.a(PG:77)
E/HttpOperation( 3236): 	... 12 more
E/HttpOperation( 3236): Caused by: faj: BadAuthentication
E/HttpOperation( 3236): 	at fal.a(PG:38)
E/HttpOperation( 3236): 	at jdj.a(PG:4089)
E/HttpOperation( 3236): 	... 14 more
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3236): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3236): 	at jdm.a(PG:82)
E/HttpOperation( 3236): 	at jcs.o(PG:406)
E/HttpOperation( 3236): 	at jcn.a(PG:1379)
E/HttpOperation( 3236): 	at jcs.i(PG:143)
E/HttpOperation( 3236): 	at hec.a(PG:42)
E/HttpOperation( 3236): 	at hee.a(PG:102)
E/HttpOperation( 3236): 	at czr.a(PG:65)
E/HttpOperation( 3236): 	at kka.a(PG:108)
E/HttpOperation( 3236): 	at czp.a(PG:19176)
E/HttpOperation( 3236): 	at czp.a(PG:9081)
E/HttpOperation( 3236): 	at czq.run(PG:1686)
E/HttpOperation( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3236): 	at jdj.a(PG:4091)
E/HttpOperation( 3236): 	at jdj.a(PG:1125)
E/HttpOperation( 3236): 	at jdm.a(PG:77)
E/HttpOperation( 3236): 	... 15 more
E/HttpOperation( 3236): Caused by: faj: BadAuthentication
E/HttpOperation( 3236): 	at fal.a(PG:38)
E/HttpOperation( 3236): 	at jdj.a(PG:4089)
E/HttpOperation( 3236): 	... 17 more
,E/ExperimentLoader( 3236): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3236): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3236): 	at jdm.a(PG:82)
E/ExperimentLoader( 3236): 	at jcs.o(PG:406)
E/ExperimentLoader( 3236): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3236): 	at jcs.i(PG:143)
E/ExperimentLoader( 3236): 	at hec.a(PG:42)
E/ExperimentLoader( 3236): 	at hee.a(PG:102)
E/ExperimentLoader( 3236): 	at czr.a(PG:65)
E/ExperimentLoader( 3236): 	at kka.a(PG:108)
E/ExperimentLoader( 3236): 	at czp.a(PG:19176)
E/ExperimentLoader( 3236): 	at czp.a(PG:9081)
E/ExperimentLoader( 3236): 	at czq.run(PG:1686)
E/ExperimentLoader( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3236): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3236): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3236): 	at jdm.a(PG:77)
E/ExperimentLoader( 3236): 	... 15 more
E/ExperimentLoader( 3236): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3236): 	at fal.a(PG:38)
E/ExperimentLoader( 3236): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3236): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 290006, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3147): [319] a.<init>: mAccountName set to: thalitester@gmail.com
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1081c989}
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3147): [319] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3147): [319] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3147): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3147): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3147): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3147): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3147): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3147): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3147): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3147): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3147): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3147): 	at com.a.a.k.run(SourceFile:110)
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1081c989}
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed,
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/BooksSync( 3964): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3964): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3435): Connecting to GoogleApiClient
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1823): Handling authorization failure
E/ClientConnectionOperation( 1823): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1823): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1823): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1823): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1823): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1823): 	... 7 more
,V/KeepSync( 3435): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3964): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3964): Soft error
E/BooksSync( 3964): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3964): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3964): Sync error
E/BooksSync( 3964): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3964): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3964): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 319352, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 29942(1303KB) AllocSpace objects, 9(332KB) LOS objects, 31% free, 34MB/50MB, paused 1.691ms total 62.564ms
,E/KeepSync( 3435): IOException
E/KeepSync( 3435): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3435): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3435): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3435): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3435): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3435): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3435): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3435): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3435): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3435): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3435): 	... 10 more
,W/KeepSync( 3435): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 322704, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1548): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1548): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1548): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1548): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1548): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1548): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1548): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2925): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2925): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2925): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2925): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2925): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2925): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2925): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2925): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/jxcore-log( 3527): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector command called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":19,"addressList":[{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"
,I/jxcore-log( 3527): Start now : testSendData.js
I/jxcore-log( 3527): 
I/jxcore-log( 3527): stop tests now !
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 19
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): check server
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): serverPort is 46019
I/jxcore-log( 3527): 
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3527): Stoping All
I/        ( 3527): Stopping services
I/        ( 3527): Stop Bluetooth
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/        ( 3527): Start-My BT: F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3527):  mInstanceString : {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5708","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3527): All stuff available and enabled
I/        ( 3527): Stoping All
I/        ( 3527): Stopping services
I/        ( 3527): Stop Bluetooth
I/        ( 3527): Starting All
I/        ( 3527): Stopping services
I/        ( 3527): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5708","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@3c8d49d4
,I/        ( 3527): Stopping services
I/        ( 3527): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5708","ra":"F8:CF:C5:D9:E5:61"}
I/        ( 3527): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5708","ra":"F8:CF:C5:D9:E5:61"}, length : 82,
I/        ( 3527): peerDiscoveryTimer timeout value:6646
,I/        ( 3527): Stop Bluetooth
,I/        ( 3527): StartBluetooth listener
I/        ( 3527): StartBluetooth listener
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/BTListenerThread( 3527): starting to listen
,I/BTListenerThread( 3527): waiting to accept incoming Connection
I/jxcore-log( 3527): StartBroadcasting started ok
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:24.045Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:24.045Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:24.045Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 3527): Connecting to null, at 7C:F9:0E:34:8A:A0,
,I/jxcore-log( 3527): 2015-11-24T16:10:24.053Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
I/jxcore-log( 3527): 
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/WB      ( 3527): We already were running, thus doing nothing
,I/        ( 3527): Added local service
I/        ( 3527): Cleared service requests
I/        ( 3527): Stopped peer discovery
I/        ( 3527): Started peer discovery
I/        ( 3527): Discovery state changed to Started.
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,D/btif_config( 3585): btif_get_device_type: Device [7c:f9:0e:34:8a:a0] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/ActivityManager(  820): Start proc 4079:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30fd4c2d:true
,I/ActivityManager(  820): Killing 3110:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
D/BluetoothAdapterProperties( 3585): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3527): Starting to Handshake
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTConnectToThread( 3527): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3527): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3527): HandshakeOk : samsung-SM-G900F_PT2346
,I/HS      ( 3527): Hand Shake finished outgoing for : samsung-SM-G900F_PT2346
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, samsung-SM-G900F_PT2346
,I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): mHTTPPort  set to : 59897
,I/BtConnectorHelper( 3527): Request socket is using : 59897
I/BtToRequestSocket( 3527): Now accepting connections
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :59897
,I/jxcore-log( 3527): 2015-11-24T16:10:28.892Z SendDataConnector.js: CLIENT connected to 59897, error: null
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:28.893Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 59897
,I/BtToRequestSocket( 3527): Set local streams
I/BtToRequestSocket( 3527): rin ended ---------------------------;
,I/jxcore-log( 3527): 2015-11-24T16:10:28.910Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 2 peers.
I/SS      ( 3527): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(2): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/jxcore-log( 3527): 2015-11-24T16:10:30.383Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:30.443Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3527): 
,I/        ( 3527): Started service discovery
,I/jxcore-log( 3527): 2015-11-24T16:10:30.550Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:30.883Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3527): 2015-11-24T16:10:31.091Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:31.296Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:31.606Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:31.816Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:31.985Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3527): ,
,I/jxcore-log( 3527): 2015-11-24T16:10:32.200Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:32.201Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:32.209Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:32.210Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
,I/BtConnectorHelper( 3527): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
,I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
,I/BtToRequestSocket( 3527): Close server socket
I/jxcore-log( 3527): 2015-11-24T16:10:32.218Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:32.220Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:32.220Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:32.220Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null,
,I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66
I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 8158 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc0eb4 rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc0eb4 rs_disc_pending=0,
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 6
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:10:33.805Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:33.806Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:33.808Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc0eb4 rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,D/btif_config( 3585): btif_get_device_type: Device [50:2e:6c:ac:21:50] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 3585): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3527): we got incoming connection
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread,
I/BTListenerThread( 3527): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc0eb4 rs_disc_pending=0,
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3236): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3236): 	at jdm.a(PG:82)
E/HttpOperation( 3236): 	at jcs.o(PG:406)
E/HttpOperation( 3236): 	at jcn.a(PG:1379)
E/HttpOperation( 3236): 	at jcs.i(PG:143)
E/HttpOperation( 3236): 	at blb.a(PG:3937)
E/HttpOperation( 3236): 	at czp.a(PG:18188)
E/HttpOperation( 3236): 	at czp.a(PG:9081)
E/HttpOperation( 3236): 	at czq.run(PG:1686)
E/HttpOperation( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3236): 	at jdj.a(PG:4091)
E/HttpOperation( 3236): 	at jdj.a(PG:1125)
E/HttpOperation( 3236): 	at jdm.a(PG:77)
E/HttpOperation( 3236): 	... 12 more
E/HttpOperation( 3236): Caused by: faj: BadAuthentication
E/HttpOperation( 3236): 	at fal.a(PG:38)
E/HttpOperation( 3236): 	at jdj.a(PG:4089)
E/HttpOperation( 3236): 	... 14 more
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3236): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 3236): java.io.IOException: Cannot obtain authentication token,
E/HttpOperation( 3236): 	at jdm.a(PG:82)
,E/HttpOperation( 3236): 	at jcs.o(PG:406)
E/HttpOperation( 3236): 	at jcn.a(PG:1379)
,E/HttpOperation( 3236): 	at jcs.i(PG:143)
E/HttpOperation( 3236): 	at hec.a(PG:42)
E/HttpOperation( 3236): ,	at hee.a(PG:102)
E/HttpOperation( 3236): 	at czr.a(PG:65)
E/HttpOperation( 3236): ,	at kka.a(PG:108)
E/HttpOperation( 3236): 	at czp.a(PG:19176)
E/HttpOperation( 3236): 	,at czp.a(PG:9081)
E/HttpOperation( 3236): 	at czq.run(PG:1686)
E/HttpOperation( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/HttpOperation( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3236): 	at jdj.a(PG:4091)
E/HttpOperation( 3236): 	at jdj.a(PG:1125),
E/HttpOperation( 3236): 	,at jdm.a(PG:77)
E/HttpOperation( 3236): 	... 15 more
E/HttpOperation( 3236): Caused by: faj: BadAuthentication
E/HttpOperation( 3236): 	at fal.a(PG:38)
E/HttpOperation( 3236): ,	at jdj.a(PG:4089)
E/HttpOperation( 3236): 	... 17 more
E/ExperimentLoader( 3236): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3236): java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3236): 	at jdm.a(PG:82)
E/ExperimentLoader( 3236): 	at jcs.o(PG:406)
E/ExperimentLoader( 3236): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3236): 	,at jcs.i(PG:143)
E/ExperimentLoader( 3236): 	at hec.a(PG:42)
E/ExperimentLoader( 3236): 	at hee.a(PG:102)
E/ExperimentLoader( 3236): 	at czr.a(PG:65),
E/ExperimentLoader( 3236): 	at kka.a(PG:108)
E/ExperimentLoader( 3236): 	at czp.a(PG:19176)
E/ExperimentLoader( 3236): 	at czp.a(PG:9081)
E/ExperimentLoader( 3236): 	at czq.run(PG:1686)
E/ExperimentLoader( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3236): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3236): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3236): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3236): 	,at jdm.a(PG:77)
E/ExperimentLoader( 3236): 	... 15 more
E/ExperimentLoader( 3236): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3236): ,	at fal.a(PG:38)
E/ExperimentLoader( 3236): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3236): 	... 17 more
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc1244 rs_disc_pending=0,
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3527): got MESSAGE_READ 80 bytes.,
I/BTListenerThread( 3527): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3527): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3527): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT4451
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3527): Starting the connected thread incoming : true, HTC-HTC One_M8_PT4451
,I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): Creating BTConnectedThread
,I/BtConnectorHelper( 3527): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3527): --DoOneRunRound started
,I/BtToRequestSocket( 3527): LocalHost address: localhost/127.0.0.1, port: 46019
,I/BtToRequestSocket( 3527): --DoOneRunRound ended
,I/jxcore-log( 3527): 2015-11-24T16:10:36.910Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3527): 
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 442778, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3527): 2015-11-24T16:10:37.332Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.357Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.409Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.479Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.510Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.526Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.565Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.569Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.578Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.595Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.626Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.633Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.638Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.668Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.680Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.715Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.739Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.748Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.756Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.796Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.817Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.840Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.880Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.890Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:10:37.925Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.964Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.978Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.987Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:37.994Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:38.025Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:38.029Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:38.038Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:38.075Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:38.081Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:38.115Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:38.137Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:38.145Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:38.176Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:38.216Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data,
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): invalid rfc slot id: 4,
,I/BtToSocketBase( 3527): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT4451,
,I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
,I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3527): 2015-11-24T16:10:38.297Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3527): 
,W/bt-rfcomm( 3585): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0,
W/bt-rfcomm( 3585): RFCOMM_DisconnectInd LCID:0x44
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc0eb4 rs_disc_pending=1,
,W/bt-btif ( 3585): bta_dm_check_av:0,
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14),
,I/jxcore-log( 3527): 2015-11-24T16:10:38.810Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:38.811Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@269f8055:true
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5-1,
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc1244 rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive,
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1473): Bluetooth Device Name: HTC One_M8
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/jxcore-log( 3527): 2015-11-24T16:10:43.816Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:43.817Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:43.818Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:43.818Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 7, f, 610c
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 8
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:10:44.080Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:44.080Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:44.081Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 3 peers.
I/SS      ( 3527): Peer(1): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 3527): Added service request,
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3527): Started service discovery
,I/jxcore-log( 3527): 2015-11-24T16:10:49.083Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:49.084Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3527): 2015-11-24T16:10:54.088Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:54.089Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:54.089Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:54.090Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp,
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 9
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:10:54.595Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:54.596Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:10:54.598Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9043"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9043"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9043, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9043, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:,
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT4262, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT4262, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B,
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3527): 2015-11-24T16:10:59.599Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:10:59.600Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT5340, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT5340, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6211","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6211","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT6211, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT6211, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3527): 2015-11-24T16:11:04.604Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:04.605Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:04.605Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:04.606Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp,
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 10
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:11:05.248Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:05.249Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:05.250Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/BooksSync( 3964): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3964): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1548): Explicit concurrent mark sweep GC freed 50060(2MB) AllocSpace objects, 6(661KB) LOS objects, 36% free, 27MB/43MB, paused 1.817ms total 45.923ms
,E/BooksAccountManager( 3964): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3964): Soft error
E/BooksSync( 3964): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3964): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3964): Sync error
E/BooksSync( 3964): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3964): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3964): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 471511, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:11:10.251Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:10.251Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3527): 2015-11-24T16:11:15.256Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:15.257Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:15.258Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:15.258Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null,
,I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66,
I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 11
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:11:15.829Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:15.830Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:15.834Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:15.837Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 3527): 
I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:15.844Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:15.845Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:15.845Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 34:FC:EF:11:AE:67
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 43611 ms, rnd: 5, ex: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63),
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1246): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3527): Found 6 peers.
,I/SS      ( 3527): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3527): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3527): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/        ( 3527): Started service discovery
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc140c rs_disc_pending=1,
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3585): process_service_search_attr_rsp,
,D/btif_config( 3585): btif_get_device_type: Device [34:fc:ef:11:ae:67] type 1,
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 3585): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1,
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3527): Starting to Handshake
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTConnectToThread( 3527): got MESSAGE_READ 76 bytes.
,I/BTConnectToThread( 3527): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3527): HandshakeOk : LGE-Nexus 5_PT474
I/HS      ( 3527): Hand Shake finished outgoing for : LGE-Nexus 5_PT474
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, LGE-Nexus 5_PT474
,I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): mHTTPPort  set to : 51662
I/BtConnectorHelper( 3527): Request socket is using : 51662
I/BtToRequestSocket( 3527): Now accepting connections
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc107c rs_disc_pending=0
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :51662
,I/jxcore-log( 3527): 2015-11-24T16:11:19.323Z SendDataConnector.js: CLIENT connected to 51662, error: null
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:19.324Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 51662
,I/BtToRequestSocket( 3527): Set local streams
,I/BtToRequestSocket( 3527): rin ended ---------------------------;
,I/jxcore-log( 3527): 2015-11-24T16:11:19.335Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3527): 2015-11-24T16:11:19.579Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:19.661Z SendDataConnector.js: CLIENT is data received : 20000,
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3527): 2015-11-24T16:11:19.728Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:19.818Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 3527): 2015-11-24T16:11:19.875Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3527): 2015-11-24T16:11:20.015Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:20.086Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:20.177Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:20.199Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:20.282Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:20.283Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:20.287Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:20.289Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
,I/BtConnectorHelper( 3527): Disconnect outgoing peer: 34:FC:EF:11:AE:67
,I/BtToSocketBase( 3527): Stop ReceivingThread
,I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
,I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
,I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/BtToRequestSocket( 3527): Close server socket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3527): 2015-11-24T16:11:20.297Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): ,
,I/jxcore-log( 3527): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:20.301Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:20.301Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:20.302Z SendDataConnector.js: do connect now
,I/jxcore-log( 3527): 
I/        ( 3527): Selected device address: 08:EC:A9:50:75:41, name: null
I/        ( 3527): Connecting to null, at 08:EC:A9:50:75:41
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 4439 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp,
,D/btif_config( 3585): btif_get_device_type: Device [08:ec:a9:50:75:41] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
D/BluetoothAdapterProperties( 3585): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3527): Starting to Handshake
,I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTConnectToThread( 3527): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3527): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3527): HandshakeOk : samsung-SM-A300FU_PT5340
I/HS      ( 3527): Hand Shake finished outgoing for : samsung-SM-A300FU_PT5340
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, samsung-SM-A300FU_PT5340
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): mHTTPPort  set to : 58731
,I/BtConnectorHelper( 3527): Request socket is using : 58731
I/BtToRequestSocket( 3527): Now accepting connections
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :58731
,I/jxcore-log( 3527): 2015-11-24T16:11:23.518Z SendDataConnector.js: CLIENT connected to 58731, error: null
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:23.521Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 58731
,I/BtToRequestSocket( 3527): Set local streams
,I/jxcore-log( 3527): 2015-11-24T16:11:23.534Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
I/BtToRequestSocket( 3527): rin ended ---------------------------;
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:408
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:22999
,I/jxcore-log( 3527): 2015-11-24T16:11:23.744Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:23.853Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Nexus 5
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3527): 2015-11-24T16:11:24.184Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:24.300Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 3527): 2015-11-24T16:11:24.483Z SendDataConnector.js: CLIENT is data received : 50000
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:24.580Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:24.585Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:24.715Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT4262, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT4262, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/jxcore-log( 3527): 2015-11-24T16:11:24.945Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3527): 2015-11-24T16:11:25.206Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:25.206Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:25.215Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:25.218Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
I/BtConnectorHelper( 3527): Disconnect outgoing peer: 08:EC:A9:50:75:41
I/BtToSocketBase( 3527): Stop ReceivingThread
,I/BtToSocketBase( 3527): Stop SendingThread
,I/BtToSocketBase( 3527): Close local in
,I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt in
,I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/BtToRequestSocket( 3527): Close server socket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3527): 2015-11-24T16:11:25.226Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:25.229Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:25.229Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:25.230Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
I/        ( 3527): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3527): Starting to connect,
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at F8:95:C7:87:85:54
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 4906 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc179c rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT5340, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT5340, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6211","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6211","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT6211, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT6211, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,D/btif_config( 3585): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1,
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3585): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3585): Failed to remove device: F8:95:C7:87:85:54,
I/BluetoothBondStateMachine( 3585): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State,
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc179c rs_disc_pending=0
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/        ( 3527): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT474, peerAddress: 34:FC:EF:11:AE:67
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT474, WifiDirectName: , WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3585): onReceive,
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: A3-1,
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3527): Starting to Handshake
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTConnectToThread( 3527): got MESSAGE_READ 77 bytes.,
I/BTConnectToThread( 3527): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6211","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3527): HandshakeOk : LGE-LG-D722_PT6211
I/HS      ( 3527): Hand Shake finished outgoing for : LGE-LG-D722_PT6211
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, LGE-LG-D722_PT6211
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): mHTTPPort  set to : 51629,
I/BtConnectorHelper( 3527): Request socket is using : 51629
I/BtToRequestSocket( 3527): Now accepting connections
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :51629
,I/jxcore-log( 3527): 2015-11-24T16:11:29.600Z SendDataConnector.js: CLIENT connected to 51629, error: null
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:29.600Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 51629
,I/BtToRequestSocket( 3527): Set local streams
I/jxcore-log( 3527): 2015-11-24T16:11:29.608Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): rin ended ---------------------------;
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3527): 2015-11-24T16:11:30.075Z SendDataConnector.js: CLIENT is data received : 10000,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:30.162Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:30.241Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:30.348Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:30.376Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:30.463Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:30.524Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:30.618Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:30.623Z SendDataConnector.js: CLIENT is data received : 90000,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:30.651Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 3527): ,
I/jxcore-log( 3527): 2015-11-24T16:11:30.652Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:30.659Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3527): ,
,I/jxcore-log( 3527): 2015-11-24T16:11:30.663Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
,I/BtConnectorHelper( 3527): Disconnect outgoing peer: F8:95:C7:87:85:54
I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
,I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3527): Close bt out
,I/BtToSocketBase( 3527): Close bt socket
I/BtToRequestSocket( 3527): Close server socket
,I/jxcore-log( 3527): 2015-11-24T16:11:30.673Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:30.677Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:30.678Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:30.679Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): ,
,I/        ( 3527): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3527): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 5424 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc179c rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/        ( 3527): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6450"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6450"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT6450, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT6450, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3585): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 15
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:11:36.299Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:36.300Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:36.301Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,V/KeepSync( 3435): Connecting to GoogleApiClient
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1823): Handling authorization failure
,E/ClientConnectionOperation( 1823): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1823): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1823): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1823): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1823): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1823): 	... 7 more
,V/KeepSync( 3435): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3435): IOException
E/KeepSync( 3435): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3435): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3435): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3435): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3435): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3435): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3435): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3435): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3435): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3435): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3435): 	... 10 more
W/KeepSync( 3435): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 478291, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:11:41.303Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:11:41.304Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3527): 
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3527): 2015-11-24T16:11:46.308Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:46.309Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:46.312Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:11:46.314Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 44:80:EB:7B:5A:05
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 8 peers.
,I/SS      ( 3527): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3527): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3527): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,D/btif_config( 3585): btif_get_device_type: Device [44:80:eb:7b:5a:05] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3585): Failed to remove device: 44:80:EB:7B:5A:05
I/BluetoothBondStateMachine( 3585): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3527): Starting to Handshake
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread,
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started,
,I/BTConnectToThread( 3527): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 3527): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT1910","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3527): HandshakeOk : motorola-XT1072_PT1910
I/HS      ( 3527): Hand Shake finished outgoing for : motorola-XT1072_PT1910
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, motorola-XT1072_PT1910
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): mHTTPPort  set to : 45702
,I/BtConnectorHelper( 3527): Request socket is using : 45702
I/BtToRequestSocket( 3527): Now accepting connections
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :45702
,I/jxcore-log( 3527): 2015-11-24T16:12:05.964Z SendDataConnector.js: CLIENT connected to 45702, error: null
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:05.965Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 45702
,I/BtToRequestSocket( 3527): Set local streams
I/jxcore-log( 3527): 2015-11-24T16:12:05.974Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
I/BtToRequestSocket( 3527): rin ended ---------------------------;
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:408
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:22999
,I/jxcore-log( 3527): 2015-11-24T16:12:06.203Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3527): ,
,I/jxcore-log( 3527): 2015-11-24T16:12:06.230Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3527): 2015-11-24T16:12:06.283Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:06.389Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3199
,I/jxcore-log( 3527): 2015-11-24T16:12:06.445Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:06.518Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:06.571Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:06.771Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:06.997Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:07.122Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:07.123Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:07.126Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:07.128Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
I/BtConnectorHelper( 3527): Disconnect outgoing peer: 44:80:EB:7B:5A:05
,I/BtToSocketBase( 3527): Stop ReceivingThread
,I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
,I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
,I/BtToSocketBase( 3527): Close bt socket
I/BtToRequestSocket( 3527): Close server socket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3527): 2015-11-24T16:12:07.137Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:07.139Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:07.140Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:07.141Z SendDataConnector.js: do connect now
,I/jxcore-log( 3527): 
I/        ( 3527): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at E0:DB:10:14:E2:C0
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 36445 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: XT1072
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 3585): check_cod: remote_cod = 0x5a0
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c,
W/bt-btif ( 3585): invalid rfc slot id: 17
E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btm  ( 3585): Device not in IRK list
,E/bt-btif ( 3585): Do not find the bg connection mask for the remote device
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BluetoothBondStateMachine( 3585): No record of the device:null
I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 9 Address: E0:DB:10:14:E2:C0 newState: 0
E/BluetoothBondStateMachine( 3585): In stable state, received invalid newState: 10
,I/jxcore-log( 3527): 2015-11-24T16:12:16.484Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3527): 
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
I/jxcore-log( 3527): 2015-11-24T16:12:16.485Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:16.486Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:21.488Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3527): ,
I/jxcore-log( 3527): 2015-11-24T16:12:21.489Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:26.492Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:26.493Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:26.494Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:26.495Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 3585): check_cod: remote_cod = 0x5a0,
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c,
W/bt-btif ( 3585): invalid rfc slot id: 18
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/BluetoothBondStateMachine( 3585): No record of the device:null
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 9 Address: E0:DB:10:14:E2:C0 newState: 0
E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3585): Device not in IRK list,
E/BluetoothBondStateMachine( 3585): In stable state, received invalid newState: 10
E/bt-btif ( 3585): Do not find the bg connection mask for the remote device
I/jxcore-log( 3527): 2015-11-24T16:12:32.520Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
,I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:32.521Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3527): 
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:12:32.522Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,V/GoogleAuthProtoRequest( 3147): [320] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 43306(1936KB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 1.746ms total 93.787ms
,W/ExperimentUpdateService( 3147): [320] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3147): [320] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3147): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3147): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3147): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3147): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3147): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3147): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3147): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3147): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3147): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3147): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3527): 2015-11-24T16:12:37.529Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:37.530Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3527): 
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/jxcore-log( 3527): 2015-11-24T16:12:42.534Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:42.535Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:42.536Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:42.536Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: E0:DB:10:14:E2:C0, name: null,
,I/        ( 3527): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,D/btif_config( 3585): btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3585): Failed to remove device: E0:DB:10:14:E2:C0
I/BluetoothBondStateMachine( 3585): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3527): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6450"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6450"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT6450, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT6450, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3527): Starting to Handshake
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread,
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTConnectToThread( 3527): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3527): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3527): HandshakeOk : samsung-SM-N910C_PT4262
I/HS      ( 3527): Hand Shake finished outgoing for : samsung-SM-N910C_PT4262
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, samsung-SM-N910C_PT4262
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): mHTTPPort  set to : 46231,
I/BtConnectorHelper( 3527): Request socket is using : 46231
I/BtToRequestSocket( 3527): Now accepting connections
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :46231,
I/jxcore-log( 3527): 2015-11-24T16:12:46.320Z SendDataConnector.js: CLIENT connected to 46231, error: null
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:46.320Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 46231
,I/jxcore-log( 3527): 2015-11-24T16:12:46.328Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
I/BtToRequestSocket( 3527): Set local streams
I/BtToRequestSocket( 3527): rin ended ---------------------------;
,I/jxcore-log( 3527): 2015-11-24T16:12:46.657Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:46.947Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:47.076Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:47.128Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:47.143Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:47.201Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): ,
,I/jxcore-log( 3527): 2015-11-24T16:12:47.216Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:47.285Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:47.634Z SendDataConnector.js: CLIENT is data received : 90000,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:48.057Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:48.058Z SendDataConnector.js: got all data for this round
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:48.065Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:48.068Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3527): 
,I/BtConnectorHelper( 3527): Disconnect outgoing peer: E0:DB:10:14:E2:C0
,I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
,I/BtToSocketBase( 3527): Close local in
,I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close bt in
,I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/BtToRequestSocket( 3527): Close server socket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3527): 2015-11-24T16:12:48.077Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:48.080Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:48.081Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:48.081Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
I/        ( 3527): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3527): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 40919 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc1b2c rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1246): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3527): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT1910","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT1910","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT1910, peerAddress: 44:80:EB:7B:5A:05,
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT1910, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT4262, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT4262, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 3585): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 20
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:12:53.987Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:53.987Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:12:53.988Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT5340, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT5340, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3527): 2015-11-24T16:12:58.989Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:12:58.990Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery,
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,D/btif_config( 3585): btif_get_device_type: Device [00:f4:6f:30:e0:6c] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
D/BluetoothAdapterProperties( 3585): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3527): we got incoming connection,
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTListenerThread( 3527): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTListenerThread( 3527): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3527): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6450"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3527): MESSAGE_WRITE 82 bytes.
I/HS      ( 3527): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT6450
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : true, samsung-SM-G800F_PT6450
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BTConnectedThread
I/BtConnectorHelper( 3527): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3527): --DoOneRunRound started
,I/BtToRequestSocket( 3527): LocalHost address: localhost/127.0.0.1, port: 46019
,I/BtToRequestSocket( 3527): --DoOneRunRound ended
,I/jxcore-log( 3527): 2015-11-24T16:13:03.478Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:03.942Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:03.946Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:03.960Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:03.963Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:03.995Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:03.996Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:13:03.996Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:13:03.997Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: B4:CE:F6:AB:A4:6A, name: null,
I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3527): 2015-11-24T16:13:04.011Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3527): 
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3527): 2015-11-24T16:13:04.023Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:04.038Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:04.075Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc1ebc rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3527): 2015-11-24T16:13:04.352Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:04.362Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:04.371Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:04.376Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:04.415Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:04.461Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:04.543Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:04.609Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:04.677Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:04.744Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:04.812Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:04.879Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:04.947Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:05.106Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:05.317Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:05.465Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:05.760Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:05.897Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:05.965Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:06.032Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:06.190Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:06.258Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:06.324Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:06.391Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:06.460Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:06.684Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:06.752Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:06.820Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:06.947Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:06.986Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:07.002Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:07.007Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:07.014Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:07.046Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:07.090Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:07.093Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:07.227Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3527): 2015-11-24T16:13:07.304Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:07.335Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:07.462Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:07.535Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:07.538Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): invalid rfc slot id: 7
,I/BtToSocketBase( 3527): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT6450
I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT6450
I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
,I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/BtToSocketBase( 3527): Close bt socket
,I/jxcore-log( 3527): 2015-11-24T16:13:07.674Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc1ebc rs_disc_pending=0
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3585): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 3585): RFCOMM_DisconnectInd LCID:0x4a
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,W/bt-sdp  ( 3585): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d,
E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 3585): invalid rfc slot id: 22
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:13:09.436Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:09.437Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:13:09.437Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0,
,I/SS      ( 3527): Found 7 peers.
,I/SS      ( 3527): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3527): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3527): Peer(4): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3527): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3527): Peer(6): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/        ( 3527): Started service discovery
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3527): 2015-11-24T16:13:14.439Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:14.440Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/jxcore-log( 3527): 2015-11-24T16:13:19.443Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:19.444Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:19.445Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:13:19.445Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at B4:CE:F6:AB:A4:6A
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,W/bt-sdp  ( 3585): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e,
E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 23
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:13:24.606Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:24.606Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:24.609Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3527): 2015-11-24T16:13:29.610Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:29.611Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 7 peers.
,I/SS      ( 3527): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3527): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3527): Peer(4): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3527): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(6): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3527): Peer(7): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3527): Started service discovery
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3527): 2015-11-24T16:13:34.614Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:34.615Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:13:34.616Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:13:34.616Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3527): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3585): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 24
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:13:39.775Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:39.776Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:39.777Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/jxcore-log( 3527): 2015-11-24T16:13:44.779Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:44.781Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3527): Found 7 peers.
,I/SS      ( 3527): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3527): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3527): Peer(4): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3527): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(6): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3527): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3527): 2015-11-24T16:13:49.786Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:49.787Z SendDataConnector.js: Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
,I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:13:49.788Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:13:49.788Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3527): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,W/bt-sdp  ( 3585): SDP - Rcvd conn cnf with error: 0xd  CID 0x40
E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 25
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:13:50.617Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:13:50.617Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:13:50.621Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:50.624Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- gotta redo : B4:CE:F6:AB:A4:6A, try count now: 1
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:13:50.629Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:13:50.630Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:13:50.630Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 08:EC:A9:50:76:27
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 62537 ms, rnd: 5, ex: Connection to B4:CE:F6:AB:A4:6A failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3585): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 26
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:13:55.774Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:13:55.775Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:13:55.776Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:14:00.778Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:14:00.779Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3527): 2015-11-24T16:14:05.783Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:14:05.784Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:05.784Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:14:05.785Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3527): Connecting to null, at 08:EC:A9:50:76:27,
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 9 peers.
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3527): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3527): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3527): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,D/btif_config( 3585): btif_get_device_type: Device [08:ec:a9:50:76:27] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,W/bt-rfcomm( 3585): PORT_StartCnf failed result:5,
,W/bt-btif ( 3585): invalid rfc slot id: 27,
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/jxcore-log( 3527): 2015-11-24T16:14:17.423Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:17.424Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:17.424Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 9 Address: 08:EC:A9:50:76:27 newState: 0
D/BluetoothAdapterProperties( 3585): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State,
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 3585): Device not in IRK list
E/bt-btif ( 3585): Do not find the bg connection mask for the remote device
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6211","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6211","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT6211, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT6211, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT5340, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT5340, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/jxcore-log( 3527): 2015-11-24T16:14:22.425Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:14:22.426Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests
I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:14:27.430Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:27.431Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
,I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:14:27.431Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:27.432Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,D/btif_config( 3585): btif_get_device_type: Device [08:ec:a9:50:76:27] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 3585): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3527): Starting to Handshake
,I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTConnectToThread( 3527): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 3527): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3527): HandshakeOk : samsung-SM-A300FU_PT2521
I/HS      ( 3527): Hand Shake finished outgoing for : samsung-SM-A300FU_PT2521
,I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, samsung-SM-A300FU_PT2521
,I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3527): mHTTPPort  set to : 48392
,I/BtConnectorHelper( 3527): Request socket is using : 48392
I/BtToRequestSocket( 3527): Now accepting connections
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :48392
,I/jxcore-log( 3527): 2015-11-24T16:14:29.288Z SendDataConnector.js: CLIENT connected to 48392, error: null
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:14:29.288Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 48392
I/BtToRequestSocket( 3527): Set local streams
I/BtToRequestSocket( 3527): rin ended ---------------------------;
,I/jxcore-log( 3527): 2015-11-24T16:14:29.296Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3527): 2015-11-24T16:14:29.446Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:29.465Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3527): 2015-11-24T16:14:29.500Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6169
,I/jxcore-log( 3527): 2015-11-24T16:14:29.554Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:29.558Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:29.624Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:29.670Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:29.683Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:29.764Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:29.810Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:29.811Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:29.818Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:14:29.819Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
I/BtConnectorHelper( 3527): Disconnect outgoing peer: 08:EC:A9:50:76:27
,I/BtToSocketBase( 3527): Stop ReceivingThread
,I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
,I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close bt in
,I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/BtToRequestSocket( 3527): Close server socket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3527): 2015-11-24T16:14:29.827Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): ,
,W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND,
I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:14:29.832Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:14:29.833Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:14:29.834Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
I/        ( 3527): Selected device address: F4:F1:E1:5C:3B:E2, name: null
I/BTConnectToThread( 3527): Starting to connect,
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at F4:F1:E1:5C:3B:E2,
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 39182 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2084 rs_disc_pending=0
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 9 peers.
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3527): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3527): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT5340, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT5340, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: A3-1
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3236): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3236): 	at jdm.a(PG:82)
E/HttpOperation( 3236): 	at jcs.o(PG:406)
E/HttpOperation( 3236): 	at jcn.a(PG:1379)
E/HttpOperation( 3236): 	at jcs.i(PG:143)
E/HttpOperation( 3236): ,	at blb.a(PG:3937)
E/HttpOperation( 3236): 	at czp.a(PG:18188)
E/HttpOperation( 3236): 	at czp.a(PG:9081)
E/HttpOperation( 3236): 	at czq.run(PG:1686)
E/HttpOperation( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3236): 	at jdj.a(PG:4091)
E/HttpOperation( 3236): 	at jdj.a(PG:1125)
E/HttpOperation( 3236): 	at jdm.a(PG:77)
,E/HttpOperation( 3236): 	... 12 more
E/HttpOperation( 3236): Caused by: faj: BadAuthentication
E/HttpOperation( 3236): 	at fal.a(PG:38)
E/HttpOperation( 3236): 	at jdj.a(PG:4089)
E/HttpOperation( 3236): 	... 14 more
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc15d4 rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3236): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3236): 	at jdm.a(PG:82)
E/HttpOperation( 3236): 	at jcs.o(PG:406)
E/HttpOperation( 3236): 	at jcn.a(PG:1379)
E/HttpOperation( 3236): 	at jcs.i(PG:143)
E/HttpOperation( 3236): 	at hec.a(PG:42)
E/HttpOperation( 3236): 	at hee.a(PG:102)
E/HttpOperation( 3236): 	at czr.a(PG:65)
E/HttpOperation( 3236): 	at kka.a(PG:108)
E/HttpOperation( 3236): 	at czp.a(PG:19176)
E/HttpOperation( 3236): 	at czp.a(PG:9081)
E/HttpOperation( 3236): 	at czq.run(PG:1686)
E/HttpOperation( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3236): 	at jdj.a(PG:4091)
E/HttpOperation( 3236): 	at jdj.a(PG:1125)
E/HttpOperation( 3236): 	at jdm.a(PG:77)
E/HttpOperation( 3236): 	... 15 more
E/HttpOperation( 3236): Caused by: faj: BadAuthentication
E/HttpOperation( 3236): 	at fal.a(PG:38)
E/HttpOperation( 3236): 	at jdj.a(PG:4089)
E/HttpOperation( 3236): 	... 17 more
,E/ExperimentLoader( 3236): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3236): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3236): ,	at jdm.a(PG:82)
E/ExperimentLoader( 3236): 	at jcs.o(PG:406)
E/ExperimentLoader( 3236): 	at jcn.a(PG:1379)
,E/ExperimentLoader( 3236): 	at jcs.i(PG:143)
E/ExperimentLoader( 3236): 	at hec.a(PG:42)
E/ExperimentLoader( 3236): 	at hee.a(PG:102)
E/ExperimentLoader( 3236): 	at czr.a(PG:65)
E/ExperimentLoader( 3236): 	at kka.a(PG:108)
E/ExperimentLoader( 3236): ,	at czp.a(PG:19176)
E/ExperimentLoader( 3236): 	at czp.a(PG:9081)
E/ExperimentLoader( 3236): 	at czq.run(PG:1686)
E/ExperimentLoader( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/ExperimentLoader( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3236): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3236): 	,at jdj.a(PG:1125)
E/ExperimentLoader( 3236): 	at jdm.a(PG:77)
E/ExperimentLoader( 3236): 	... 15 more
E/ExperimentLoader( 3236): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3236): 	at fal.a(PG:38)
E/ExperimentLoader( 3236): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3236): 	... 17 more
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc1cf4 rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 693632, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/btif_config( 3585): btif_get_device_type: Device [b4:ce:f6:ab:a4:6a] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1,
E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 3585): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3527): we got incoming connection
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTListenerThread( 3527): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTListenerThread( 3527): got MESSAGE_READ 84 bytes.
,I/BTListenerThread( 3527): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3527): MESSAGE_WRITE 82 bytes.
I/HS      ( 3527): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT6452
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT6452
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BTConnectedThread
I/BtConnectorHelper( 3527): Server socket is using : 0, and is now connected.
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/BtToRequestSocket( 3527): --DoOneRunRound started
,I/BtToRequestSocket( 3527): LocalHost address: localhost/127.0.0.1, port: 46019
,I/BtToRequestSocket( 3527): --DoOneRunRound ended
I/jxcore-log( 3527): 2015-11-24T16:14:49.038Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:49.461Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:49.525Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:49.590Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:49.599Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:49.627Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:49.657Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:49.741Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:49.775Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:49.804Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:49.885Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3527): 
,W/bt-btm  ( 3585): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc15d4 rs_disc_pending=2
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3527): 2015-11-24T16:14:50.208Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data,
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3585): onReceive,
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: A3-1
,I/jxcore-log( 3527): 2015-11-24T16:14:50.438Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc1cf4 rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3527): 2015-11-24T16:14:50.475Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:50.518Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:50.536Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:50.553Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:50.567Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:50.606Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:50.989Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.007Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.018Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.037Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.075Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.150Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3527): 2015-11-24T16:14:51.174Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.208Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.280Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.341Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.361Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.505Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.517Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.530Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.565Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.588Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.619Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.636Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.644Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.675Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.688Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.698Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.760Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.777Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.786Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.796Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:51.808Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3527): ,
,I/jxcore-log( 3527): 2015-11-24T16:14:51.846Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): invalid rfc slot id: 21
,I/BtToSocketBase( 3527): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT6452
I/BtToSocketBase( 3527): Stop ReceivingThread
,I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,W/bt-rfcomm( 3585): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 3585): RFCOMM_DisconnectInd LCID:0x4b
,I/jxcore-log( 3527): 2015-11-24T16:14:51.923Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc1cf4 rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2414 rs_disc_pending=0
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: HTC Desire 820
,D/btif_config( 3585): btif_get_device_type: Device [e0:db:10:1f:c9:5e] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
D/BluetoothAdapterProperties( 3585): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3527): we got incoming connection
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTListenerThread( 3527): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTListenerThread( 3527): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3527): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3527): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3527): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT1336
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3527): Starting the connected thread incoming : true, samsung-SM-N9005_PT1336
,I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BTConnectedThread
I/BtConnectorHelper( 3527): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3527): --DoOneRunRound started
,I/BtToRequestSocket( 3527): LocalHost address: localhost/127.0.0.1, port: 46019
,I/BtToRequestSocket( 3527): --DoOneRunRound ended
,I/jxcore-log( 3527): 2015-11-24T16:14:56.627Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6211","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6211","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT6211, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT6211, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3527): 2015-11-24T16:14:57.138Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:57.197Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:57.268Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:57.273Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:57.332Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:57.338Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:57.375Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:57.396Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:57.413Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3527): 2015-11-24T16:14:57.703Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/jxcore-log( 3527): 2015-11-24T16:14:58.020Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:58.072Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:58.138Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:58.196Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:58.198Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:58.267Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:58.333Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:58.395Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:58.403Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:58.472Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:58.550Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:58.585Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:58.707Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.038Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3527): 2015-11-24T16:14:59.283Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.335Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.387Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.392Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.447Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.455Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.510Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.562Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.684Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.748Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.806Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.809Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.887Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.942Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.986Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:14:59.990Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:00.273Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:00.289Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:00.344Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:00.357Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:00.388Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data,
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3527): 2015-11-24T16:15:00.440Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:00.446Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:00.484Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:00.531Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:00.633Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:00.675Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): invalid rfc slot id: 30
,I/BtToSocketBase( 3527): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT1336
,I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
,I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
,I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3527): 2015-11-24T16:15:00.844Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3527): 
,W/bt-rfcomm( 3585): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 3585): RFCOMM_DisconnectInd LCID:0x4d
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3585): SDP - Rcvd conn cnf with error: 0x8  CID 0x46
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 29
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:15:03.797Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:03.799Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:15:03.800Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Note3-1
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:15:08.800Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:08.801Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3527): 
,D/btif_config( 3585): btif_get_device_type: Device [58:3f:54:73:64:c0] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
D/BluetoothAdapterProperties( 3585): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:255,
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3527): we got incoming connection
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3527): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTListenerThread( 3527): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3527): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3527): MESSAGE_WRITE 82 bytes.
I/HS      ( 3527): Incoming connection Hand Shake finished for : LGE-LG-D855_PT6302
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3527): Starting the connected thread incoming : true, LGE-LG-D855_PT6302,
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BTConnectedThread
I/BtConnectorHelper( 3527): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3527): --DoOneRunRound started
,I/BtToRequestSocket( 3527): LocalHost address: localhost/127.0.0.1, port: 46019,
I/BtToRequestSocket( 3527): --DoOneRunRound ended
,I/jxcore-log( 3527): 2015-11-24T16:15:09.011Z SendDataTCPServer.js: TCP/IP server connected,
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 9 peers.
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3527): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(5): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(8): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3527): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/jxcore-log( 3527): 2015-11-24T16:15:09.430Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.438Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.555Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3527): ,
,I/jxcore-log( 3527): 2015-11-24T16:15:09.564Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.566Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.576Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.586Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.625Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.664Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.695Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.699Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.708Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.714Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.755Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.760Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.763Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.796Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.813Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.821Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.828Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.865Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.872Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.882Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.893Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.904Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.936Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.962Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.970Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.978Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:09.991Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:10.025Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:10.034Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:10.065Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:10.069Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:10.111Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:10.145Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:10.185Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:10.225Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3585): invalid rfc slot id: 31
,I/BtToSocketBase( 3527): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT6302
I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT6302
I/BtToSocketBase( 3527): Close LocalOutputStream
,I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt in
,I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
,I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/jxcore-log( 3527): 2015-11-24T16:15:10.345Z SendDataTCPServer.js: TCP/IP server is ended
,I/jxcore-log( 3527): 
W/bt-rfcomm( 3585): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 3585): RFCOMM_DisconnectInd LCID:0x4f,
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3527): 2015-11-24T16:15:13.805Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:15:13.806Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:15:13.806Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:13.807Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at F4:F1:E1:5C:3B:E2
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BooksSync( 3964): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3964): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3964): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3964): Soft error
E/BooksSync( 3964): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3964): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3964): Sync error
E/BooksSync( 3964): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3964): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3964): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 721357, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/SS      ( 3527): Found 7 peers.
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3527): Peer(4): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3527): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(7): A3-1 0a:ec:a9:50:75:42
D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,W/bt-btm  ( 3585): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc25dc rs_disc_pending=2
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: G3-1
,I/        ( 3527): Started service discovery
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,W/bt-rfcomm( 3585): PORT_StartCnf failed result:5
W/bt-btif ( 3585): invalid rfc slot id: 33
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/jxcore-log( 3527): 2015-11-24T16:15:24.082Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:15:24.082Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3527): ,
I/jxcore-log( 3527): 2015-11-24T16:15:24.084Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c,
,I/BluetoothBondStateMachine( 3585): No record of the device:null
I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 9 Address: F4:F1:E1:5C:3B:E2 newState: 0
,E/BluetoothBondStateMachine( 3585): In stable state, received invalid newState: 10
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3585): Device not in IRK list
,E/bt-btif ( 3585): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3527): 2015-11-24T16:15:29.085Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:15:29.086Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:15:34.090Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:15:34.091Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:15:34.091Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:15:34.092Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at F4:F1:E1:5C:3B:E2
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 7 peers.
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3527): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3527): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,D/btif_config( 3585): btif_get_device_type: Device [f4:f1:e1:5c:3b:e2] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0,
D/BluetoothAdapterProperties( 3585): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1,
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3527): Starting to Handshake
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTConnectToThread( 3527): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 3527): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3527): HandshakeOk : motorola-XT1039_PT1668
I/HS      ( 3527): Hand Shake finished outgoing for : motorola-XT1039_PT1668
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, motorola-XT1039_PT1668
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3527): mHTTPPort  set to : 42905
I/BtConnectorHelper( 3527): Request socket is using : 42905
,I/BtToRequestSocket( 3527): Now accepting connections
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :42905
,I/jxcore-log( 3527): 2015-11-24T16:15:36.144Z SendDataConnector.js: CLIENT connected to 42905, error: null
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:15:36.145Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 42905
,I/BtToRequestSocket( 3527): Set local streams
I/BtToRequestSocket( 3527): rin ended ---------------------------;
,I/jxcore-log( 3527): 2015-11-24T16:15:36.153Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23853
,I/jxcore-log( 3527): 2015-11-24T16:15:36.355Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18903
,I/jxcore-log( 3527): 2015-11-24T16:15:36.441Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:10983
,I/jxcore-log( 3527): 2015-11-24T16:15:36.484Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:36.490Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4053
,I/jxcore-log( 3527): 2015-11-24T16:15:36.558Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:36.575Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:36.624Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:36.629Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:36.669Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:36.743Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:36.744Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:15:36.748Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): ,
I/jxcore-log( 3527): 2015-11-24T16:15:36.749Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
I/BtConnectorHelper( 3527): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
,I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
,I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
,I/BtToSocketBase( 3527): Close bt socket
I/BtToRequestSocket( 3527): Close server socket
I/jxcore-log( 3527): 2015-11-24T16:15:36.755Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3527): 
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:15:36.762Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:15:36.763Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:36.764Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 58:3F:54:73:64:C0, name: G3-1,
I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/        ( 3527): Connecting to G3-1, at 58:3F:54:73:64:C0
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 66911 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc224c rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: G3-1,
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc25dc rs_disc_pending=1,
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc224c rs_disc_pending=0
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3527): Starting to Handshake
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTConnectToThread( 3527): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3527): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3527): HandshakeOk : LGE-LG-D855_PT6302
,I/HS      ( 3527): Hand Shake finished outgoing for : LGE-LG-D855_PT6302
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, LGE-LG-D855_PT6302
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3527): mHTTPPort  set to : 47500
,I/BtConnectorHelper( 3527): Request socket is using : 47500
,I/BtToRequestSocket( 3527): Now accepting connections
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :47500
,I/jxcore-log( 3527): 2015-11-24T16:15:40.118Z SendDataConnector.js: CLIENT connected to 47500, error: null
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:40.119Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 47500
,I/jxcore-log( 3527): 2015-11-24T16:15:40.126Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
I/BtToRequestSocket( 3527): Set local streams
I/BtToRequestSocket( 3527): rin ended ---------------------------;
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc224c rs_disc_pending=1,
E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3585): bta_dm_check_av:0,
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
D/BluetoothMapService( 3585): onReceive
D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: XT1039
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,W/bt-btif ( 3585): dm_pm_timer expires
W/bt-btif ( 3585): dm_pm_timer expires 0
W/bt-btif ( 3585): proc dm_pm_timer expires
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc25dc rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3527): 2015-11-24T16:15:50.159Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:15:50.160Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:50.162Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:50.163Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:15:50.165Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3527): 
,I/BtToSocketBase( 3527): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3527): Disconnect outgoing peer: LGE-LG-D855_PT6302
I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
,I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/BtToRequestSocket( 3527): Close server socket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btif ( 3585): unknown send() error, sent:-1, p_buf->len:3,  errno:32
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 7 peers.
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3527): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3527): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending,
I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,I/jxcore-log( 3527): 2015-11-24T16:15:55.164Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:15:55.165Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: G3-1,
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [08:ec:a9:50:75:41]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: A3-1
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3527): we got incoming connection
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTListenerThread( 3527): waiting to accept incoming Connection,
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTListenerThread( 3527): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 3527): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3527): MESSAGE_WRITE 82 bytes.
I/HS      ( 3527): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT5340
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : true, samsung-SM-A300FU_PT5340
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BTConnectedThread
,I/BtConnectorHelper( 3527): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3527): --DoOneRunRound started
,I/jxcore-log( 3527): 2015-11-24T16:15:59.960Z SendDataTCPServer.js: TCP/IP server connected,
I/jxcore-log( 3527): 
I/BtToRequestSocket( 3527): LocalHost address: localhost/127.0.0.1, port: 46019
,I/BtToRequestSocket( 3527): --DoOneRunRound ended,
,I/jxcore-log( 3527): 2015-11-24T16:16:00.170Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:00.170Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:16:00.171Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:16:00.171Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 58:3F:54:73:64:C0, name: G3-1
,I/        ( 3527): Connecting to G3-1, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc15d4 rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3527): 2015-11-24T16:16:01.199Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:01.373Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:01.572Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3527): Cleared service requests,
,I/        ( 3527): Started peer discovery
,W/bt-sdp  ( 3585): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 37
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:16:06.099Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.100Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.100Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.120Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.127Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.135Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.145Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.246Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.348Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.358Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 8 peers.
I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3527): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3527): Peer(5): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3527): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3527): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3527): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/jxcore-log( 3527): 2015-11-24T16:16:06.565Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.666Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.706Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.779Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.786Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.889Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.956Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.966Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.971Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.985Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:06.994Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.060Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.073Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.079Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.090Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.095Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.099Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.160Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.168Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.173Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.181Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.272Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.281Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.288Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.294Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.302Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/jxcore-log( 3527): 2015-11-24T16:16:07.377Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.384Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.390Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.460Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.496Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.560Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.570Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.577Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.585Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.590Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.664Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.671Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:07.708Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:16:07.712Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): invalid rfc slot id: 32
,I/BtToSocketBase( 3527): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT5340
I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
,I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close bt in
,I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close bt out
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT5340
,I/BtToSocketBase( 3527): Close bt socket
I/BtToSocketBase( 3527): Close bt in
,I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/jxcore-log( 3527): 2015-11-24T16:16:07.814Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3527): 
,I/        ( 3527): Started service discovery
,W/bt-rfcomm( 3585): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,W/bt-rfcomm( 3585): RFCOMM_DisconnectInd LCID:0x4c
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3527): 2015-11-24T16:16:11.103Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:11.104Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: A3-1
,I/jxcore-log( 3527): 2015-11-24T16:16:16.108Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:16.109Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:16:16.109Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:16:16.110Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 58:3F:54:73:64:C0, name: G3-1,
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to G3-1, at 58:3F:54:73:64:C0
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,V/KeepSync( 3435): Connecting to GoogleApiClient
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1823): Handling authorization failure
E/ClientConnectionOperation( 1823): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1823): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1823): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1823): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1823): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1823): 	... 7 more
,V/KeepSync( 3435): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3435): IOException
E/KeepSync( 3435): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3435): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3435): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3435): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3435): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3435): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3435): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3435): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3435): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3435): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3435): 	... 10 more
,W/KeepSync( 3435): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 764672, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: G3-1
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/SS      ( 3527): Found 5 peers.
I/SS      ( 3527): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3527): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(5): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3527): Starting to Handshake
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTConnectToThread( 3527): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3527): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3527): HandshakeOk : LGE-LG-D855_PT6302
I/HS      ( 3527): Hand Shake finished outgoing for : LGE-LG-D855_PT6302
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, LGE-LG-D855_PT6302
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): mHTTPPort  set to : 54365
,I/BtConnectorHelper( 3527): Request socket is using : 54365
I/BtToRequestSocket( 3527): Now accepting connections
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :54365
,I/jxcore-log( 3527): 2015-11-24T16:16:19.811Z SendDataConnector.js: CLIENT connected to 54365, error: null
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:19.811Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 54365
,I/BtToRequestSocket( 3527): Set local streams
I/BtToRequestSocket( 3527): rin ended ---------------------------;
,I/jxcore-log( 3527): 2015-11-24T16:16:19.820Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
,I/        ( 3527): Started service discovery
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3527): 2015-11-24T16:16:21.486Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3527): 2015-11-24T16:16:22.862Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3527): 2015-11-24T16:16:25.737Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3527): 2015-11-24T16:16:27.561Z SendDataConnector.js: CLIENT is data received : 40000,
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 3527): 2015-11-24T16:16:27.699Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:27.833Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:27.984Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:28.046Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:28.164Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:28.231Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:28.232Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:28.241Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:16:28.242Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
,I/BtConnectorHelper( 3527): Disconnect outgoing peer: 58:3F:54:73:64:C0
,I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
,I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
,I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/BtToRequestSocket( 3527): Close server socket
,I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3527): 2015-11-24T16:16:28.249Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:16:28.254Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3527): ,
I/jxcore-log( 3527): 2015-11-24T16:16:28.254Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:16:28.254Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
I/        ( 3527): Selected device address: F8:95:C7:87:3C:51, name: null
I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at F8:95:C7:87:3C:51
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 51474 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT5340, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT5340, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc25dc rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc25dc rs_disc_pending=0
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc25dc rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc27a4 rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: G3-1
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/btif_config( 3585): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3585): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3527): Starting to Handshake
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTConnectToThread( 3527): got MESSAGE_READ 77 bytes.,
I/BTConnectToThread( 3527): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3527): HandshakeOk : LGE-LG-H815_PT7587
,I/HS      ( 3527): Hand Shake finished outgoing for : LGE-LG-H815_PT7587
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, LGE-LG-H815_PT7587
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): mHTTPPort  set to : 40645
,I/BtConnectorHelper( 3527): Request socket is using : 40645
I/BtToRequestSocket( 3527): Now accepting connections
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :40645
,I/jxcore-log( 3527): 2015-11-24T16:16:36.705Z SendDataConnector.js: CLIENT connected to 40645, error: null
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:36.706Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 40645
,I/BtToRequestSocket( 3527): Set local streams
I/jxcore-log( 3527): 2015-11-24T16:16:36.716Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): rin ended ---------------------------;
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:675
,I/jxcore-log( 3527): 2015-11-24T16:16:36.876Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:36.992Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:37.036Z SendDataConnector.js: CLIENT is data received : 30000
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:37.121Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc27a4 rs_disc_pending=0,
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3527): 2015-11-24T16:16:37.397Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:37.438Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:37.497Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:37.516Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:37.555Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:37.595Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:37.596Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:37.603Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): ,
I/jxcore-log( 3527): 2015-11-24T16:16:37.605Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
I/BtConnectorHelper( 3527): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
,I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/BtToRequestSocket( 3527): Close server socket
,I/jxcore-log( 3527): 2015-11-24T16:16:37.615Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:16:37.617Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:37.618Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:16:37.618Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 58:2A:F7:ED:96:BE, name: null
,W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 58:2A:F7:ED:96:BE
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 9343 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc27a4 rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc296c rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,D/btif_config( 3585): btif_get_device_type: Device [58:2a:f7:ed:96:be] type 1,
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1,
E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0,
D/BluetoothAdapterProperties( 3585): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc296c rs_disc_pending=0
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive,
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: G4-1
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3527): Starting to Handshake
,I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTConnectToThread( 3527): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 3527): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT5583","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3527): HandshakeOk : HUAWEI-ALE-L21_PT5583
I/HS      ( 3527): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT5583
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT5583
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): mHTTPPort  set to : 55025
,I/BtConnectorHelper( 3527): Request socket is using : 55025
I/BtToRequestSocket( 3527): Now accepting connections
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :55025
,I/jxcore-log( 3527): 2015-11-24T16:16:41.960Z SendDataConnector.js: CLIENT connected to 55025, error: null
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:41.962Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 55025
,I/BtToRequestSocket( 3527): Set local streams
,I/jxcore-log( 3527): 2015-11-24T16:16:41.974Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
I/BtToRequestSocket( 3527): rin ended ---------------------------;
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24843
,I/jxcore-log( 3527): 2015-11-24T16:16:42.457Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:42.618Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13953
,I/jxcore-log( 3527): 2015-11-24T16:16:42.862Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3527): 
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/jxcore-log( 3527): 2015-11-24T16:16:43.061Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4053
,I/jxcore-log( 3527): 2015-11-24T16:16:43.733Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3527): 2015-11-24T16:16:43.934Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:44.088Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:44.374Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:44.669Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3527): ,
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 6 peers.
I/SS      ( 3527): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3527): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Started service discovery
,W/bt-btif ( 3585): dm_pm_timer expires
,W/bt-btif ( 3585): dm_pm_timer expires 0
W/bt-btif ( 3585): proc dm_pm_timer expires
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
W/bt-btif ( 3585): invalid rfc slot id: 40
I/BtToSocketBase( 3527): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3527): Disconnect outgoing peer: HUAWEI-ALE-L21_PT5583
,I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
,I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
,I/BtToSocketBase( 3527): Close bt socket
I/BtToRequestSocket( 3527): Close server socket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: ALE-L21
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3527): 2015-11-24T16:16:54.670Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:54.671Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:16:54.672Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:16:54.672Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:54.674Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:59.673Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:16:59.674Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:16:59.675Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT5340, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT5340, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3527): 2015-11-24T16:17:04.679Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:04.680Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:04.680Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:04.681Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: ALE-L21
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,D/btif_config( 3585): btif_get_device_type: Device [58:2a:f7:ed:96:be] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 3585): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3527): Starting to Handshake
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTConnectToThread( 3527): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 3527): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT5583","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3527): HandshakeOk : HUAWEI-ALE-L21_PT5583
,I/HS      ( 3527): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT5583
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT5583
,I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3527): mHTTPPort  set to : 58638
I/BtConnectorHelper( 3527): Request socket is using : 58638
,I/BtToRequestSocket( 3527): Now accepting connections
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :58638,
I/jxcore-log( 3527): 2015-11-24T16:17:05.703Z SendDataConnector.js: CLIENT connected to 58638, error: null
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:05.704Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 58638,
I/BtToRequestSocket( 3527): Set local streams
I/jxcore-log( 3527): 2015-11-24T16:17:05.715Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3527): 
I/BtToRequestSocket( 3527): rin ended ---------------------------;
,I/jxcore-log( 3527): 2015-11-24T16:17:05.826Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:05.827Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:05.830Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:05.833Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
,I/BtConnectorHelper( 3527): Disconnect outgoing peer: 58:2A:F7:ED:96:BE
I/BtToSocketBase( 3527): Stop ReceivingThread
,I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
,I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
,I/BtToRequestSocket( 3527): Close server socket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3527): 2015-11-24T16:17:05.844Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:05.847Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:05.848Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:05.848Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
I/        ( 3527): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/BTConnectToThread( 3527): Starting to connect,
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 34:FC:EF:9D:93:0B
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 28210 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2b34 rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2b34 rs_disc_pending=0
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,D/btif_config( 3585): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
D/BluetoothAdapterProperties( 3585): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3527): Starting to Handshake
,I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2b34 rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3527): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3527): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3527): HandshakeOk : LGE-LG-D802_PT2047
I/HS      ( 3527): Hand Shake finished outgoing for : LGE-LG-D802_PT2047
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, LGE-LG-D802_PT2047
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3527): mHTTPPort  set to : 37648
,I/BtConnectorHelper( 3527): Request socket is using : 37648
I/BtToRequestSocket( 3527): Now accepting connections
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3527): Found 8 peers.
,I/SS      ( 3527): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3527): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3527): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3527): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3527): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :37648
,I/jxcore-log( 3527): 2015-11-24T16:17:09.167Z SendDataConnector.js: CLIENT connected to 37648, error: null
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:09.167Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 37648,
I/BtToRequestSocket( 3527): Set local streams
I/BtToRequestSocket( 3527): rin ended ---------------------------;
,I/jxcore-log( 3527): 2015-11-24T16:17:09.176Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:09.577Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3527): ,
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive,
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2b34 rs_disc_pending=0
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
I/BluetoothClassifier( 1473): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 3527): 2015-11-24T16:17:10.049Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,I/jxcore-log( 3527): 2015-11-24T16:17:10.224Z SendDataConnector.js: CLIENT is data received : 30000,
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3527): 2015-11-24T16:17:10.327Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:10.718Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3527): 2015-11-24T16:17:10.884Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:10.989Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:11.234Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:11.375Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3527): 2015-11-24T16:17:11.621Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:11.622Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:11.630Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:11.632Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
,I/BtConnectorHelper( 3527): Disconnect outgoing peer: 34:FC:EF:9D:93:0B
,I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
,I/BtToSocketBase( 3527): Close local in
,I/BtToSocketBase( 3527): Close LocalOutputStream
,I/BtToSocketBase( 3527): Close localHostSocket
,I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
,I/BtToSocketBase( 3527): Close bt socket
I/BtToRequestSocket( 3527): Close server socket
,I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3527): 2015-11-24T16:17:11.643Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
,I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3527): 
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/jxcore-log( 3527): 2015-11-24T16:17:11.645Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:11.645Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:11.646Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): ,
I/        ( 3527): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
I/        ( 3527): Connecting to Note3-1, at E0:DB:10:1F:C9:5E,
I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 5776 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2b34 rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3585): info:x10,
,D/        ( 3585): remote version info [e0:db:10:1f:c9:5e]: 6, 10f, 608
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3527): Starting to Handshake
,I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 3527): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3527): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3527): HandshakeOk : samsung-SM-N9005_PT1336
I/HS      ( 3527): Hand Shake finished outgoing for : samsung-SM-N9005_PT1336
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, samsung-SM-N9005_PT1336
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): mHTTPPort  set to : 45999
,I/BtConnectorHelper( 3527): Request socket is using : 45999
I/BtToRequestSocket( 3527): Now accepting connections
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT5340, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT5340, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :45999
,I/jxcore-log( 3527): 2015-11-24T16:17:13.451Z SendDataConnector.js: CLIENT connected to 45999, error: null
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:13.452Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 45999
I/BtToRequestSocket( 3527): Set local streams
I/BtToRequestSocket( 3527): rin ended ---------------------------;
I/jxcore-log( 3527): 2015-11-24T16:17:13.462Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:13.766Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:13.826Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:13.830Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:13.868Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:13.906Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:13.911Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:13.966Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:13.973Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:14.029Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:14.030Z SendDataConnector.js: got all data for this round,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:14.033Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:14.035Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
I/BtConnectorHelper( 3527): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 3527): Stop ReceivingThread,
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
,I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt in
,I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close bt out
,I/BtToSocketBase( 3527): Close bt socket
I/BtToRequestSocket( 3527): Close server socket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/jxcore-log( 3527): 2015-11-24T16:17:14.044Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- round done--------
,I/jxcore-log( 3527): 
I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:14.048Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:14.051Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:14.054Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 2386 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND,
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2414 rs_disc_pending=0
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Thali Test's G2
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT4262, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT4262, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [50:2e:6c:ac:21:50]: 6, f, 4106
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: HTC One_M8
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc1244 rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3527): Starting to Handshake
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTConnectToThread( 3527): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 3527): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3527): HandshakeOk : HTC-HTC One_M8_PT4451
I/HS      ( 3527): Hand Shake finished outgoing for : HTC-HTC One_M8_PT4451
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, HTC-HTC One_M8_PT4451
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): mHTTPPort  set to : 49355
,I/BtConnectorHelper( 3527): Request socket is using : 49355
I/BtToRequestSocket( 3527): Now accepting connections
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :49355,
I/jxcore-log( 3527): 2015-11-24T16:17:20.929Z SendDataConnector.js: CLIENT connected to 49355, error: null
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:20.930Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 49355,
I/BtToRequestSocket( 3527): Set local streams
,I/BtToRequestSocket( 3527): rin ended ---------------------------;,
I/jxcore-log( 3527): 2015-11-24T16:17:20.939Z SendDataConnector.js: CLIENT now sending 100000 bytes of data,
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24707,
,I/jxcore-log( 3527): 2015-11-24T16:17:21.093Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:21.098Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16787
,I/jxcore-log( 3527): 2015-11-24T16:17:21.237Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3527): 2015-11-24T16:17:21.435Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:21.493Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:21.679Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:21.731Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:21.779Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:21.787Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:21.836Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:21.837Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:21.842Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:21.844Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3527): 
,I/BtConnectorHelper( 3527): Disconnect outgoing peer: 50:2E:6C:AC:21:50
,I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
,I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
,I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close bt in
,I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
,I/BtToRequestSocket( 3527): Close server socket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3527): 2015-11-24T16:17:21.854Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
I/jxcore-log( 3527): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:21.858Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:21.859Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:21.860Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 7788 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 45
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:17:24.686Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:24.687Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:24.688Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests
I/        ( 3527): Started peer discovery
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive,
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: HTC One_M8
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 7 peers.
,I/SS      ( 3527): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3527): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3527): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3527): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Started service discovery,
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3527): 2015-11-24T16:17:29.693Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:29.694Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:34.697Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:34.698Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:34.698Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:34.699Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     (  820): Explicit concurrent mark sweep GC freed 62111(2MB) AllocSpace objects, 9(521KB) LOS objects, 31% free, 34MB/50MB, paused 1.444ms total 91.810ms
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 3585): invalid rfc slot id: 46
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:17:35.961Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:35.962Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:35.963Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [58:2a:f7:ed:96:be]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc296c rs_disc_pending=0
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT4262, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT4262, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc296c rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3527): we got incoming connection
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3527): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc296c rs_disc_pending=0
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3527): 2015-11-24T16:17:40.966Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:40.966Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/BTListenerThread( 3527): got MESSAGE_READ 80 bytes.
,I/BTListenerThread( 3527): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT5583","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3527): MESSAGE_WRITE 82 bytes.
I/HS      ( 3527): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT5583
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT5583
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BTConnectedThread
,I/BtConnectorHelper( 3527): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3527): --DoOneRunRound started
,I/BtToRequestSocket( 3527): LocalHost address: localhost/127.0.0.1, port: 46019
,I/BtToRequestSocket( 3527): --DoOneRunRound ended
,I/jxcore-log( 3527): 2015-11-24T16:17:41.266Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3527): 2015-11-24T16:17:41.658Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.662Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.704Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.708Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.744Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.781Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.821Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.825Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.832Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.846Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.886Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.892Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.899Z SendDataTCPServer.js: TCP/IP server has received 32496 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.925Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.965Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:41.993Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.015Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.055Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.075Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.083Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.115Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.122Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.125Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 3527): ,
,I/jxcore-log( 3527): 2015-11-24T16:17:42.132Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.166Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.169Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.185Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.227Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.231Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.238Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.276Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.316Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.322Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:42.355Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): invalid rfc slot id: 36
,I/BtToSocketBase( 3527): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT5583
I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT5583
I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt socket
I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/jxcore-log( 3527): 2015-11-24T16:17:42.432Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3527): 
,W/bt-rfcomm( 3585): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0,
,W/bt-rfcomm( 3585): RFCOMM_DisconnectInd LCID:0x4e
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/jxcore-log( 3527): 2015-11-24T16:17:45.970Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:45.971Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:45.971Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:17:45.972Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null,
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 7 peers.
,I/SS      ( 3527): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(2): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3527): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3527): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/        ( 3527): Started service discovery
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [f4:f1:e1:5c:3b:e2]: 7, f, 6109
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: XT1039
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL,
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc224c rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 48
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:17:55.388Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:55.391Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:55.391Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3527): we got incoming connection
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTListenerThread( 3527): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc224c rs_disc_pending=0
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3527): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3527): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3527): MESSAGE_WRITE 82 bytes.
I/HS      ( 3527): Incoming connection Hand Shake finished for : motorola-XT1039_PT1668
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3527): Starting the connected thread incoming : true, motorola-XT1039_PT1668
,I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BTConnectedThread
I/BtConnectorHelper( 3527): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3527): --DoOneRunRound started
,I/BtToRequestSocket( 3527): LocalHost address: localhost/127.0.0.1, port: 46019
,I/BtToRequestSocket( 3527): --DoOneRunRound ended
,I/jxcore-log( 3527): 2015-11-24T16:17:56.278Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:56.728Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:56.807Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:56.817Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:56.860Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:56.904Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:56.911Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:56.916Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:56.963Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:56.968Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:56.976Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:56.982Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.043Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.075Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.142Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.194Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.200Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.207Z SendDataTCPServer.js: TCP/IP server has received 32496 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.245Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.267Z SendDataTCPServer.js: TCP/IP server has received 36456 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.308Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.314Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.322Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.356Z SendDataTCPServer.js: TCP/IP server has received 46356 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.377Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.442Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.450Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.486Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.508Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 3527): ,
,I/jxcore-log( 3527): 2015-11-24T16:17:57.515Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.521Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.556Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.577Z SendDataTCPServer.js: TCP/IP server has received 66156 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.629Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.636Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.647Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.758Z SendDataTCPServer.js: TCP/IP server has received 74076 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.766Z SendDataTCPServer.js: TCP/IP server has received 76056 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.773Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.817Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.823Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.855Z SendDataTCPServer.js: TCP/IP server has received 83976 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.884Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.891Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.931Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.937Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.942Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:57.984Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:58.039Z SendDataTCPServer.js: TCP/IP server has received 97836 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:58.079Z SendDataTCPServer.js: TCP/IP server has received 99816 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:17:58.498Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): invalid rfc slot id: 47
I/BtToSocketBase( 3527): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT1668
I/BtToSocketBase( 3527): Stop ReceivingThread
,I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
,I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close localHostSocket
I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3527): Close bt in
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT1668
I/BtToSocketBase( 3527): Close bt out
,I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt socket
I/BtToSocketBase( 3527): Close bt out
,I/BtToSocketBase( 3527): Close bt socket
I/jxcore-log( 3527): 2015-11-24T16:17:58.746Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT4262, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT4262, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc224c rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3585): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 3585): RFCOMM_DisconnectInd LCID:0x43
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Thali Test (Galaxy A3),
,I/jxcore-log( 3527): 2015-11-24T16:18:00.393Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:00.395Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc224c rs_disc_pending=0
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3527): we got incoming connection
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTListenerThread( 3527): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc224c rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3527): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 3527): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3527): MESSAGE_WRITE 82 bytes.
I/HS      ( 3527): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT2521
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : true, samsung-SM-A300FU_PT2521
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BTConnectedThread
,I/BtConnectorHelper( 3527): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3527): --DoOneRunRound started
,I/BtToRequestSocket( 3527): LocalHost address: localhost/127.0.0.1, port: 46019
,I/BtToRequestSocket( 3527): --DoOneRunRound ended
,I/jxcore-log( 3527): 2015-11-24T16:18:01.741Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc224c rs_disc_pending=0
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3527): 2015-11-24T16:18:02.320Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:02.324Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:02.486Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:02.493Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:02.600Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:02.608Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:02.650Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:02.685Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:02.760Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3527): ,
,I/jxcore-log( 3527): 2015-11-24T16:18:02.764Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:02.820Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:02.857Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:02.913Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:02.946Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.030Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.086Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3527): 2015-11-24T16:18:03.192Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.303Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.349Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.354Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.364Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.466Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive,
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1473): Bluetooth Device Name: XT1039
,I/jxcore-log( 3527): 2015-11-24T16:18:03.539Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.627Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.634Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.644Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.729Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.765Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.812Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.818Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.869Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:03.904Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.045Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.085Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.147Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.153Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.161Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.251Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.307Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.317Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.410Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.584Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.615Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.644Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.676Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.740Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:04.747Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:05.002Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:05.271Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:05.278Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:05.281Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:05.399Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:05.399Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:05.400Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:05.400Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): ,
,I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2084 rs_disc_pending=0
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3585): invalid rfc slot id: 49
I/BtToSocketBase( 3527): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT2521
I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
,I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
,I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3527): 2015-11-24T16:18:06.054Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: ALE-L21
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 3585): invalid rfc slot id: 51
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:18:07.181Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:07.181Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:07.182Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2084 rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL,
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3527): 2015-11-24T16:18:12.184Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:12.185Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 8 peers.
,I/SS      ( 3527): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3527): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(4): A3-1 0a:ec:a9:50:75:42,
I/SS      ( 3527): Peer(5): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3527): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3527): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(8): Android_8ae2 52:55:27:f0:fd:0b,
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/        ( 3527): Started service discovery
,I/jxcore-log( 3527): 2015-11-24T16:18:17.189Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:17.189Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:17.190Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:17.190Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT4262, peerAddress: E0:DB:10:14:E2:C0
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT4262, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 52
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:18:19.417Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:19.418Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:19.422Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:19.429Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:19.432Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
,I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:19.433Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:19.433Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 57560 ms, rnd: 5, ex: Connection to 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 53
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:18:20.936Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:20.936Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:20.937Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/jxcore-log( 3527): 2015-11-24T16:18:25.938Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:25.938Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:18:30.942Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:30.943Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:30.944Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:30.944Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 7 peers.
E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,I/SS      ( 3527): Peer(1): G3-1 02:9a:02:7b:60:ac
W/bt-btif ( 3585): invalid rfc slot id: 54
I/SS      ( 3527): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/SS      ( 3527): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3527): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:18:32.308Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:32.308Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:32.309Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
D/WifiP2pManager( 3527): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/        ( 3527): Started service discovery
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3527): 2015-11-24T16:18:37.310Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:37.311Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT5340, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT5340, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/jxcore-log( 3527): 2015-11-24T16:18:42.315Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:42.315Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:42.316Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:42.316Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/BTConnectToThread( 3527): Starting to connect,
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1,
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 55
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:18:43.331Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:43.332Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:43.334Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive,
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3527): 2015-11-24T16:18:48.335Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:48.336Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0,
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3527): 2015-11-24T16:18:53.340Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:53.340Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:53.341Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:53.341Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 56
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:18:54.659Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:54.659Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:18:54.660Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:18:59.661Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:18:59.662Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3527): Found 11 peers.
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3527): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3527): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3527): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0,
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0,
I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3527): 2015-11-24T16:19:04.665Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:04.666Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:04.666Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:04.667Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1,
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 57
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:19:05.428Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:05.430Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:05.436Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:05.438Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:05.442Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
,I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:05.443Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:05.444Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 7C:F9:0E:37:96:AB, name: null,
I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 7C:F9:0E:37:96:AB
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 45998 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 58
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:19:10.089Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:10.090Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:10.090Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests,
I/        ( 3527): Started peer discovery
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:19:15.092Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:15.092Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 11 peers.
I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3527): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3527): Peer(8): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3527): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3527): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/        ( 3527): Started service discovery
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: G4-1
,D/btif_config( 3585): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 3585): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3527): 2015-11-24T16:19:20.096Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:20.097Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:20.098Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:20.098Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 7C:F9:0E:37:96:AB, name: null
I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc27a4 rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3527): we got incoming connection
,I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTListenerThread( 3527): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTListenerThread( 3527): got MESSAGE_READ 77 bytes.,
I/BTListenerThread( 3527): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3527): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3527): Incoming connection Hand Shake finished for : LGE-LG-H815_PT7587
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : true, LGE-LG-H815_PT7587
,I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BTConnectedThread
I/BtConnectorHelper( 3527): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3527): --DoOneRunRound started
,I/BtToRequestSocket( 3527): LocalHost address: localhost/127.0.0.1, port: 46019
,I/jxcore-log( 3527): 2015-11-24T16:19:21.040Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3527): 
I/BtToRequestSocket( 3527): --DoOneRunRound ended
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3527): 2015-11-24T16:19:21.502Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:22.055Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:22.536Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:22.744Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:22.880Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [34:fc:ef:9d:93:0b]: 6, f, 410d
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Thali Test's G2
,I/jxcore-log( 3527): 2015-11-24T16:19:23.161Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:23.237Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:23.372Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:23.438Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:23.577Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:23.716Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:23.788Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:23.858Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:23.925Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:23.993Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:24.061Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3527): 
,D/btif_config( 3585): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/jxcore-log( 3527): 2015-11-24T16:19:24.130Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3527): 
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,E/bt-btif ( 3585): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3585): Entering PendingCommandState State
,I/jxcore-log( 3527): 2015-11-24T16:19:24.198Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:24.272Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3527): ,
,I/jxcore-log( 3527): 2015-11-24T16:19:24.336Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:24.401Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3527): 
,I/BluetoothBondStateMachine( 3585): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0,
D/BluetoothAdapterProperties( 3585): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3585): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3585): StableState(): Entering Off State
,I/jxcore-log( 3527): 2015-11-24T16:19:24.539Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:24.827Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:24.897Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:25.125Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:25.231Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:25.574Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:25.744Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:25.747Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3527): 
,W/bt-sdp  ( 3585): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 59
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:19:25.789Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:25.789Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
,I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:25.790Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:25.814Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3527): we got incoming connection
,I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3527): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/jxcore-log( 3527): 2015-11-24T16:19:26.047Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.064Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.095Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.099Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.106Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.110Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.146Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.149Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.152Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.246Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.254Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.286Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.302Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.307Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.350Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.354Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.385Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.391Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.395Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3527): 
,I/BTListenerThread( 3527): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3527): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3527): MESSAGE_WRITE 82 bytes.
I/HS      ( 3527): Incoming connection Hand Shake finished for : LGE-LG-D802_PT2047
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3527): Starting the connected thread incoming : true, LGE-LG-D802_PT2047
,I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BTConnectedThread
,I/BtConnectorHelper( 3527): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3527): --DoOneRunRound started
,I/BtToRequestSocket( 3527): LocalHost address: localhost/127.0.0.1, port: 46019
,I/BtToRequestSocket( 3527): --DoOneRunRound ended
,I/jxcore-log( 3527): 2015-11-24T16:19:26.425Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): invalid rfc slot id: 50
,I/BtToSocketBase( 3527): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT7587
I/BtToSocketBase( 3527): Stop ReceivingThread
,I/BtToSocketBase( 3527): Stop SendingThread
,I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close bt out
I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close bt socket
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT7587
,I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/jxcore-log( 3527): 2015-11-24T16:19:26.448Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc27a4 rs_disc_pending=0
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3585): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
,W/bt-rfcomm( 3585): RFCOMM_DisconnectInd LCID:0x4e
,I/jxcore-log( 3527): 2015-11-24T16:19:26.809Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.836Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.840Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.883Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.929Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:26.958Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3527): ,
,I/jxcore-log( 3527): 2015-11-24T16:19:27.015Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.056Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.162Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.219Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.304Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.311Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.352Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.358Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.363Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.400Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.406Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.414Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.445Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.455Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.464Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.495Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.522Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.567Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.730Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.761Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3527): 2015-11-24T16:19:27.847Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:27.970Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:28.021Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3527): ,
,I/jxcore-log( 3527): 2015-11-24T16:19:28.051Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:28.142Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests
,I/jxcore-log( 3527): 2015-11-24T16:19:28.327Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3527): 
,I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:19:28.384Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:28.713Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:28.793Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:28.918Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:28.993Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:29.009Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:29.044Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:29.071Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:29.116Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:29.155Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:29.216Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:29.221Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:29.251Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:29.399Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:29.404Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:29.419Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2b34 rs_disc_pending=0
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3585): invalid rfc slot id: 60
I/BtToSocketBase( 3527): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT2047
I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
,I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT2047
I/BtToSocketBase( 3527): Close LocalOutputStream
,I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
,I/BtToSocketBase( 3527): Close bt in
,I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/jxcore-log( 3527): 2015-11-24T16:19:29.892Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3527): 
,W/bt-rfcomm( 3585): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 3585): RFCOMM_DisconnectInd LCID:0x44
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc27a4 rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: G4-1
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 6109
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5-1
,I/jxcore-log( 3527): 2015-11-24T16:19:30.791Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:30.792Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2b34 rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc0eb4 rs_disc_pending=0
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3527): we got incoming connection
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3527): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 12 peers.,
I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3527): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3527): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3527): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(7): G4-1 a2:39:f7:6f:c9:5d,
I/SS      ( 3527): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3527): Peer(9): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3527): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3527): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc0eb4 rs_disc_pending=1,
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc0eb4 rs_disc_pending=0,
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3527): got MESSAGE_READ 82 bytes.,
,I/BTListenerThread( 3527): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3527): MESSAGE_WRITE 82 bytes.
I/HS      ( 3527): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT2346
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3527): Starting the connected thread incoming : true, samsung-SM-G900F_PT2346
I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BTConnectedThread
,I/BtConnectorHelper( 3527): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3527): --DoOneRunRound started
,I/BtToRequestSocket( 3527): LocalHost address: localhost/127.0.0.1, port: 46019
,I/BtToRequestSocket( 3527): --DoOneRunRound ended
,I/jxcore-log( 3527): 2015-11-24T16:19:31.866Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/jxcore-log( 3527): 2015-11-24T16:19:32.392Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data,
I/jxcore-log( 3527): 
,I/        ( 3527): Started service discovery
,I/jxcore-log( 3527): 2015-11-24T16:19:32.414Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.432Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.462Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.492Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data,
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2b34 rs_disc_pending=0,
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3527): 2015-11-24T16:19:32.529Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.534Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.565Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.568Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.581Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.593Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.625Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.658Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.672Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.714Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.744Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.776Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.779Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.830Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.837Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.859Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.906Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.911Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.918Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.955Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.964Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.968Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:32.975Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:33.015Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:33.031Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:33.066Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:33.069Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:33.076Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:33.105Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:33.110Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:33.145Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): invalid rfc slot id: 61
,I/BtToSocketBase( 3527): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2346
,I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
,I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
,I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2346
,I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
,I/BtToSocketBase( 3527): Close bt socket
I/jxcore-log( 3527): 2015-11-24T16:19:33.215Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3527): 
,W/bt-rfcomm( 3585): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
,W/bt-rfcomm( 3585): RFCOMM_DisconnectInd LCID:0x41
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2b34 rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc0eb4 rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT4262, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT4262, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3527): 2015-11-24T16:19:35.796Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:35.796Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:35.797Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:35.797Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 7C:F9:0E:37:96:AB,
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5-1
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [7c:f9:0e:37:96:ab]: 7, f, 610c
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 63
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:19:37.008Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:37.009Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:37.010Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:19:42.011Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:42.012Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3527): 2015-11-24T16:19:47.017Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:47.018Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:47.018Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:47.019Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 64
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:19:47.199Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:47.200Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:47.200Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:19:52.201Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:52.202Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:57.207Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:57.208Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:57.208Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:57.209Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
I/        ( 3527): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 3527): Connecting to null, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 65
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:19:57.448Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:57.449Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:57.456Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:57.459Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 1
I/jxcore-log( 3527): 
I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:57.463Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:57.464Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:57.465Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 52008 ms, rnd: 5, ex: Connection to 7C:F9:0E:37:96:AB failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 6, f, 4106
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 66
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:19:57.725Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:19:57.726Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:19:57.727Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 9 peers.
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3527): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3527): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3527): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3527): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc107c rs_disc_pending=0
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL,
E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT4262, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT4262, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/jxcore-log( 3527): 2015-11-24T16:20:02.727Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:02.728Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3527): 2015-11-24T16:20:07.733Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:07.734Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:07.734Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:07.735Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66,
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 67
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:20:08.382Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:08.383Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:08.383Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:20:13.384Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:13.385Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:18.388Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:18.389Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:18.389Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:18.390Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 68
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:20:19.270Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:19.270Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:19.271Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/SS      ( 3527): Found 3 peers.,
I/SS      ( 3527): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3527): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3527): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Started service discovery
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc107c rs_disc_pending=0
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3527): 2015-11-24T16:20:24.272Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:24.273Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:29.278Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:29.278Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:29.279Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:29.279Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 69
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:20:30.649Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): ,
,I/jxcore-log( 3527): 2015-11-24T16:20:30.650Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:30.650Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:20:35.651Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:35.652Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,V/GoogleAuthProtoRequest( 3147): [321] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1548): Explicit concurrent mark sweep GC freed 60811(2MB) AllocSpace objects, 15(1654KB) LOS objects, 36% free, 27MB/43MB, paused 924us total 45.132ms
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3147): [321] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3147): [321] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3147): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3147): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3147): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3147): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3147): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3147): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3147): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3147): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3147): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3147): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3527): 2015-11-24T16:20:40.657Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:40.658Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3527): ,
I/jxcore-log( 3527): 2015-11-24T16:20:40.658Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:40.659Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 70
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:20:42.056Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:42.057Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:42.062Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:42.066Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 2
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:42.072Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:42.074Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:42.074Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 44594 ms, rnd: 5, ex: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/GCM     ( 1548): Message class com.google.f.a.a.i
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc107c rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3585): SDP - Rcvd conn cnf with error: 0x1f  CID 0x42,
E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 71
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:20:43.091Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:43.093Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:43.094Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL,
,I/jxcore-log( 3527): 2015-11-24T16:20:48.095Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:48.096Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/jxcore-log( 3527): 2015-11-24T16:20:53.099Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A,
,I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:53.099Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:53.100Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:53.101Z SendDataConnector.js: do connect now,
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820,
I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [b4:ce:f6:ab:a4:6a]: 6, f, 6109
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3527): Starting to Handshake
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread,
I/BTConnectToThread( 3527): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started
,I/BTConnectToThread( 3527): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 3527): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3527): HandshakeOk : HTC-HTC Desire 820_PT6452
I/HS      ( 3527): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT6452
,I/BtConnectorHelper( 3527): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT6452
,I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3527): Creating BtConnectedRequestSocket
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped,
I/BtToRequestSocket( 3527): mHTTPPort  set to : 35914
,I/BtConnectorHelper( 3527): Request socket is using : 35914
I/BtToRequestSocket( 3527): Now accepting connections
,I/BtConnectorHelper( 3527): Calling ConnectionStatusUpdate with port :35914
,I/jxcore-log( 3527): 2015-11-24T16:20:55.003Z SendDataConnector.js: CLIENT connected to 35914, error: null
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:55.004Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3527): 
,I/BtToRequestSocket( 3527): incoming data from: /127.0.0.1, port: 35914
,I/BtToRequestSocket( 3527): Set local streams
,I/BtToRequestSocket( 3527): rin ended ---------------------------;
I/jxcore-log( 3527): 2015-11-24T16:20:55.016Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3527): 
,D/        ( 3585): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:403
,I/jxcore-log( 3527): 2015-11-24T16:20:55.257Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:55.301Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:55.306Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:55.374Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:55.382Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:55.430Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:55.488Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:55.559Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:55.596Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:55.597Z SendDataConnector.js: got all data for this round,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:55.600Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:55.601Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3527): 
,I/BtConnectorHelper( 3527): Disconnect outgoing peer: B4:CE:F6:AB:A4:6A
,I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
,I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close LocalOutputStream
I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
I/BtToSocketBase( 3527): Close bt socket
,I/BtToRequestSocket( 3527): Close server socket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3527): 2015-11-24T16:20:55.610Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:55.613Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:20:55.613Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:20:55.614Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 13524 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3527): Starting to connect,
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
W/bt-btif ( 3585): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc1cf4 rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 73
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,I/jxcore-log( 3527): 2015-11-24T16:21:00.669Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:00.669Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:00.670Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:21:05.671Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:05.672Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:21:10.676Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:10.677Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:10.677Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:10.678Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp,
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0,
,W/bt-btif ( 3585): invalid rfc slot id: 74
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:21:12.548Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:12.549Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:12.549Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 5 peers.,
I/SS      ( 3527): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(2): S5mini-1 02:f4:6f:30:e0:6d,
I/SS      ( 3527): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3527): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request,
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Started service discovery
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:21:17.554Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3527): ,
I/jxcore-log( 3527): 2015-11-24T16:21:17.555Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A,
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0,
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/        ( 3527): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT474, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT474, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3527): 2015-11-24T16:21:22.559Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:22.560Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true,
I/jxcore-log( 3527): ,
I/jxcore-log( 3527): 2015-11-24T16:21:22.560Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
,I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:22.561Z SendDataConnector.js: do connect now
,I/jxcore-log( 3527): 
I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 75,
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:21:24.993Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:24.994Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:24.995Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3527): Cleared service requests,
,I/        ( 3527): Started peer discovery
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:21:29.996Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:29.997Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3527): 2015-11-24T16:21:35.000Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:35.001Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:35.001Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:35.002Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null,
,I/BTConnectToThread( 3527): Starting to connect,
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68,
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3585): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 76
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:21:40.149Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:40.150Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:40.151Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3527): Found 7 peers.
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3527): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3527): Started service discovery
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3527): 2015-11-24T16:21:45.152Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:45.152Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3527): 2015-11-24T16:21:50.156Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:50.157Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:50.157Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:50.158Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 77
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:21:51.917Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:51.918Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:51.923Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:51.926Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 2
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:51.933Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:21:51.935Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
,I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:51.936Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 56306 ms, rnd: 5, ex: Connection to 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2cfc rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 6, f, 6109
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 78
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:21:53.430Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:53.431Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:53.431Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3527): 2015-11-24T16:21:58.433Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:21:58.434Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 8 peers.
I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3527): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3527): 2015-11-24T16:22:03.437Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:03.438Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:03.438Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:22:03.439Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 3585): info:x10,
,D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 79
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:22:04.946Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:04.948Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:22:04.949Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3527): 2015-11-24T16:22:09.951Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:09.952Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests,
,I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:22:14.956Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:22:14.957Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:22:14.958Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:14.958Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1,
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 80
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:22:16.435Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:22:16.436Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:16.437Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive,
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 9 peers.
I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3527): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3527): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3527): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Started service discovery
,I/jxcore-log( 3527): 2015-11-24T16:22:21.437Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:22:21.438Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3527): 2015-11-24T16:22:26.442Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:26.443Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:26.443Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:26.444Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1,
,I/BTConnectToThread( 3527): Starting to connect,
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback,
,I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 81
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/jxcore-log( 3527): 2015-11-24T16:22:29.562Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:29.563Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
,I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:29.564Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3527): 2015-11-24T16:22:34.565Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:22:34.566Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 9 peers.
I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3527): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3527): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3527): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/jxcore-log( 3527): 2015-11-24T16:22:39.568Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:22:39.569Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:39.570Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:39.570Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3527): Started service discovery
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1,
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 3585): invalid rfc slot id: 82
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:22:40.574Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:40.575Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:22:40.580Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:22:40.585Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 2
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:40.587Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:22:40.588Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:40.588Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
I/        ( 3527): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 7C:F9:0E:37:96:AB
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 48641 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [7c:f9:0e:37:96:ab]: 6, f, 410d
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 83
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:22:42.619Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:42.620Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:42.620Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:22:47.622Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:47.623Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/jxcore-log( 3527): 2015-11-24T16:22:52.626Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:52.626Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:52.627Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:52.627Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3527): Starting to connect,
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback,
I/        ( 3527): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [7c:f9:0e:37:96:ab]: 6, f, 410d
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 84
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:22:52.789Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:52.790Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:22:52.791Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery,
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:22:57.792Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:22:57.792Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 8 peers.
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(4): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3527): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3527): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/        ( 3527): Started service discovery
,I/jxcore-log( 3527): 2015-11-24T16:23:02.796Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:02.797Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:02.797Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:02.798Z SendDataConnector.js: do connect now,
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3527): Starting to connect,
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback,
I/        ( 3527): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 85
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:23:03.047Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:03.048Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:03.048Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3527): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:23:08.049Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:08.050Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3236): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3236): 	at jdm.a(PG:82)
E/HttpOperation( 3236): 	at jcs.o(PG:406)
E/HttpOperation( 3236): 	at jcn.a(PG:1379)
E/HttpOperation( 3236): 	at jcs.i(PG:143)
E/HttpOperation( 3236): 	at blb.a(PG:3937)
E/HttpOperation( 3236): 	at czp.a(PG:18188)
E/HttpOperation( 3236): 	at czp.a(PG:9081)
E/HttpOperation( 3236): 	at czq.run(PG:1686)
E/HttpOperation( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3236): 	at jdj.a(PG:4091)
E/HttpOperation( 3236): 	at jdj.a(PG:1125)
E/HttpOperation( 3236): 	at jdm.a(PG:77)
E/HttpOperation( 3236): 	... 12 more
E/HttpOperation( 3236): Caused by: faj: BadAuthentication
E/HttpOperation( 3236): 	at fal.a(PG:38)
E/HttpOperation( 3236): 	at jdj.a(PG:4089)
E/HttpOperation( 3236): 	... 14 more
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3236): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3236): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3236): 	at jdm.a(PG:82)
E/HttpOperation( 3236): 	at jcs.o(PG:406)
E/HttpOperation( 3236): 	at jcn.a(PG:1379)
E/HttpOperation( 3236): 	at jcs.i(PG:143)
E/HttpOperation( 3236): 	at hec.a(PG:42)
E/HttpOperation( 3236): 	at hee.a(PG:102)
E/HttpOperation( 3236): 	at czr.a(PG:65)
E/HttpOperation( 3236): 	at kka.a(PG:108)
E/HttpOperation( 3236): 	at czp.a(PG:19176)
E/HttpOperation( 3236): 	at czp.a(PG:9081)
E/HttpOperation( 3236): 	at czq.run(PG:1686)
E/HttpOperation( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/HttpOperation( 3236): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3236): 	at jdj.a(PG:4091)
E/HttpOperation( 3236): 	at jdj.a(PG:1125)
E/HttpOperation( 3236): 	at jdm.a(PG:77)
E/HttpOperation( 3236): ,	... 15 more
E/HttpOperation( 3236): Caused by: faj: BadAuthentication
E/HttpOperation( 3236): 	at fal.a(PG:38)
E/HttpOperation( 3236): 	at jdj.a(PG:4089),
E/HttpOperation( 3236): 	... 17 more
E/ExperimentLoader( 3236): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 3236): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3236): 	at jdm.a(PG:82)
E/ExperimentLoader( 3236): 	at jcs.o(PG:406)
E/ExperimentLoader( 3236): 	,at jcn.a(PG:1379)
E/ExperimentLoader( 3236): 	at jcs.i(PG:143)
E/ExperimentLoader( 3236): 	at hec.a(PG:42)
E/ExperimentLoader( 3236): ,	at hee.a(PG:102)
E/ExperimentLoader( 3236): 	at czr.a(PG:65)
E/ExperimentLoader( 3236): 	at kka.a(PG:108)
E/ExperimentLoader( 3236): 	at czp.a(PG:19176)
E/ExperimentLoader( 3236): ,	at czp.a(PG:9081)
E/ExperimentLoader( 3236): ,	at czq.run(PG:1686)
E/ExperimentLoader( 3236): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3236): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/ExperimentLoader( 3236): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3236): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3236): 	at java.lang.Thread.run(Thread.java:818),
E/ExperimentLoader( 3236): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3236): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3236): 	at jdj.a(PG:1125)
,E/ExperimentLoader( 3236): 	at jdm.a(PG:77)
E/ExperimentLoader( 3236): 	... 15 more
E/ExperimentLoader( 3236): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3236): 	at fal.a(PG:38)
E/ExperimentLoader( 3236): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3236): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1194764, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0,
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B,
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0,
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3527): 2015-11-24T16:23:13.053Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:13.054Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
,I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:13.054Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:13.055Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 7C:F9:0E:37:96:AB, name: null,
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 86
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:23:14.079Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:14.079Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:14.080Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3527): 2015-11-24T16:23:19.080Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:19.081Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests,
I/        ( 3527): Started peer discovery
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3527): Found 11 peers.
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b,
I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3527): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3527): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3527): 2015-11-24T16:23:24.086Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:24.087Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:24.087Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:24.088Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3527): Starting to connect,
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:87, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 87
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:23:25.419Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:25.421Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:25.426Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:25.429Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 2
I/jxcore-log( 3527): 
I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:25.433Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:25.434Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:25.434Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 44834 ms, rnd: 5, ex: Connection to 7C:F9:0E:37:96:AB failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2ec4 rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 88
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:23:26.988Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:26.989Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:26.990Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc107c rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery,
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/jxcore-log( 3527): 2015-11-24T16:23:31.991Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:31.992Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3527): 2015-11-24T16:23:36.997Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:36.998Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:36.998Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:36.999Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 11 peers.
I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3527): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3527): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3527): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 89
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:23:38.282Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:38.283Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:38.283Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Started service discovery
,I/BooksSync( 3964): Starting books sync for 61035162, extras: ade
,I/art     (  820): Explicit concurrent mark sweep GC freed 57730(2MB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 1.479ms total 73.792ms
,I/BooksConfig( 3964): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3964): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3964): Soft error
E/BooksSync( 3964): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3964): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3964): Sync error
E/BooksSync( 3964): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3964): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3964): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1220287, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:23:43.285Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:43.286Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/UsageStatsService(  820): User[0] Flushing usage stats to disk
,I/jxcore-log( 3527): 2015-11-24T16:23:48.289Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:48.290Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:48.290Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:48.291Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 90
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:23:48.716Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:48.716Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:48.716Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:23:53.717Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:53.718Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:23:58.721Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:58.722Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:58.722Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:23:58.723Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 3585): process_service_search_attr_rsp,
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 3585): invalid rfc slot id: 91
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:24:00.051Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:24:00.052Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:24:00.053Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:24:05.054Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:24:05.055Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:24:10.059Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:24:10.060Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:24:10.060Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:24:10.061Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
I/        ( 3527): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3527): Starting to connect,
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 34:FC:EF:11:B1:66
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 92
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:24:10.799Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:24:10.800Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:24:10.804Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:24:10.807Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 3
I/jxcore-log( 3527): 
I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:24:10.810Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:24:10.811Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:24:10.812Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null
I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 45368 ms, rnd: 5, ex: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc107c rs_disc_pending=1
W/bt-btif ( 3585): bta_dm_check_av:0
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [80:01:84:8a:b3:68]: 6, f, 6109,
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2cfc rs_disc_pending=1
,W/bt-btif ( 3585): bta_dm_check_av:0
W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:93, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 93,
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:24:14.394Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:24:14.394Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:24:14.395Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:24:19.396Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:24:19.397Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/jxcore-log( 3527): 2015-11-24T16:24:24.400Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:24:24.401Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:24:24.402Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:24:24.402Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [80:01:84:8a:b3:68]: 6, f, 6109
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 94
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:24:27.738Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:24:27.739Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:24:27.739Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:24:32.740Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:24:32.741Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:24:37.746Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:24:37.746Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:24:37.747Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:24:37.747Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 4 peers.,
I/SS      ( 3527): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3527): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,V/KeepSync( 3435): Connecting to GoogleApiClient
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1823): Handling authorization failure
E/ClientConnectionOperation( 1823): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1823): ,	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1823): 	,at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1823): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/ClientConnectionOperation( 1823): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1823): 	at java.lang.Thread.run(Thread.java:818)
,E/ClientConnectionOperation( 1823): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.a(SourceFile:365)
,E/ClientConnectionOperation( 1823): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1823): 	,at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1823): 	,at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1823): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1823): 	... 7 more
,V/KeepSync( 3435): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3435): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3435): IOException
E/KeepSync( 3435): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3435): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3435): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
,E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3435): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3435): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3435): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3435): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3435): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3435): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3435): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3435): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3435): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3435): 	,... 10 more
W/KeepSync( 3435): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1306769, reason: 10079, SyncResult: stats [ numIoExceptions: 1],
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:,
,I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0,
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:95, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 95
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:25:07.490Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:25:07.491Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:25:07.491Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL,
,I/jxcore-log( 3527): 2015-11-24T16:25:12.492Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:25:12.493Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:25:17.498Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:25:17.499Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:25:17.499Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:25:17.500Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 3585): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:96, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 96
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:25:22.658Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:25:22.659Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:25:22.659Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 5 peers.
,I/SS      ( 3527): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3527): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3527): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3527): 2015-11-24T16:25:27.661Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:25:27.662Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:25:32.665Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:25:32.666Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:25:32.666Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
,I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:25:32.667Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 80:01:84:8A:B3:68, name: null,
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3527): Cleared service requests
I/        ( 3527): Started peer discovery
,W/bt-sdp  ( 3585): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:97, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 97
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:25:37.829Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:25:37.830Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:25:37.833Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:25:37.839Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- round done--------,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 3
I/jxcore-log( 3527): 
I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:25:37.842Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:25:37.843Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:25:37.844Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 87019 ms, rnd: 5, ex: Connection to 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:98, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 98,
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:25:38.901Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:25:38.902Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:25:38.902Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 5 peers.
I/SS      ( 3527): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3527): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3527): Started service discovery
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3527): 2015-11-24T16:25:43.903Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:25:43.904Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3527): 2015-11-24T16:25:48.907Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:25:48.908Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:25:48.908Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:25:48.909Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1,
W/bt-sdp  ( 3585): process_service_search_attr_rsp,
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:99, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 99
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:25:50.163Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:25:50.164Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:25:50.165Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1,
,I/jxcore-log( 3527): 2015-11-24T16:25:55.166Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): ,
I/jxcore-log( 3527): 2015-11-24T16:25:55.167Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C,
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3527): 2015-11-24T16:26:00.169Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:00.169Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:00.169Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:00.169Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d,
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:100, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3585): invalid rfc slot id: 100
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:26:00.724Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:00.725Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:00.725Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3527): 2015-11-24T16:26:05.727Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:05.728Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 5 peers.
I/SS      ( 3527): Peer(1): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3527): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3527): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3527): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(5): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/        ( 3527): Started service discovery
,I/jxcore-log( 3527): 2015-11-24T16:26:10.731Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:10.732Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:10.733Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:10.733Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
,D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:101, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 101,
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:26:11.358Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:11.360Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:11.361Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3527): 2015-11-24T16:26:16.362Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:16.363Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/jxcore-log( 3527): 2015-11-24T16:26:21.368Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:21.368Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:21.369Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:21.369Z SendDataConnector.js: do connect now,
I/jxcore-log( 3527): 
I/        ( 3527): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1,
,I/        ( 3527): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,W/bt-btif ( 3585): info:x10,
,D/        ( 3585): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d,
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:102, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 102
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3527): 2015-11-24T16:26:22.184Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:22.184Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:22.187Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:22.190Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- round done--------
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 3
I/jxcore-log( 3527): 
I/jxcore-log( 3527): do fake peer & start
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:22.192Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:22.193Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:22.194Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 3527): Connecting to null, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback round[0] time: 44343 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10,
D/        ( 3585): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL,
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending,
I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,E/bt-btm  ( 3585): tBTM_SEC_DEV:0xa2fc2ec4 rs_disc_pending=1,
,W/bt-btif ( 3585): bta_dm_check_av:0,
,W/bt-btif ( 3585): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:103, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 103
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:26:23.337Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed,
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:23.338Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:23.339Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/SS      ( 3527): Found 5 peers.
I/SS      ( 3527): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3527): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/        ( 3527): Started service discovery,
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL,
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3527): 2015-11-24T16:26:28.342Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:28.342Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3527): 2015-11-24T16:26:33.346Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:33.347Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:33.347Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:33.348Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 7C:F9:0E:37:96:AB, name: null,
,I/BTConnectToThread( 3527): Starting to connect
W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3585): info:x10,
,D/        ( 3585): remote version info [7c:f9:0e:37:96:ab]: 6, f, 410d
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:104, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 104
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:26:34.911Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:34.912Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:34.912Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1336","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1336, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1336, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3527): 2015-11-24T16:26:39.914Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:39.915Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/        ( 3527): Cleared service requests,
,I/        ( 3527): Started peer discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 6 peers.
I/SS      ( 3527): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3527): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,I/jxcore-log( 3527): 2015-11-24T16:26:44.918Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:44.919Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:44.919Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:44.920Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3527): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:105, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3585): invalid rfc slot id: 105
I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:26:46.123Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:46.125Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:46.127Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1246): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3527): 2015-11-24T16:26:51.128Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:51.128Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:26:56.132Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:26:56.133Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:56.134Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:26:56.134Z SendDataConnector.js: do connect now
I/jxcore-log( 3527): 
,I/        ( 3527): Selected device address: 7C:F9:0E:37:96:AB, name: null,
,I/BTConnectToThread( 3527): Starting to connect
,W/BluetoothAdapter( 3527): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3527): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 3585): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3585): info:x10
D/        ( 3585): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 3585): process_service_search_attr_rsp
,E/bt-btif ( 3585): DISCOVERY_COMP_EVT slot id:106, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 3585): invalid rfc slot id: 106
,I/BTConnectToThread( 3527): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3527): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3527): 2015-11-24T16:27:00.101Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
I/jxcore-log( 3527): 2015-11-24T16:27:00.101Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:00.104Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3527): 
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 6 peers.
,I/SS      ( 3527): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3527): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3527): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Started service discovery
,I/jxcore-log( 3527): timeout now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): dun
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): weAreDoneNow , resultArray.length: 15,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): done, now sending data to server
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): -- RESULT DATA {"name:":"motorola-Nexus 6_PT5708","time":1000083,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:34:8A:A0","time":8158,"result":"OK","connections":1,"tryCount":1},{"name":"34:FC:EF:11:AE:67","time":4439,"result":"OK","connections":1,"tryCount":1},{"name":"08:EC:A9:50:75:41","time":4906,"result":"OK","connections":1,"tryCount":1},{"name":"F8:95:C7:87:85:54","time":5424,"result":"OK","connections":1,"tryCount":1},{"name":"44:80:EB:7B:5A:05","time":36445,"result":"OK","connections":2,"tryCount":1},{"name":"E0:DB:10:14:E2:C0","time":40919,"result":"OK","connections":3,"tryCount":1},{"name":"08:EC:A9:50:76:27","time":39182,"result":"OK","connections":3,"tryCount":1},{"name":"F4:F1:E1:5C:3B:E2","time":66911,"result":"OK","connections":3,"tryCount":1},{"name":"58:3F:54:73:64:C0","time":51474,"result":"OK","connections":3,"tryCount":1},{"name":"F8:95:C7:87:3C:51","time":9343,"result":"OK","connections":1,"tryCount":1},{"name":"58:2A:F7:ED:96:BE","time":28210,"result":"OK","connections":2,"tryCount":
,I/jxcore-log( 3527): sendList : 100% : 66911 ms, 99% : 66911 ms, 95 : 51474 ms, 90% : 51474 ms.
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Result count 15, range 2386 ms to  66911 ms.
,I/jxcore-log( 3527): 
,I/jxcore-log( 3527): sendList failed peers count : 4 [21.05263157894737 %]
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 3
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): - Peer ID : 34:FC:EF:11:B1:66, Tried : 3
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): - Peer ID : 80:01:84:8A:B3:68, Tried : 3
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): - Peer ID : 00:F4:6F:30:E0:6C, Tried : 3
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): sendList never tried peers count : 0 [0 %]
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:04.085Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:04.085Z SendDataConnector.js: Stop retry timer
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:04.086Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 3585): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT474, peerAddress: 34:FC:EF:11:AE:67
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT474, WifiDirectName: , WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery,
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 6 peers.
I/SS      ( 3527): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3527): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Started service discovery
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 6 peers.
,I/SS      ( 3527): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3527): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-btif ( 3585): info:x10,
,D/        ( 3585): remote version info [34:fc:ef:11:ae:67]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3585): new conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3585): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3527): we got incoming connection
I/BTHandshakeSocketThread( 3527): Creating BTHandshakeSocketThread
I/BTListenerThread( 3527): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread started,
,I/BTListenerThread( 3527): got MESSAGE_READ 76 bytes.
,I/BTListenerThread( 3527): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3527): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3527): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT474
I/BTHandshakeSocketThread( 3527): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3527): Starting the connected thread incoming : true, LGE-Nexus 5_PT474
,I/BtToSocketBase( 3527): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3527): Creating BTConnectedThread
I/BtConnectorHelper( 3527): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3527): --DoOneRunRound started
,I/BtToRequestSocket( 3527): LocalHost address: localhost/127.0.0.1, port: 46019
,I/BtToRequestSocket( 3527): --DoOneRunRound ended
,I/jxcore-log( 3527): 2015-11-24T16:27:50.291Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.702Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.706Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.711Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.714Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.719Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.724Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.726Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.728Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3527): ,
,I/        ( 3527): Cleared service requests
,I/jxcore-log( 3527): 2015-11-24T16:27:50.765Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.768Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3527): 
,I/        ( 3527): Started peer discovery
,I/jxcore-log( 3527): 2015-11-24T16:27:50.771Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.775Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.815Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.820Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.856Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.861Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.866Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.905Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.911Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.917Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:27:50.955Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3527): 
,W/bt-btif ( 3585): invalid rfc slot id: 62
I/BtToSocketBase( 3527): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT474
,I/BtToSocketBase( 3527): Stop ReceivingThread
I/BtToSocketBase( 3527): Stop SendingThread
I/BtToSocketBase( 3527): Close local in
I/BtToSocketBase( 3527): Close LocalOutputStream
,I/BtToSocketBase( 3527): Close localHostSocket
I/BtToSocketBase( 3527): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close bt in
,I/BtConnectorHelper( 3527): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3527): Close bt out
,I/BtConnectorHelper( 3527): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT474
I/BtToSocketBase( 3527): Close bt socket
I/BtToSocketBase( 3527): Close bt in
I/BtToSocketBase( 3527): Close bt out
,I/BtToSocketBase( 3527): Close bt socket
I/jxcore-log( 3527): 2015-11-24T16:27:51.072Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3527): 
,W/bt-rfcomm( 3585): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3585): RFCOMM_DisconnectInd LCID:0x47,
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3585): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3585): onReceive
,I/BTConnectionReceiver( 1473): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1473): Bluetooth Device Name: Nexus 5,
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 8 peers.,
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86,
,I/SS      ( 3527): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3527): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b,
I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2,
I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d,
I/SS      ( 3527): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3527): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery,
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0,
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:,
I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 8 peers.
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3527): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 6 peers.,
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3527): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3527): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2,
,I/SS      ( 3527): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT474, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT474, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/        ( 3527): Cleared service requests
I/        ( 3527): Started peer discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 4 peers.
,I/SS      ( 3527): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3527): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(4): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3527): Added service request
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1246): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 3527): Cleared service requests
,I/        ( 3527): Started peer discovery
,I/EventLogService( 1823): Opted in for usage reporting
I/EventLogService( 1823): Aggregate from 1448380801164 (log), 1448380801164 (data)
,W/EventLogAggregator( 1823): Unknown tag: snet_gcore
W/EventLogAggregator( 1823): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1823): dumping service [account]
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 7 peers.
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3527): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3527): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT474, peerAddress: 34:FC:EF:11:AE:67
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT474, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3527): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3527): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3527): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3527): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3527): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3527): Cleared service requests
I/        ( 3527): Started peer discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 9 peers.
,I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3527): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
,I/SS      ( 3527): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3527): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3527): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3527): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/        ( 3527): Started service discovery
,I/        ( 3527): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3527): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3527): Cleared service requests
I/        ( 3527): Started peer discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3527): Found 9 peers.
I/SS      ( 3527): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3527): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3527): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2,
I/SS      ( 3527): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3527): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3527): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3527): Peer(7): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3527): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3527): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3527): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3527): Added service request
,I/wpa_supplicant( 1246): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3527): Started service discovery
,I/wpa_supplicant( 1246): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3585): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28,
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/        ( 3527): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
,I/        ( 3527): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3527): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3527): DBG, CoordinatorConnector command called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): stop tests now !
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): stop current!,
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): testSendData stopped,
,I/jxcore-log( 3527): 
,I/        ( 3527): Stoping All
,I/        ( 3527): Stopping services
I/        ( 3527): Stopping services
I/        ( 3527): Stop Bluetooth
I/        ( 3527): Stop Bluetooth
I/BTListenerThread( 3527): Stopped
,I/jxcore-log( 3527): StopBroadcasting went ok
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): 2015-11-24T16:31:23.681Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3527): 
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3527): Cleared local services
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant( 1246): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/        ( 3527): Cleared service requests
I/        ( 3527): Stopped peer discovery
,I/jxcore-log( 3527): DBG, CoordinatorConnector command called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":2386,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"34:FC:EF:11:AE:67\",\"time\":4439,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"08:EC:A9:50:75:41\",\"time\":4906,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F8:95:C7:87:85:54\",\"time\":5424,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"34:FC:EF:9D:93:0B\",\"time\":5776,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"50:2E:6C:AC:21:50\",\"time\":7788,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":8158,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F8:95:C7:87:3C:51\",\"time\":9343,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"B4:CE:F6:AB:A4:6A\",\"time\":13524,\"result\":\"OK\",\"connections\":2,\"tryCount\":2},{\"name\":\"58:2A:F7:ED:96:BE\",\"time\":282
I/jxcore-log( 3527): ****TEST TOOK:  ms ****
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3527): 
I/jxcore-log( 3527): stop tests now !
I/jxcore-log( 3527): 
I/jxcore-log( 3527): end, event received
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): CoordinatorConnector close called
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The Coordinator has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The Coordinator has closed!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): stop tests now !
I/jxcore-log( 3527): 
I/jxcore-log( 3527): turning Radios off
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Toggling radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  820): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@116813ef mBinding = false
,D/BluetoothManagerService(  820): Message: 2,
,D/BluetoothManagerService(  820): Sending off request.
D/WifiService(  820): setWifiEnabled: false pid=3527, uid=10265
,E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterState( 3585): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3585): Setting state to 13
I/BluetoothAdapterState( 3585): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3585): onBluetoothDisable()
,I/BluetoothAdapterState( 3585): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService(  820): Message: 60
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  820): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3585): onReceive,
,D/BluetoothMapService( 3585): STATE_TURNING_OFF
D/BluetoothMapService( 3585): MAP Service closeService in
,D/BluetoothMapMasInstance( 3585): MAP Service shutdown
V/BluetoothMapMasInstance( 3585): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3585): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3585): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3585): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3585): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3585): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3585): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3585): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
I/BtOppRfcommListener( 3585): stopping Accept Thread
E/BtOppRfcommListener( 3585): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 3585): BluetoothSocket listen thread finished
D/BluetoothAdapterProperties( 3585): Scan Mode:20
D/BluetoothAdapterState( 3585): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
W/bt-btif ( 3585): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 3585): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3585): L2CAP - PSM: 0x0017 not found for deregistration
,D/btif_config_util( 3585): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3527): Radios toggled
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
E/native  (  820): do suspend true
,W/ContextImpl( 4079): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/CommandListener(  351): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1548): Read error: ssl=0x9cc73400: I/O error during system call, Connection timed out
,V/NativeCrypto( 1548): SSL shutdown failed: ssl=0x9cc73400: I/O error during system call, Broken pipe
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ActivityManager(  820): Start proc 4591:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  820): scanCount==0 - aborting
D/WifiScanningService(  820): SCAN_AVAILABLE : 1
D/RttService(  820): SCAN_AVAILABLE : 1
D/WifiScanningService(  820): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  820): DefaultState
D/RttService(  820): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
,E/native  (  820): do suspend true
D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 4079): Adding local MAP profile
,D/BluetoothMap( 4079): Create BluetoothMap proxy object
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 4079): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 4079): finishStartingService: stopping service
,D/BluetoothInputDevice( 4079): Proxy object connected
D/HidProfile( 4079): Bluetooth service connected
,D/BluetoothPan( 4079): BluetoothPAN Proxy object connected
,D/PanProfile( 4079): Bluetooth service connected
,D/BluetoothMap( 4079): Proxy object connected
D/CommandListener(  351): Clearing all IP addresses on wlan0
D/MapProfile( 4079): Bluetooth service connected
D/BluetoothMap( 4079): getConnectedDevices()
,E/WifiStateMachine(  820): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524292
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Disconnected - quitting
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/BluetoothMap( 4079): Bluetooth is Not enabled
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  820): MasterInitialState.processMessage what=3
D/Tethering(  820): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1473): Network connectivity changed, type is: 6
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/GpsLocationProvider(  820): No APN found to select.
,I/wpa_supplicant( 1246): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 1246): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
E/GpsLocationProvider(  820): No APN found to select.
,D/AndroidRuntime( 4584): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4584): CheckJNI is OFF
,D/bt_userial( 3585): RX termination
W/bt-btif ( 3585): ag scb idx 1 not allocated
W/bt_userial( 3585): select_read return size <=0:-1, exiting userial_read_thread
,E/bt-btif ( 3585): BTA AG is already disabled, ignoring ...
,D/bt_userial( 3585): Leaving userial_read_thread()
W/bt-l2cap( 3585): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3585): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3585): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3585): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3585): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3585): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3585): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3585): hw_epilog_process
I/bt_userial_vendor( 3585): device fd = 53 close
,D/AndroidRuntime( 4584): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  820): Killing 3527:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,I/GKI_LINUX( 3585): gki_task task_id=0 [BTU] terminating
,I/wpa_supplicant( 1246): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  820): InitialState.processMessage what=4
E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/PackageSettings(  820): Skipping PackageSetting{110cd34a com.example.hello/10272} due to missing metadata,
,I/GKI_LINUX( 3585): GKI_exit_task 0 done
,I/GKI_LINUX( 3585): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3585): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/StrictMode( 4591): StrictMode policy violation; ~duration=194 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4591): 	,at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4591): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4591): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4591): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4591): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4591): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4591): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 4591): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 4591): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84),
D/StrictMode( 4591): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4591): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4591): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4591): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4591): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4591): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4591): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4591): StrictMode policy violation; ~duration=194 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4591): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
,D/StrictMode( 4591): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4591): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4591): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4591): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4591): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4591): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4591): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4591): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4591): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4591): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4591): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
,D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4591): StrictMode policy violation; ~duration=192 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4591): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4591): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4591): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4591): 	,at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4591): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4591): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4591): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4591): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 4591): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4591): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4591): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4591): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4591): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4591): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4591): 	at android.os.Looper.loop(Looper.java:135)
,D/StrictMode( 4591): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4591): StrictMode policy violation; ~duration=189 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4591): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4591): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 4591): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 4591): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540),
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4591): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4591): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4591): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4591): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4591): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4591): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4591): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4591): StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4591): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4591): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
,D/StrictMode( 4591): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4591): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4591): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4591): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4591): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4591): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4591): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4591): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
,D/StrictMode( 4591): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4591): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4591): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4591): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4591): StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 4591): 	,at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4591): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 4591): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 4591): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 4591): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 4591): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 4591): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 4591): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 4591): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 4591): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 4591): # via Binder call with stack:
D/StrictMode( 4591): android.os.StrictMode$LogStackTrace
D/StrictMode( 4591): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 4591): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 4591): 	,at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 4591): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 4591): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 4591): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 4591): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 4591): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 4591): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
,D/StrictMode( 4591): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4591): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4591): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4591): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4591): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4591): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4591): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4591): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4591): StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4591): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4591): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4591): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4591): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4591): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4591): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4591): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 4591): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540),
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4591): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4591): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4591): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4591): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4591): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4591): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4591): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run,(ZygoteInit.java:903)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4591): StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4591): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4591): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4591): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4591): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4591): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4591): 	,at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4591): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4591): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4591): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4591): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4591): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4591): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4591): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4591): StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4591): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137),
D/StrictMode( 4591): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4591): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4591): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4591): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4591): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4591): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4591): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4591): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4591): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4591): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4591): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4591): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4591): StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4591): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4591): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4591): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4591): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4591): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4591): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4591): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 4591): 	at com.google.p.j.a(PG:121)
D/StrictMode( 4591): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 4591): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 4591): 	at com.google.p.e.a(PG:170)
D/StrictMode( 4591): 	at com.google.p.e.b(PG:21)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4591): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4591): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4591): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4591): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4591): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4591): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4591): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4591): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4591): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4591): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 4591): Application name is not set. Call Builder#setApplicationName.
,E/libprocessgroup(  820): failed to kill 1 processes for processgroup 3527
,W/ActivityManager(  820): Force removing ActivityRecord{34b69bc4 u0 com.test.thalitest/.MainActivity t24}: app died, no saved state
I/WindowState(  820): WIN DEATH: Window{25ebb8f9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  820): Client connection lost with reason: 4
,V/ActivityManager(  820): Display changed displayId=0
,I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,D/Tethering(  820): sendTetherStateChangedBroadcast 0, 0, 0
,D/HeadsetService( 3585): Received stop request...Stopping profile...
D/TaskPersister(  820): removeObsoleteFile: deleting file=24_task.xml
,D/A2dpService( 3585): Received stop request...Stopping profile...
D/HeadsetStateMachine( 3585): Exit Disconnected: -1
D/A2dpStateMachine( 3585): Exit Disconnected: -1
,D/HeadsetStateMachine( 3585): Unbinding service...
D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@245a56ad:true
W/Settings( 2831): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Keyboard.Facilitator( 1212): resetDictionaries() : en_US
,W/Settings( 1849): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1064): Explicit concurrent mark sweep GC freed 80576(3MB) AllocSpace objects, 0(0B) LOS objects, 17% free, 73MB/89MB, paused 1.332ms total 51.598ms
D/BluetoothA2dp( 1064): Proxy object disconnected
I/Keyboard.Facilitator.DecoderInitializer( 1212): run()
,I/art     ( 1473): Explicit concurrent mark sweep GC freed 122661(5MB) AllocSpace objects, 28(448KB) LOS objects, 22% free, 27MB/35MB, paused 351us total 96.725ms
,I/art     (  820): Explicit concurrent mark sweep GC freed 77637(3MB) AllocSpace objects, 10(160KB) LOS objects, 31% free, 34MB/50MB, paused 1.573ms total 85.874ms
I/art     (  820): WaitForGcToComplete blocked for 48.502ms for cause Explicit
D/BluetoothHeadset(  820): Proxy object disconnected
,D/BluetoothHeadset( 1278): Proxy object disconnected
,D/BluetoothHeadset( 1064): Proxy object disconnected
D/BluetoothHeadset(  820): Proxy object disconnected
D/BluetoothHeadset(  820): Proxy object disconnected
D/BluetoothA2dp(  820): Proxy object disconnected
,I/art     (  820): Explicit concurrent mark sweep GC freed 5640(304KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 1.518ms total 54.458ms
,I/art     (  820): WaitForGcToComplete blocked for 63.014ms for cause Explicit
W/BluetoothHeadsetServiceJni( 3585): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3585): Cleaning up Bluetooth Handsfree callback object
,I/Decoder ( 1212): createOrResetDecoder
D/HidService( 3585): Received stop request...Stopping profile...
D/BluetoothInputDevice( 1064): Proxy object disconnected
I/GKI_LINUX( 3585): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3585): GKI_exit_task 2 done
I/GKI_LINUX( 3585): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterState( 3585): Stopping profile services that were post enabled
,D/HealthService( 3585): Received stop request...Stopping profile...
D/BluetoothInputDevice( 4079): Proxy object disconnected
D/HidProfile( 4079): Bluetooth service disconnected
D/PanService( 3585): Received stop request...Stopping profile...
D/BtGatt.DebugUtils( 3585): handleDebugAction() action=null
D/BtGatt.GattService( 3585): Received stop request...Stopping profile...
D/BtGatt.GattService( 3585): stop()
D/BtGatt.AdvertiseManager( 3585): advertise clients cleared
D/BluetoothPan( 4079): BluetoothPAN Proxy object disconnected
D/PanProfile( 4079): Bluetooth service disconnected
,D/BluetoothPan( 1064): BluetoothPAN Proxy object disconnected
,I/ActivityManager(  820): Killing 3611:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,D/JobSchedulerService(  820): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/art     (  820): Explicit concurrent mark sweep GC freed 4230(188KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 1.286ms total 62.066ms
,D/AuthorizationBluetoothService( 1548): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/BluetoothHidServiceJni( 3585): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 3585): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3585): Cleaning up Bluetooth GID callback object
D/BluetoothMapService( 3585): Received stop request...Stopping profile...
D/BluetoothMapService( 3585): stop()
D/BluetoothMapEmailAppObserver( 3585): deinitObservers()
D/BluetoothMapEmailAppObserver( 3585): removeReceiver()
,D/BluetoothMap( 1064): Proxy object disconnected
,I/ConfigService( 1548): onCreate
W/BluetoothHealthServiceJni( 3585): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3585): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3585): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3585): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 3585): MAP Service closeService in
D/BluetoothAdapterState( 3585): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 3585): cleanup()
D/BluetoothAdapterProperties( 3585): Setting state to 10
,D/BluetoothMapService( 3585): MAP Service closeService in
I/BluetoothAdapterState( 3585): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  820): Message: 60
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  820): Broadcasting onBluetoothStateChange(false) to 17 receivers.
I/BluetoothAdapterState( 3585): Entering OffState
D/BluetoothMap( 4079): Proxy object disconnected
D/MapProfile( 4079): Bluetooth service disconnected
D/BluetoothA2dp( 1064): onBluetoothStateChange: up=false
,W/InputMethodManagerService(  820): Got RemoteException sending setActive(false) notification to pid 3527 uid 10265
,D/BluetoothHeadset( 1064): onBluetoothStateChange: up=false
I/Keyboard.Facilitator( 1212): onFinishInput()
,D/BluetoothHeadset( 1278): onBluetoothStateChange: up=false
D/BluetoothA2dpSink( 1064): onBluetoothStateChange: up=false
,E/BluetoothA2dpSink( 1064): 
E/BluetoothA2dpSink( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@1a80ed1f
E/BluetoothA2dpSink( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1064): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1064): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothMap( 4079): onBluetoothStateChange: up=false
D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 1064): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  820): onBluetoothStateChange: up=false
D/BluetoothMap( 1064): onBluetoothStateChange: up=false
,D/BluetoothPbap( 4079): onBluetoothStateChange: up=false
,D/BluetoothAvrcpController( 1064): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1064): 
E/BluetoothAvrcpController( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@161e986c
E/BluetoothAvrcpController( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1064): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1064): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothInputDevice( 4079): onBluetoothStateChange: up=false
,D/BluetoothHeadsetClient( 1064): onBluetoothStateChange: up=false
E/BluetoothHeadsetClient( 1064): 
E/BluetoothHeadsetClient( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@cfffe35
E/BluetoothHeadsetClient( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1064): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1064): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothHeadset(  820): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  820): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  820): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService(  820): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@116813ef mBinding = false
,D/BluetoothManagerService(  820): Sending unbind request.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1212): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1212): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = user
D/Launcher.Workspace( 1315): 11683562 - stripEmptyScreens()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1212): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1212): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1212): run()
I/StatsUtilsManager( 1212): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1212): shouldRecordStats() = Too Soon
D/Launcher.Workspace( 1315): 11683562 - stripEmptyScreens()
,I/ActivityManager(  820): Start proc 4639:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,D/BluetoothManagerService(  820): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1064): 768488159: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1064): 768488159: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1064): 768488159: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3585): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3585): GKI_exit_task 1 done
I/GKI_LINUX( 3585): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3585): cleanupNative: return from cleanup
I/art     ( 3585): System.exit called, status: 0
I/AndroidRuntime( 3585): VM exiting with result code 0, cleanup skipped.
,I/art     ( 4584): System.exit called, status: 0
,I/AndroidRuntime( 4584): VM exiting with result code 0.
,W/LocationOracleImpl( 1473): Best location was null
,I/HotwordRecognitionRnr( 1473): Starting hotword detection.
I/art     ( 1315): Explicit concurrent mark sweep GC freed 11528(662KB) AllocSpace objects, 13(1519KB) LOS objects, 31% free, 35MB/51MB, paused 2.223ms total 26.118ms
,I/MicrophoneInputStream( 1473): mic_starting com.google.android.apps.gsa.speech.audio.u@3c74684c
,I/ActivityManager(  820): Process com.android.bluetooth (pid 3585) has died
,I/AudioFlinger(  355): AudioFlinger's thread 0xb4cd0000 ready to run
,I/SoundTriggerHwService::Module(  355): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1473): mic_started com.google.android.apps.gsa.speech.audio.u@3c74684c
,I/art     ( 1548): Explicit concurrent mark sweep GC freed 76579(3MB) AllocSpace objects, 8(882KB) LOS objects, 37% free, 27MB/43MB, paused 1.960ms total 41.760ms
,D/audio_hw_primary(  355): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  355): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  355): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  355): enable_snd_device: snd_device(55: voice-rec-mic)
,W/LocationOracleImpl( 1473): Best location was null
,D/audio_hw_primary(  355): enable_audio_route: apply and update mixer path: audio-record
,I/MusicStore( 4639): Database version: 120
,W/LocationOracleImpl( 1473): Best location was null
,I/art     ( 1849): Explicit concurrent mark sweep GC freed 22846(1293KB) AllocSpace objects, 11(176KB) LOS objects, 37% free, 26MB/42MB, paused 993us total 56.549ms
,E/DataBuffer( 1849): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@24f76829)
,I/HotwordWorker( 1473): onReady
,W/ResourcesManager( 4639): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4639): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4639): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660503315
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ProviderInstaller( 4639): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 4639): GMSCore installation verified
,I/ConfigStore( 4639): Config Database version: 1
,E/SQLiteDatabase( 4639): Failed to open database '/data/data/com.google.android.music/databases/config.db'.
E/SQLiteDatabase( 4639): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4639): 	at com.google.android.music.store.ConfigStore.getDatabase(ConfigStore.java:64)
E/SQLiteDatabase( 4639): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 4639): 	at com.google.android.music.store.ConfigContentProvider.query(ConfigContentProvider.java:129)
E/SQLiteDatabase( 4639): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4639): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4639): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 4639): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 4639): 	at com.google.android.music.utils.ConfigCache.get(ConfigCache.java:136)
E/SQLiteDatabase( 4639): 	at com.google.android.music.utils.ConfigUtils.getString(ConfigUtils.java:673)
E/SQLiteDatabase( 4639): 	at com.google.android.music.utils.ConfigUtils.getBoolean(ConfigUtils.java:709)
E/SQLiteDatabase( 4639): 	at com.google.android.music.utils.ConfigUtils.isPlayLoggingEnabled(ConfigUtils.java:399)
E/SQLiteDatabase( 4639): 	at com.google.android.music.eventlog.MusicEventLogger.<init>(MusicEventLogger.java:152)
E/SQLiteDatabase( 4639): 	at com.google.android.music.eventlog.MusicEventLogger.getInstance(MusicEventLogger.java:270)
E/SQLiteDatabase( 4639): 	at com.google.android.music.MusicApplication.onCreate(MusicApplication.java:87)
E/SQLiteDatabase( 4639): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
E/SQLiteDatabase( 4639): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
E/SQLiteDatabase( 4639): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
E/SQLiteDatabase( 4639): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
E/SQLiteDatabase( 4639): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4639): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4639): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4639): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4639): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4639): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4639): 	at com.android.internal.os.,ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4639): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 4639): FATAL EXCEPTION: main
E/AndroidRuntime( 4639): Process: com.google.android.music:main, PID: 4639
E/AndroidRuntime( 4639): java.lang.RuntimeException: Unable to create application com.google.android.music.MusicApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4639): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4556)
E/AndroidRuntime( 4639): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
E/AndroidRuntime( 4639): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
E/AndroidRuntime( 4639): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4639): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4639): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4639): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4639): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4639): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4639): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4639): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4639): 	at com.google.android.music.store.ConfigStore.getDatabase(ConfigStore.java:64)
E/AndroidRuntime( 4639): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 4639): 	at com.google.android.music.store.ConfigContentProvider.query(ConfigContentProvider.java:129)
E/AndroidRuntime( 4639): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/AndroidRuntime( 4639): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/AndroidRuntime( 4639): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/AndroidRuntime( 4639): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/AndroidRuntime( 4639): 	at com.google.android.music.utils.ConfigCache.get(ConfigCache.java:136)
E/AndroidRuntime( 4639): 	at com.google.android.music.utils.ConfigUtils.getString(ConfigUtils.java:673)
E/AndroidRuntime( 4639): 	at com.google.android.music.utils.ConfigUtils.getBoolean(ConfigUtils.java:709)
E/AndroidRuntime( 4639): 	at com.google.android.music.utils.ConfigUtils.isPlayLoggingEnabled(ConfigUtils.java:399)
E/AndroidRuntime( 4639): 	at com.google.android.music.eventlog.MusicEventLogger.<init>(MusicEventLogger.java:152)
E/AndroidRuntime( 4639): 	at com.google.android.music.eventlog.MusicEventLogger.getInstance(MusicEventLogger.java:270)
E/AndroidRuntime( 4639): 	at com.google.android.music.MusicApplication.onCreate(MusicApplication.java:87)
E/AndroidRuntime( 4639): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
E/AndroidRuntime( 4639): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
E/AndroidRuntime( 4639): 	... 9 more
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
D/OpenGLRenderer(  820): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  820): Validating map...
,I/OpenGLRenderer(  820): Initialized EGL, version 1.4
,D/OpenGLRenderer(  820): Enabling debug mode 0
,I/HotwordDetector( 1473): Closing mic
I/MicrophoneInputStream( 1473): mic_close com.google.android.apps.gsa.speech.audio.u@3c74684c
,D/audio_hw_primary(  355): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  355): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  355): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1473): Stopping hotword detection.
I/HotwordRecognitionRnr( 1473): Hotword detection finished
,E/native  ( 1212): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1212): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,I/ActivityManager(  820): Start proc 4688:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,E/SQLiteDatabase( 4688): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 4688): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4688): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4688): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4688): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4688): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4688): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4688): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4688): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4688): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4688): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4688): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 4688): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/SQLiteDatabase( 4688): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/SQLiteDatabase( 4688): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/SQLiteDatabase( 4688): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4688): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4688): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4688): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 4688): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4688): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4688): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4688): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4688): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4688): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4688): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4688): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4688): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4688): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4688): 	at com.android.provider,s.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 4688): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/SQLiteOpenHelper( 4688): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/SQLiteOpenHelper( 4688): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/SQLiteOpenHelper( 4688): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4688): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 4688): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 4688): (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,E/AndroidRuntime( 4688): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4688): Process: android.process.acore, PID: 4688
E/AndroidRuntime( 4688): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 4688): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4688): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4688): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4688): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4688): 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
E/AndroidRuntime( 4688): 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
E/AndroidRuntime( 4688): 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1068)
E/AndroidRuntime( 4688): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
E/AndroidRuntime( 4688): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/AndroidRuntime( 4688): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 4688): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/AndroidRuntime( 4688): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/AndroidRuntime( 4688): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4688): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4688): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4688): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  820): Can't write: system_app_crash,
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72),
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method),
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
,I/ConfigService( 1548): onDestroy
,E/QMI_FW  (  820): xport_send: Sendto failed for port 4096
E/LocSvc_api_v02(  820): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660503315
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/qdhwcomposer(  264): handle_blank_event: dpy:0 panel power state: 0

```
