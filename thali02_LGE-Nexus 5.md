#### Test 5133502802397d9_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
W/ResourcesManager( 3028): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3028): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,--------- beginning of main
D/Finsky  ( 2573): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  757): Killing 2290:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
V/JNIHelp ( 3028): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/libprocessgroup(  757): failed to open /acct/uid_1000/pid_2290/cgroup.procs: No such file or directory
W/System  ( 3028): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3028): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3081): 
D/AndroidRuntime( 3081): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3081): CheckJNI is OFF
D/AndroidRuntime( 3081): Calling main entry com.android.commands.am.Am
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  757): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3097 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3081): Shutting down VM
V/ActivityManager(  757): Display changed displayId=0
I/Icing   ( 1648): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1648): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1648): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 3097): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3097): Time to load native libraries: 1 ms (timestamps 4624-4625)
I/LibraryLoader( 3097): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3097): Binding Chromium to main looper Looper (main, tid 1) {4d43a2}
I/LibraryLoader( 3097): Expected native library version number "",actual native library version number ""
I/chromium( 3097): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3097): Initializing chromium process, singleProcess=true
W/art     ( 3097): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3097): ApplicationContext is null in ApplicationStatus
W/chromium( 3097): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3097): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3097): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3097): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1bd14ec9:true
,D/BluetoothAdapter( 3097): 568326126: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3097): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3097): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3097): CordovaWebView is running on device made by: LGE
W/art     ( 3097): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3097): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3097): Render dirty regions requested: true
D/Atlas   ( 3097): Validating map...
W/chromium( 3097): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3097): Initialized EGL, version 1.4
D/OpenGLRenderer( 3097): Enabling debug mode 0
W/BindingManager( 3097): Cannot call determinedVisibility() - never saw a connection for the pid: 3097
W/IInputConnectionWrapper( 3097): showStatusIcon on inactive InputConnection
I/ActivityManager(  757): Displayed com.test.thalitest/.MainActivity: +425ms (total +59s192ms)
D/JsMessageQueue( 3097): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3097): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1549956992
D/JX-Cordova( 3097): jxcore cordova android initializing
I/ActivityManager(  757): Killing 2370:com.google.android.youtube/u0a80 (adj 15): empty #17
W/libprocessgroup(  757): failed to open /acct/uid_10080/pid_2370/cgroup.procs: No such file or directory
,W/jxcore-log( 3097): Initializing JXcore engine
W/jxcore-log( 3097): JXcore engine is ready
,W/jxcore-log( 3097): Starting JXcore engine
,W/.test.thalitest( 3097): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7868]" dev="sockfs" ino=7868 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3097): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3097): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8489]" dev="sockfs" ino=8489 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3097): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19143]" dev="sockfs" ino=19143 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3097): Platform android
W/jxcore-log( 3097): 
W/jxcore-log( 3097): Process ARCH arm
W/jxcore-log( 3097): 
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3097): JXcore Cordova bridge is ready!
I/jxcore-log( 3097): 
W/jxcore-log( 3097): JXcore engine is started
I/Choreographer( 3097): Skipped 108 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3097): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3097): Toggling radios to true
I/jxcore-log( 3097): 
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  757): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  757): Message: 1
D/BluetoothManagerService(  757): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  757): New client listening to asynchronous messages
D/WifiService(  757): setWifiEnabled: true pid=3097, uid=10270
E/WifiService(  757): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3097): Radios toggled
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  757): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  757): do suspend true
,I/ActivityManager(  757): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3150 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1321): Read error: ssl=0xa421be00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1321): SSL shutdown failed: ssl=0xa421be00: I/O error during system call, Broken pipe
,D/ConnectivityService(  757): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): ValidatedState{ when=-15ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=-15ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiStateMachine(  757): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  991): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  757): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  757): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  757): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  757): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Disconnected - quitting
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  757): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1273): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/ResourcesManager( 3150): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
D/WifiNetworkAgent(  757): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityManager.CallbackHandler( 1648): CM callback handler got msg 524292
,D/AdapterServiceConfig( 3150): Adding HeadsetService
D/AdapterServiceConfig( 3150): Adding A2dpService
,D/AdapterServiceConfig( 3150): Adding HidService
D/AdapterServiceConfig( 3150): Adding HealthService
D/AdapterServiceConfig( 3150): Adding PanService
D/AdapterServiceConfig( 3150): Adding GattService
D/AdapterServiceConfig( 3150): Adding BluetoothMapService
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23e4f2cf:true
,D/BluetoothAdapterState( 3150): make
,I/bluedroid( 3150): init
,I/BluetoothAdapterState( 3150): Entering OffState
,I/bte_conf( 3150): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3150): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3150): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3150): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3150): get_profile_interface socket
I/bluedroid( 3150): get_profile_interface map_client
,D/BluetoothManagerService(  757): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  757): Message: 40
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3150): config_hci_snoop_log
,I/GKI_LINUX( 3150): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothManagerService(  757): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  757): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/BluetoothAdapterProperties( 3150): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  757): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  757): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3150): Name is: Nexus 5
,D/BluetoothAdapterState( 3150): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3150): Setting state to 11
,I/BluetoothAdapterState( 3150): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  757): Message: 60
,D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  757): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3150): make
,I/BluetoothBondStateMachine( 3150): StableState(): Entering Off State
,I/ActivityManager(  757): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3193 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothHeadset( 1273): Proxy object connected
,D/BluetoothHeadset(  757): Proxy object connected
D/BluetoothHeadset( 1239): Proxy object connected
,I/BluetoothAdapterState( 3150): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetService( 3150): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3150): classInitNative: succeeds
,D/BluetoothHeadset( 1239): Proxy object connected
,D/HeadsetStateMachine( 3150): make
,D/HeadsetStateMachine( 3150): max_hf_connections = 1
I/bluedroid( 3150): get_profile_interface handsfree
,D/BluetoothAdapterService( 3150): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ccd5833
,D/HeadsetStateMachine( 3150): Enter Disconnected: -2, size: 0
,D/BluetoothA2dp(  757): Proxy object connected
,D/A2dpService( 3150): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3150): classInitNative: succeeds
,I/bluedroid( 3150): get_profile_interface avrcp
,E/RemoteController( 3150): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 3150): classInitNative: succeeds
D/A2dpStateMachine( 3150): make
,I/bluedroid( 3150): get_profile_interface a2dp
,I/GKI_LINUX( 3150): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3150): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ccd5833
,I/BluetoothHidServiceJni( 3150): classInitNative: succeeds
D/A2dpStateMachine( 3150): Enter Disconnected: -2
,D/HidService( 3150): Received start request. Starting profile...
I/bluedroid( 3150): get_profile_interface hidhost
D/BluetoothAdapterService( 3150): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ccd5833
I/BluetoothHealthServiceJni( 3150): classInitNative: succeeds
D/HealthService( 3150): Received start request. Starting profile...
,I/bluedroid( 3150): get_profile_interface health
D/BluetoothAdapterService( 3150): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ccd5833
,I/BluetoothPanServiceJni( 3150): classInitNative(L105): succeeds
,D/PanService( 3150): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3150): initializeNative(L110): pan
,I/bluedroid( 3150): get_profile_interface pan
,D/BluetoothAdapterService( 3150): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ccd5833
I/BtGatt.JNI( 3150): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 3150): handleDebugAction() action=null
,D/BtGatt.GattService( 3150): Received start request. Starting profile...
D/BtGatt.GattService( 3150): start()
I/bluedroid( 3150): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3150): advertise manager created
,D/BluetoothAdapterService( 3150): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ccd5833
,V/BluetoothMapService( 3150): BluetoothMapBinder()
,D/BluetoothMapService( 3150): Received start request. Starting profile...
,D/BluetoothMapService( 3150): start()
,D/BluetoothMapEmailSettingsLoader( 3150): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3150): createReceiver()
,D/BluetoothMapEmailAppObserver( 3150): initObservers()
D/BluetoothMapEmailAppObserver( 3150): getEnabledAccountItems()
,D/BluetoothAdapterService( 3150): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ccd5833
D/HeadsetStateMachine( 3150): Proxy object connected
D/HeadsetStateMachine( 3150): Disconnected process message: 10, size: 0
,V/BluetoothMapService( 3150): Handler(): got msg=1
D/HeadsetPhoneState( 3150): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3150): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3150): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3150): enable
I/ActivityManager(  757): Killing 2475:com.google.android.deskclock/u0a38 (adj 15): empty #17
I/bt_hci_bdroid( 3150): init
I/GKI_LINUX( 3150): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3150): btu_task pending for preload complete event
,I/bt_vendor( 3150): init
I/bt_vnd_conf( 3150): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3150): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3150): userial_init
,I/bt_userial_vendor( 3150): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3150): device fd = 53 open
,D/bt_userial( 3150): Entering userial_read_thread()
,I/bt_hwcfg( 3150): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3150): Chipset BCM4335C0
D/bt_hwcfg( 3150): Target name = [BCM4335C0]
,I/bt_hwcfg( 3150): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,W/libprocessgroup(  757): failed to open /acct/uid_10038/pid_2475/cgroup.procs: No such file or directory
,D/WifiService(  757): New client listening to asynchronous messages
,D/AuthorizationBluetoothService( 1321): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/bt_hwcfg( 3150): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3150): Settlement delay -- 100 ms
I/bt_hwcfg( 3150): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3150): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3150): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3150): vendor lib fwcfg completed
I/bt-btu  ( 3150): btu_task received preload complete event
,I/        ( 3150): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3150): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3150): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3150): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3150): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3150): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3150): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3150): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3150): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3150): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3150): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3150): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3150): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3150): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3150): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3150): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3ad99d5 
E/bt-btm  ( 3150): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3ad99d5 
,I/wpa_supplicant(  991): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  991): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  991): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  991): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  757): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  757): Start Dhcp Watchdog 2
,E/bt-btif ( 3150): Calling BTA_HhEnable
E/bt-btif ( 3150): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3150): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  757): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  757): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3150): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3150): Scan Mode:20
,D/BluetoothAdapterProperties( 3150): Discoverable Timeout:120
,D/bte_conf( 3150): Device ID record 1 : primary
D/bte_conf( 3150):   vendorId            = 000f
D/bte_conf( 3150):   vendorIdSource      = 0001
D/bte_conf( 3150):   product             = 1200
D/bte_conf( 3150):   version             = 1436
D/bte_conf( 3150):   clientExecutableURL = 
D/bte_conf( 3150):   serviceDescription  = 
D/bte_conf( 3150):   documentationURL    = 
D/bte_conf( 3150): bte_load_did_conf no section named DID2.
E/native  (  757): do suspend false
D/BluetoothPanServiceJni( 3150): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3150): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3150): ScanMode =  20
D/BluetoothAdapterProperties( 3150): State =  11
,D/BluetoothAdapterProperties( 3150): Scan Mode:21
D/BluetoothAdapterProperties( 3150): Setting state to 12
I/BluetoothAdapterState( 3150): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties( 3150): Discoverable Timeout:120
,D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 3150): Entering On State
D/BluetoothManagerService(  757): Broadcasting onBluetoothStateChange(true) to 5 receivers.
,D/BluetoothHeadset( 1273): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1239): onBluetoothStateChange: up=true
D/BluetoothA2dp(  757): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1239): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  757): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  757): Bluetooth State Change Intent: 11 -> 12
,E/WifiStateMachine(  757): scanCount==0 - aborting
,D/BluetoothManagerService(  757): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 3150): onReceive
D/BluetoothMapService( 3150): STATE_ON
,V/BluetoothMapService( 3150): Handler(): got msg=1
D/BluetoothMapMasInstance( 3150): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3150): MAS initSocket()
D/BluetoothMapMasInstance( 3150):   masId = 00
D/BluetoothMapMasInstance( 3150):   msgTypes = 0e
D/BluetoothMapMasInstance( 3150):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3150):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  757): Message: 40
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/Telecom ( 1239): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/bt-smp  ( 3150): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3150): Plain text(LSB ~ MSB) = cb b1 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3150): Encrypted text(LSB ~ MSB) = af ef c1 48 6f 41 98 55 16 f7 45 1d a8 58 69 e0 
W/bt-btm  ( 3150): Stopping oneshot timer
,E/bt_h4   ( 3150): vendor lib postload completed
,W/BluetoothAdapter( 3150): getBluetoothService() called with no BluetoothManagerCallback
,W/ContextImpl( 3193): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,V/BluetoothMapMasInstance( 3150): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3150): Accepting socket connection...
,D/HeadsetStateMachine( 3150): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3150): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3150): mNumber:  mType: 128
D/HeadsetStateMachine( 3150): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3150): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/bt-smp  ( 3150): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3150): Plain text(LSB ~ MSB) = f9 3f 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3150): Encrypted text(LSB ~ MSB) = 20 bc 16 2a 0a 49 de 01 83 43 7f 14 33 95 95 3c 
W/bt-btm  ( 3150): Stopping oneshot timer
,W/bt-smp  ( 3150): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3150): Plain text(LSB ~ MSB) = 7b fe 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3150): Encrypted text(LSB ~ MSB) = f2 f8 cc 8c fa f5 34 c9 bb 3b 17 c4 04 20 e3 1d 
W/bt-btm  ( 3150): Stopping oneshot timer
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fab2b54:true
,W/bt-smp  ( 3150): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3150): Plain text(LSB ~ MSB) = 6a a0 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3150): Encrypted text(LSB ~ MSB) = 29 81 63 7e e4 85 c4 eb 9a 20 f6 33 bd 35 d4 14 
W/bt-btm  ( 3150): Stopping oneshot timer
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/LocalBluetoothProfileManager( 3193): Adding local A2DP profile
,W/BluetoothAdapter( 3150): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  757): Message: 30
,D/LocalBluetoothProfileManager( 3193): Adding local HEADSET profile
,D/BluetoothManagerService(  757): Message: 30
,W/bt-smp  ( 3150): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3150): Plain text(LSB ~ MSB) = 5a 14 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3150): Encrypted text(LSB ~ MSB) = 3a a1 dc 54 ef e1 58 10 3c c0 c4 b0 a3 ae 4b 25 
W/bt-btm  ( 3150): Stopping oneshot timer
,W/bt-smp  ( 3150): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3150): Plain text(LSB ~ MSB) = b5 ed 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3150): Encrypted text(LSB ~ MSB) = c2 93 d6 6e 57 bc 26 fc 0e b5 7f 93 77 ca 0b d8 
W/bt-btm  ( 3150): Stopping oneshot timer
,W/bt-smp  ( 3150): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3150): Plain text(LSB ~ MSB) = c2 88 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3150): Encrypted text(LSB ~ MSB) = 4b 41 19 af 23 3a 8a 83 c8 3b a9 45 aa 63 8d 2e 
W/bt-btm  ( 3150): Stopping oneshot timer
,I/art     (  757): Explicit concurrent mark sweep GC freed 29276(1474KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 1.159ms total 92.522ms
,D/BluetoothManagerService(  757): Message: 30
,D/BluetoothManagerService(  757): Message: 30
,D/LocalBluetoothProfileManager( 3193): Adding local MAP profile
D/BluetoothMap( 3193): Create BluetoothMap proxy object
,D/BluetoothManagerService(  757): Message: 30
,D/BluetoothManagerService(  757): Message: 30
,D/LocalBluetoothProfileManager( 3193): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3193): finishStartingService: stopping service
D/BluetoothA2dp( 3193): Proxy object connected
D/A2dpProfile( 3193): Bluetooth service connected
,D/BluetoothHeadset( 3193): Proxy object connected
D/HeadsetProfile( 3193): Bluetooth service connected
,D/BluetoothInputDevice( 3193): Proxy object connected
D/HidProfile( 3193): Bluetooth service connected
,D/BluetoothPan( 3193): BluetoothPAN Proxy object connected
,D/PanProfile( 3193): Bluetooth service connected
,D/AuthorizationBluetoothService( 1321): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothMap( 3193): Proxy object connected
D/MapProfile( 3193): Bluetooth service connected
D/BluetoothMap( 3193): getConnectedDevices()
V/BluetoothMapService( 3150): getConnectedDevices()
,D/BluetoothPbap( 3193): Proxy object connected
D/PbapServerProfile( 3193): Bluetooth service connected
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3150): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3150): Accept thread started.
,I/dhcpcd  ( 3271): version 5.5.6 starting
,E/dhcpcd  ( 3271): get_duid: Read-only file system
,I/dhcpcd  ( 3271): wlan0: rebinding lease of 192.168.1.114
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3097): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): my name is : LGE-Nexus 5_PT474
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): attempting to connect to test coordinator
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): check test folder
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): found test : ./testFindPeers.js
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): found test : ./testReConnect.js
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): found test : ./testSendData.js
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): Test app app.js loaded
I/jxcore-log( 3097): 
,I/Choreographer( 3097): Skipped 139 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/chromium( 3097): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/dhcpcd  ( 3271): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3271): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2654): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/iu.Environment( 1648): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1648): num queued entries: 0
,I/iu.UploadsManager( 1648): num updated entries: 0
,I/iu.SyncManager( 1648): NEXT; no task
,E/GpsLocationProvider(  757): No APN found to select.
,D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1648): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1648): onCreate
,E/GpsLocationProvider(  757): No APN found to select.
,D/SystemUpdateService( 1648): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1648): active receiver: enabled
,I/SystemUpdateService( 1648): showing system update notification
,I/Babel   ( 1903): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  757): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3317 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ValidateNoPeople(  757): skipping global notification
,V/SystemUpdateService( 1648): retry (wakeup: false) in 3599960 ms
,D/SystemUpdateService( 1648): onDestroy
,E/native  (  757): do suspend true
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  757): Adding iface wlan0 to network 101
,E/ConnectivityService(  757): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  757): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  757): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  757): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  757): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  757): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  757): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757):    accepting network in place of null
,D/CSLegacyTypeTracker(  757): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  757): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1648): CM callback handler got msg 524290
,I/GAv4    ( 3317): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3317):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3317):   adb logcat -s GAv4
,W/GAv4    ( 3317): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3317): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3317): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 24 Nov 2015 16:04:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448381081246], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448381081228]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Validated
D/ConnectivityService(  757): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1648): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1273): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/art     ( 1321): Explicit concurrent mark sweep GC freed 11761(702KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 534us total 24.796ms
,I/WebViewFactory( 3317): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3317): Time to load native libraries: 2 ms (timestamps 659-661)
I/LibraryLoader( 3317): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3317): Binding Chromium to main looper Looper (main, tid 1) {3b600844}
,I/LibraryLoader( 3317): Expected native library version number "",actual native library version number ""
,I/chromium( 3317): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3317): Initializing chromium process, singleProcess=true
,W/art     ( 3317): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3317): ApplicationContext is null in ApplicationStatus
,W/chromium( 3317): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3317): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3317): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3317): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3317): Requires BLUETOOTH permission
,I/NSApplication( 3317): Starting up...
,I/ActivityManager(  757): Killing 2534:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10069/pid_2534/cgroup.procs: No such file or directory
,V/MusicLeanback( 2654): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/iu.Environment( 1648): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1648): num queued entries: 0
I/iu.UploadsManager( 1648): num updated entries: 0
,I/iu.SyncManager( 1648): NEXT; no task
,D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1648): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1648): onCreate
,D/SystemUpdateService( 1648): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1648): active receiver: enabled
,I/SystemUpdateService( 1648): showing system update notification
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  757): skipping global notification
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SystemUpdateService( 1648): retry (wakeup: false) in 3599954 ms
,D/SystemUpdateService( 1648): onDestroy
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 1903): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  757): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2654): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2654): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1648): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1648): onCreate
,D/SystemUpdateService( 1648): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1648): active receiver: enabled
E/GpsLocationProvider(  757): No APN found to select.
I/SystemUpdateService( 1648): showing system update notification
V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ValidateNoPeople(  757): skipping global notification
V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/SystemUpdateService( 1648): retry (wakeup: false) in 3599981 ms
D/SystemUpdateService( 1648): onDestroy
,I/jxcore-log( 3097): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,D/Finsky  ( 2573): [240] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2573): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1321): Vacuum at: now=1448381104611 tag=VacuumService
,D/UdcCache:FPQuery( 1648): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1321): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1321): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1321): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1321): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1321): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1321): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1321):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1321): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1321): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1321): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1321): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1321): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1321): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/art     (  757): Explicit concurrent mark sweep GC freed 31643(1412KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.165ms total 58.069ms
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/ClearcutLoggerApiImpl( 1614): disconnect managed GoogleApiClient
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,D/AlarmManagerService(  757): Setting time of day to sec=1448381196
,W/AlarmManagerService(  757): Unable to set rtc to 1448381196: Invalid argument
,I/ActivityManager(  757): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3530 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 342us total 19.864ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.984ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 7.456ms
,I/ActivityManager(  757): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3572 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/ActivityManager(  757): Killing 1831:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10045/pid_1831/cgroup.procs: No such file or directory
,D/TimeService( 3572): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448381197058
D/        ( 3572): TimeServiceNative: User Time to be set is 1448381197058
D/QC-time-services( 3572): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3572): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3572): Lib:time_genoff_operation: pargs->ts_val = 1448381197058
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448381197058
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1448381197058, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/28/70 21:57:27
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 7509447000
D/QC-time-services(  197): Daemon:new time 1448381197058 
D/QC-time-services(  197): Daemon: delta 1440871750058 genoff 1440871750058 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871750058 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services( 3572): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871750058 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1132416397058
,E/QC-time-services( 3572): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  757): Killing 2624:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,W/libprocessgroup(  757): failed to open /acct/uid_10003/pid_2624/cgroup.procs: No such file or directory
,I/CheckinService( 1648): Checkin interval check for package: unspecified last checkin: 1448344821726 min interval config: 0 actual interval: 36375374
,I/ActivityManager(  757): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3606 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3606): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3606):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3606):   adb logcat -s GAv4
,W/GAv4    ( 3606): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3606): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3606): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  757): Killing 2505:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10070/pid_2505/cgroup.procs: No such file or directory
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector connect called
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Coordinator is now connected to the server!
I/jxcore-log( 3097): 
,I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3097): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector command called
I/jxcore-log( 3097): 
I/jxcore-log( 3097): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":19,"addressList":[{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"
I/jxcore-log( 3097): Start now : testSendData.js
I/jxcore-log( 3097): 
I/jxcore-log( 3097): stop tests now !
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 19
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): check server
I/jxcore-log( 3097): 
I/jxcore-log( 3097): serverPort is 37245
I/jxcore-log( 3097): 
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3097): Stoping All
I/        ( 3097): Stopping services
I/        ( 3097): Stop Bluetooth
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3097): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3097):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"}
,I/        ( 3097): All stuff available and enabled
I/        ( 3097): Stoping All
I/        ( 3097): Stopping services
I/        ( 3097): Stop Bluetooth
I/        ( 3097): Starting All
I/        ( 3097): Stopping services
I/        ( 3097): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@f508645
I/        ( 3097): Stopping services
I/        ( 3097): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"}
I/        ( 3097): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT474","ra":"34:FC:EF:11:AE:67"}, length : 76
,I/        ( 3097): peerDiscoveryTimer timeout value:9351
,I/        ( 3097): Stop Bluetooth
I/        ( 3097): StartBluetooth listener
I/        ( 3097): StartBluetooth listener
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3097): StartBroadcasting started ok
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:10:24.602Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
,I/BTListenerThread( 3097): starting to listen
I/BTListenerThread( 3097): waiting to accept incoming Connection
,I/jxcore-log( 3097): 2015-11-24T16:10:24.661Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:10:24.661Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3097): Connecting to null, at F8:95:C7:87:3C:51
I/jxcore-log( 3097): 2015-11-24T16:10:24.666Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
I/jxcore-log( 3097): 
I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/WB      ( 3097): We already were running, thus doing nothing
,I/        ( 3097): Added local service
I/        ( 3097): Cleared service requests
I/        ( 3097): Stopped peer discovery
I/        ( 3097): Started peer discovery
I/        ( 3097): Discovery state changed to Started.
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 2 peers.
I/SS      ( 3097): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3097): Peer(2): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3097): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3150): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3150): Entering PendingCommandState State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 3150): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 9 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3150): Failed to remove device: F8:95:C7:87:3C:51
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,E/BluetoothEventManager( 3193): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-rfcomm( 3150): PORT_StartCnf failed result:5
E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3150): Do not find the bg connection mask for the remote device
,W/bt-btif ( 3150): invalid rfc slot id: 5
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:10:58.177Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:10:58.177Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3097): 
,D/BluetoothMapService( 3150): onReceive
,I/jxcore-log( 3097): 2015-11-24T16:10:58.180Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/BluetoothBondStateMachine( 3150): StableState(): Entering Off State
,D/BluetoothManagerService(  757): Message: 20
,D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d765f5d:true
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: G4-1
,I/jxcore-log( 3097): 2015-11-24T16:11:03.182Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:11:03.184Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3150): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3150): Entering PendingCommandState State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3150): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3150): StableState(): Entering Off State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3150): new conn_srvc id:26, app_id:255
W/bt-btif ( 3150): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3150): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3097): we got incoming connection
,I/BTHandshakeSocketThread( 3097): Creating BTHandshakeSocketThread
I/BTListenerThread( 3097): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread started
,I/BTListenerThread( 3097): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3097): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6211","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3097): MESSAGE_WRITE 76 bytes.
I/HS      ( 3097): Incoming connection Hand Shake finished for : LGE-LG-D722_PT6211
I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3097): Starting the connected thread incoming : true, LGE-LG-D722_PT6211
I/BtToSocketBase( 3097): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3097): Creating BTConnectedThread
I/BtConnectorHelper( 3097): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3097): --DoOneRunRound started
,I/jxcore-log( 3097): 2015-11-24T16:11:05.062Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3097): 
,I/BtToRequestSocket( 3097): LocalHost address: localhost/127.0.0.1, port: 37245
,I/BtToRequestSocket( 3097): --DoOneRunRound ended
,I/jxcore-log( 3097): 2015-11-24T16:11:05.484Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.497Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.532Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.540Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.569Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.613Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.633Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.646Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.667Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.697Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.757Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.763Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.830Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.868Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.880Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.890Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.900Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.920Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:05.998Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:06.008Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:06.021Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:06.045Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:06.077Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:06.100Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:06.139Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:06.157Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:06.189Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3097): 
,W/bt-btif ( 3150): invalid rfc slot id: 4
,I/BtToSocketBase( 3097): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3097): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3097): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT6211
I/BtToSocketBase( 3097): Stop ReceivingThread
I/BtToSocketBase( 3097): Stop SendingThread
I/BtToSocketBase( 3097): Close local in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3097): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3097): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT6211
I/BtToSocketBase( 3097): Close LocalOutputStream
,I/BtToSocketBase( 3097): Close localHostSocket
I/BtToSocketBase( 3097): Close bt in
I/BtToSocketBase( 3097): Close bt out
I/BtToSocketBase( 3097): Close bt socket
,I/BtToSocketBase( 3097): Close bt in
,I/BtToSocketBase( 3097): Close bt out
,I/BtToSocketBase( 3097): Close bt socket
,I/jxcore-log( 3097): 2015-11-24T16:11:06.330Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3097): 
,W/bt-rfcomm( 3150): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0,
W/bt-rfcomm( 3150): RFCOMM_DisconnectInd LCID:0x43
,I/jxcore-log( 3097): 2015-11-24T16:11:08.212Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:11:08.212Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:11:08.213Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:11:08.214Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3097): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c50ebc rs_disc_pending=1
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c50ebc rs_disc_pending=0
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: G3s-1
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c5124c rs_disc_pending=0
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 3150): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3150): Entering PendingCommandState State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 3150): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3150): StableState(): Entering Off State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/bt-btif ( 3150): new conn_srvc id:26, app_id:255
W/bt-btif ( 3150): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3150): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3097): we got incoming connection
I/BTHandshakeSocketThread( 3097): Creating BTHandshakeSocketThread
I/BTListenerThread( 3097): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread started
,I/BTListenerThread( 3097): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3097): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5708","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3097): MESSAGE_WRITE 76 bytes.
I/HS      ( 3097): Incoming connection Hand Shake finished for : motorola-Nexus 6_PT5708
I/BtConnectorHelper( 3097): Starting the connected thread incoming : true, motorola-Nexus 6_PT5708
I/BtToSocketBase( 3097): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3097): Creating BTConnectedThread
I/BtConnectorHelper( 3097): Server socket is using : 0, and is now connected.
I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3097): --DoOneRunRound started
I/BtToRequestSocket( 3097): LocalHost address: localhost/127.0.0.1, port: 37245
I/jxcore-log( 3097): 2015-11-24T16:11:19.741Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3097): 
I/BtToRequestSocket( 3097): --DoOneRunRound ended
,I/jxcore-log( 3097): 2015-11-24T16:11:20.151Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.158Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.196Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.241Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.255Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.291Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.329Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.334Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.348Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.370Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.382Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.417Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.425Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.454Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.489Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.497Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.506Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.544Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.577Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.583Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.610Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.646Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.691Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.698Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.728Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.767Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.776Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.780Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.816Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.848Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.857Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.868Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.907Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.925Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.957Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:20.967Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3097): 
,W/bt-btif ( 3150): invalid rfc slot id: 6
,I/BtToSocketBase( 3097): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3097): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3097): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT5708
I/BtToSocketBase( 3097): Stop ReceivingThread
I/BtToSocketBase( 3097): Stop SendingThread
I/BtToSocketBase( 3097): Close local in
I/BtToSocketBase( 3097): Close LocalOutputStream
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3097): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3097): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT5708
I/BtToSocketBase( 3097): Close localHostSocket
,I/BtToSocketBase( 3097): Close bt in
I/BtToSocketBase( 3097): Close bt out
I/BtToSocketBase( 3097): Close bt socket
,I/BtToSocketBase( 3097): Close bt in
I/BtToSocketBase( 3097): Close bt out
I/BtToSocketBase( 3097): Close bt socket
,I/jxcore-log( 3097): 2015-11-24T16:11:21.075Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3097): 
,W/bt-rfcomm( 3150): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3150): RFCOMM_DisconnectInd LCID:0x46
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: Nexus 6
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3097): Found 4 peers.
I/SS      ( 3097): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 3097): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(3): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3097): Peer(4): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3097): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3097): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3097): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-rfcomm( 3150): PORT_StartCnf failed result:5
,E/bt-btif ( 3150): check_cod: remote_cod = 0x5a020c
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3150): Do not find the bg connection mask for the remote device
,W/bt-btif ( 3150): invalid rfc slot id: 7
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 9 Address: F8:95:C7:87:3C:51 newState: 0
,E/BluetoothBondStateMachine( 3150): In stable state, received invalid newState: 10
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:11:32.215Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:32.218Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:32.221Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: G4-1
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 3150): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3150): Entering PendingCommandState State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3150): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3150): StableState(): Entering Off State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,W/bt-btif ( 3150): new conn_srvc id:26, app_id:255
W/bt-btif ( 3150): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3150): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3097): we got incoming connection
I/BTHandshakeSocketThread( 3097): Creating BTHandshakeSocketThread
I/BTListenerThread( 3097): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread started
,I/BTListenerThread( 3097): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3097): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3097): MESSAGE_WRITE 76 bytes.
I/HS      ( 3097): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT5340
,I/BtConnectorHelper( 3097): Starting the connected thread incoming : true, samsung-SM-A300FU_PT5340
I/BtToSocketBase( 3097): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3097): Creating BTConnectedThread
I/BtConnectorHelper( 3097): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3097): --DoOneRunRound started
,I/jxcore-log( 3097): 2015-11-24T16:11:34.189Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3097): 
,I/BtToRequestSocket( 3097): LocalHost address: localhost/127.0.0.1, port: 37245
I/BtToRequestSocket( 3097): --DoOneRunRound ended
,I/jxcore-log( 3097): 2015-11-24T16:11:34.573Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:34.667Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:34.739Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:34.839Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:34.872Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:35.093Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:35.198Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3097): 
,I/        ( 3097): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT5340, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT5340, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/jxcore-log( 3097): 2015-11-24T16:11:35.381Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:35.417Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:35.512Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:35.577Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:35.618Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:35.731Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:35.737Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:35.898Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:35.999Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:36.006Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:36.019Z SendDataTCPServer.js: TCP/IP server has received 32496 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:36.049Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:36.134Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:36.161Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:36.350Z SendDataTCPServer.js: TCP/IP server has received 44376 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:36.387Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:36.541Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:36.579Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:36.666Z SendDataTCPServer.js: TCP/IP server has received 54276 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:36.767Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:36.876Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:36.987Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:36.999Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.029Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.065Z SendDataTCPServer.js: TCP/IP server has received 66156 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.071Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.080Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.090Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.127Z SendDataTCPServer.js: TCP/IP server has received 76056 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.167Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.179Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.192Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.228Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:11:37.229Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.236Z SendDataTCPServer.js: TCP/IP server has received 83976 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.277Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.291Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.363Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.611Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.683Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:11:37.717Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3097): 
,W/bt-btif ( 3150): invalid rfc slot id: 8
,I/BtToSocketBase( 3097): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3097): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3097): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT5340
I/BtToSocketBase( 3097): Stop ReceivingThread
I/BtToSocketBase( 3097): Stop SendingThread
I/BtToSocketBase( 3097): Close local in
,I/BtToSocketBase( 3097): Close LocalOutputStream
I/BtToSocketBase( 3097): Close localHostSocket
I/BtToSocketBase( 3097): Close bt in
I/BtToSocketBase( 3097): Close bt out
I/BtToSocketBase( 3097): Close bt socket
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3097): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3097): 2015-11-24T16:11:38.029Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3097): 
,W/bt-rfcomm( 3150): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3150): RFCOMM_DisconnectInd LCID:0x49
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: A3-1
,I/jxcore-log( 3097): 2015-11-24T16:11:42.236Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:11:42.236Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:11:42.237Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:11:42.237Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3097): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant(  991): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3097): Found 4 peers.
I/SS      ( 3097): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(2): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3097): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3097): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6450"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6450"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT6450, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT6450, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3097): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3097): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3097): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3097): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3097): Found 5 peers.
I/SS      ( 3097): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3097): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3097): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3097): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3097): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x22  CID 0x4a
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 10
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:12:14.179Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:14.180Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:14.181Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT1910","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT1910","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT1910, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT1910, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/jxcore-log( 3097): 2015-11-24T16:12:19.182Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:19.183Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:12:24.188Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:24.188Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:24.189Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:24.190Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3097): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x9  CID 0x4b
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 11
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:12:25.069Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:25.070Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:25.070Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 8 peers.
I/SS      ( 3097): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3097): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3097): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3097): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3097): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3097): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3097): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3097): 2015-11-24T16:12:30.072Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:30.073Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3097): 2015-11-24T16:12:35.078Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:35.079Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:35.079Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:35.080Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3097): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x9  CID 0x4c
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 12
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:12:37.868Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:37.869Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:12:37.888Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:37.894Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- gotta redo : F8:95:C7:87:3C:51, try count now: 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:37.903Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:37.904Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:37.904Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3097): Connecting to null, at 58:2A:F7:ED:96:BE
I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 133269 ms, rnd: 5, ex: Connection to F8:95:C7:87:3C:51 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 3150): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3150): Entering PendingCommandState State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 3150): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3150): StableState(): Entering Off State
,E/BluetoothEventManager( 3193): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3150): new conn_srvc id:26, app_id:1
W/bt-btif ( 3150): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3150): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3097): Starting to Handshake
,I/BTHandshakeSocketThread( 3097): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3097): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread started
,I/BTConnectToThread( 3097): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3097): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT5583","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3097): HandshakeOk : HUAWEI-ALE-L21_PT5583
I/HS      ( 3097): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT5583
,I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3097): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT5583
I/BtToSocketBase( 3097): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3097): Creating BtConnectedRequestSocket
I/        ( 3097): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6662","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3097): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6662","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT6662, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT6662, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/BtToRequestSocket( 3097): mHTTPPort  set to : 54889
,I/BtConnectorHelper( 3097): Request socket is using : 54889
I/BtToRequestSocket( 3097): Now accepting connections
,I/BtConnectorHelper( 3097): Calling ConnectionStatusUpdate with port :54889
I/jxcore-log( 3097): 2015-11-24T16:12:41.687Z SendDataConnector.js: CLIENT connected to 54889, error: null
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:41.688Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3097): 
,I/BtToRequestSocket( 3097): incoming data from: /127.0.0.1, port: 54889
I/BtToRequestSocket( 3097): Set local streams
I/BtToRequestSocket( 3097): rin ended ---------------------------;
,I/jxcore-log( 3097): 2015-11-24T16:12:41.710Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3097): 
,D/        ( 3150): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3097): 2015-11-24T16:12:42.127Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:12:42.540Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3097): 
,D/        ( 3150): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3097): 2015-11-24T16:12:42.674Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:12:43.045Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3097): 
,D/        ( 3150): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3097): 2015-11-24T16:12:43.433Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:12:43.801Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:12:44.156Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:12:44.536Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3097): 
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3097): 2015-11-24T16:12:44.787Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:12:45.023Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:45.024Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:12:45.045Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:45.046Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3097): 
I/BtConnectorHelper( 3097): Disconnect outgoing peer: 58:2A:F7:ED:96:BE
I/BtToSocketBase( 3097): Stop ReceivingThread
I/BtToSocketBase( 3097): Stop SendingThread
I/BtToSocketBase( 3097): Close local in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3097): Close LocalOutputStream
I/BtToSocketBase( 3097): Close localHostSocket
,I/BtToSocketBase( 3097): Close bt in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3097): Close bt out
I/BtToSocketBase( 3097): Close bt socket
I/BtToRequestSocket( 3097): Close server socket
I/jxcore-log( 3097): 2015-11-24T16:12:45.071Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:45.074Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:12:45.075Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:12:45.080Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3097): Connecting to null, at 50:2E:6C:AC:21:50
,I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 7121 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c515dc rs_disc_pending=1
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 14
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:12:50.001Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:50.002Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:50.002Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 11 peers.
I/SS      ( 3097): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3097): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3097): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3097): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3097): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3097): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3097): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3097): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3097): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3097): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3097): 2015-11-24T16:12:55.003Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:12:55.004Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3097): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3097): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3097): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6662","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6662","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT6662, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT6662, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3097): 2015-11-24T16:13:00.008Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:00.009Z SendDataConnector.js: Connect (retry count 1) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:00.009Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:00.010Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3097): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 11 peers.
I/SS      ( 3097): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3097): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3097): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3097): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3097): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3097): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3097): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3097): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3097): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3097): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3150): invalid rfc slot id: 15
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:13:21.409Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:21.410Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:21.410Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:26.412Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:26.413Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:31.417Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:31.417Z SendDataConnector.js: Connect (retry count 2) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:31.418Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:31.418Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3097): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [50:2e:6c:ac:21:50]: 0, 0, 0
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 3150): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3150): Entering PendingCommandState State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 3150): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3150): StableState(): Entering Off State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c517a4 rs_disc_pending=1
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,W/bt-btif ( 3150): new conn_srvc id:26, app_id:255
W/bt-btif ( 3150): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3150): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3097): we got incoming connection
I/BTHandshakeSocketThread( 3097): Creating BTHandshakeSocketThread
I/BTListenerThread( 3097): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread started
,I/BTListenerThread( 3097): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3097): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3097): MESSAGE_WRITE 76 bytes.
I/HS      ( 3097): Incoming connection Hand Shake finished for : motorola-XT1039_PT1668
I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3097): Starting the connected thread incoming : true, motorola-XT1039_PT1668
I/BtToSocketBase( 3097): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3097): Creating BTConnectedThread
I/BtConnectorHelper( 3097): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3097): --DoOneRunRound started
,I/jxcore-log( 3097): 2015-11-24T16:13:33.893Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3097): 
,I/BtToRequestSocket( 3097): LocalHost address: localhost/127.0.0.1, port: 37245
I/BtToRequestSocket( 3097): --DoOneRunRound ended
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 3150): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3150): Entering PendingCommandState State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 3150): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3150): StableState(): Entering Off State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,W/bt-btif ( 3150): new conn_srvc id:26, app_id:1
W/bt-btif ( 3150): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3150): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3097): Starting to Handshake
I/BTHandshakeSocketThread( 3097): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3097): MESSAGE_WRITE 76 bytes.
I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread started
,I/BTConnectToThread( 3097): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3097): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3097): HandshakeOk : HTC-HTC One_M8_PT4451
I/HS      ( 3097): Hand Shake finished outgoing for : HTC-HTC One_M8_PT4451
I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3097): Starting the connected thread incoming : false, HTC-HTC One_M8_PT4451
I/BtToSocketBase( 3097): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3097): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3097): mHTTPPort  set to : 40272
I/BtConnectorHelper( 3097): Request socket is using : 40272
I/BtToRequestSocket( 3097): Now accepting connections
,I/jxcore-log( 3097): 2015-11-24T16:13:34.330Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.335Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.340Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.343Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.349Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.357Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.363Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.396Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.427Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.435Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.444Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.454Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.492Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3097): 
,I/BtConnectorHelper( 3097): Calling ConnectionStatusUpdate with port :40272
I/jxcore-log( 3097): 2015-11-24T16:13:34.622Z SendDataConnector.js: CLIENT connected to 40272, error: null
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:34.623Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3097): 
,I/BtToRequestSocket( 3097): incoming data from: /127.0.0.1, port: 40272
I/BtToRequestSocket( 3097): Set local streams
,I/BtToRequestSocket( 3097): rin ended ---------------------------;
,I/jxcore-log( 3097): 2015-11-24T16:13:34.656Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.670Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.733Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:34.766Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3097): 
,D/        ( 3150): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3097): 2015-11-24T16:13:34.864Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3097): 
,D/        ( 3150): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18767
,I/jxcore-log( 3097): 2015-11-24T16:13:34.916Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:35.009Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3097): 
,D/        ( 3150): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7877
,I/jxcore-log( 3097): 2015-11-24T16:13:35.081Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:35.175Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:35.247Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:35.283Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:35.329Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:35.337Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:35.418Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:35.419Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:35.435Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:35.435Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3097): 
I/BtConnectorHelper( 3097): Disconnect outgoing peer: 50:2E:6C:AC:21:50
I/BtToSocketBase( 3097): Stop ReceivingThread
I/BtToSocketBase( 3097): Stop SendingThread
I/BtToSocketBase( 3097): Close local in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3097): Close LocalOutputStream
I/BtToSocketBase( 3097): Close localHostSocket
I/BtToSocketBase( 3097): Close bt in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3097): Close bt out
I/BtToSocketBase( 3097): Close bt socket
I/BtToRequestSocket( 3097): Close server socket
,I/jxcore-log( 3097): 2015-11-24T16:13:35.459Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:35.464Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:35.472Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:35.472Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,W/bt-btif ( 3150): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/        ( 3097): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 50345 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3097): 2015-11-24T16:13:35.836Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:36.278Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:36.317Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:36.520Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3097): 
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [f8:95:c7:87:85:54]: 0, 0, 0
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3097): 2015-11-24T16:13:36.626Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:36.632Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3097): 
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,I/jxcore-log( 3097): 2015-11-24T16:13:36.973Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:36.980Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:37.200Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:37.208Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:37.212Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3097): 
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3150): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3150): Entering PendingCommandState State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3150): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3150): StableState(): Entering Off State
,I/jxcore-log( 3097): 2015-11-24T16:13:37.661Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3097): 
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/jxcore-log( 3097): 2015-11-24T16:13:37.696Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3097): 
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c50ebc rs_disc_pending=1
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3097): 2015-11-24T16:13:37.895Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3097): 
,W/bt-btif ( 3150): new conn_srvc id:26, app_id:1
W/bt-btif ( 3150): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3150): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3097): Starting to Handshake
,I/BTHandshakeSocketThread( 3097): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3097): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread started
,I/jxcore-log( 3097): 2015-11-24T16:13:38.233Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3097): 
,I/BTConnectToThread( 3097): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3097): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6211","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3097): HandshakeOk : LGE-LG-D722_PT6211
I/HS      ( 3097): Hand Shake finished outgoing for : LGE-LG-D722_PT6211
I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3097): Starting the connected thread incoming : false, LGE-LG-D722_PT6211
I/BtToSocketBase( 3097): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3097): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3097): mHTTPPort  set to : 56104
I/BtConnectorHelper( 3097): Request socket is using : 56104
I/BtToRequestSocket( 3097): Now accepting connections
,I/jxcore-log( 3097): 2015-11-24T16:13:38.325Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:38.334Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:38.407Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:38.427Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:38.438Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:38.468Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:38.538Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:38.547Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3097): 
,I/BtConnectorHelper( 3097): Calling ConnectionStatusUpdate with port :56104
,I/jxcore-log( 3097): 2015-11-24T16:13:38.625Z SendDataConnector.js: CLIENT connected to 56104, error: null
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:38.626Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3097): 
,I/BtToRequestSocket( 3097): incoming data from: /127.0.0.1, port: 56104
I/BtToRequestSocket( 3097): Set local streams
I/BtToRequestSocket( 3097): rin ended ---------------------------;
,I/jxcore-log( 3097): 2015-11-24T16:13:38.651Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:38.653Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:38.709Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3097): 
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: HTC One_M8
,I/jxcore-log( 3097): 2015-11-24T16:13:38.952Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:38.980Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:38.983Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:39.034Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:39.158Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:39.187Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:39.339Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:39.480Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3097): 
,W/bt-btif ( 3150): invalid rfc slot id: 9
,I/BtToSocketBase( 3097): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3097): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3097): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT1668
I/BtToSocketBase( 3097): Stop ReceivingThread
I/BtToSocketBase( 3097): Stop SendingThread
I/BtToSocketBase( 3097): Close local in
I/BtToSocketBase( 3097): Close LocalOutputStream
I/BtToSocketBase( 3097): Close localHostSocket
I/BtToSocketBase( 3097): Close bt in
I/BtToSocketBase( 3097): Close bt out
I/BtToSocketBase( 3097): Close bt socket
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3097): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3097): 2015-11-24T16:13:39.520Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:39.605Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3097): 
,W/bt-rfcomm( 3150): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 3150): RFCOMM_DisconnectInd LCID:0x45
,I/jxcore-log( 3097): 2015-11-24T16:13:40.011Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:40.132Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:40.167Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:40.167Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:40.183Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:40.183Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3097): 
,I/BtConnectorHelper( 3097): Disconnect outgoing peer: F8:95:C7:87:85:54
I/BtToSocketBase( 3097): Stop ReceivingThread
I/BtToSocketBase( 3097): Stop SendingThread
I/BtToSocketBase( 3097): Close local in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3097): Close LocalOutputStream
I/BtToSocketBase( 3097): Close localHostSocket
I/BtToSocketBase( 3097): Close bt in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3097): Close bt out
I/BtToSocketBase( 3097): Close bt socket
I/BtToRequestSocket( 3097): Close server socket
,I/jxcore-log( 3097): 2015-11-24T16:13:40.215Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:40.221Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:40.222Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:40.222Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3097): Connecting to null, at 80:01:84:8A:B3:68
I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 4696 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c51b34 rs_disc_pending=1
,W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 19
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:13:42.648Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:42.649Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:42.650Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: XT1039
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: G3s-1
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3097): 2015-11-24T16:13:47.650Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:47.651Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:13:52.657Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:52.658Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:52.659Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:52.660Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3097): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 20
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:13:53.602Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:53.602Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:53.603Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/ActivityManager(  757): Killing 2907:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10008/pid_2907/cgroup.procs: No such file or directory
,I/jxcore-log( 3097): 2015-11-24T16:13:58.604Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:13:58.604Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,E/bt-btif ( 3150): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3150): Entering PendingCommandState State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 3150): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3150): StableState(): Entering Off State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,W/bt-btif ( 3150): new conn_srvc id:26, app_id:255
W/bt-btif ( 3150): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3150): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3097): we got incoming connection
I/BTHandshakeSocketThread( 3097): Creating BTHandshakeSocketThread
I/BTListenerThread( 3097): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread started
,I/BTListenerThread( 3097): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3097): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3097): MESSAGE_WRITE 76 bytes.
I/HS      ( 3097): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT2521
I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3097): Starting the connected thread incoming : true, samsung-SM-A300FU_PT2521
I/BtToSocketBase( 3097): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3097): Creating BTConnectedThread
I/BtConnectorHelper( 3097): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3097): --DoOneRunRound started
,I/BtToRequestSocket( 3097): LocalHost address: localhost/127.0.0.1, port: 37245
I/BtToRequestSocket( 3097): --DoOneRunRound ended
,I/jxcore-log( 3097): 2015-11-24T16:14:01.533Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:01.920Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:01.935Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:01.944Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:01.952Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:01.965Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:01.970Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.020Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.034Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.040Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.052Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.087Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.119Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.125Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.169Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.182Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.219Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.236Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.248Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.277Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.320Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.368Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.378Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.385Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.391Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.439Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.453Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.488Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.500Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.509Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.519Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.559Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.566Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.572Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.582Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.591Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.639Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.648Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.660Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:02.700Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3097): 
,W/bt-btif ( 3150): invalid rfc slot id: 17
,I/BtToSocketBase( 3097): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3097): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3097): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT2521
I/BtToSocketBase( 3097): Stop ReceivingThread
I/BtToSocketBase( 3097): Stop SendingThread
I/BtToSocketBase( 3097): Close local in
I/BtToSocketBase( 3097): Close LocalOutputStream
I/BtToSocketBase( 3097): Close localHostSocket
I/BtToSocketBase( 3097): Close bt in
I/BtToSocketBase( 3097): Close bt out
I/BtToSocketBase( 3097): Close bt socket
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3097): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3097): 2015-11-24T16:14:02.784Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3097): 
,W/bt-rfcomm( 3150): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3150): RFCOMM_DisconnectInd LCID:0x4c
,I/jxcore-log( 3097): 2015-11-24T16:14:03.609Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:03.610Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:03.610Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:03.611Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3097): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c51cfc rs_disc_pending=1
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 22
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c51cfc rs_disc_pending=1
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3097): 2015-11-24T16:14:05.731Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:05.732Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:05.732Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c51b34 rs_disc_pending=1
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14),
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c51cfc rs_disc_pending=0
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c51b34 rs_disc_pending=0
E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/jxcore-log( 3097): 2015-11-24T16:14:10.732Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:10.733Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 4 peers.
I/SS      ( 3097): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3097): Peer(3): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3097): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3097): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3097): 2015-11-24T16:14:15.737Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:15.738Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:15.739Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:15.739Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3097): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3097): Starting to connect
,W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 23
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:14:16.643Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:16.643Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:16.651Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3097): 2015-11-24T16:14:21.652Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:21.661Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:26.665Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:26.665Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:26.666Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:26.666Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3097): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 24
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:14:26.917Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:26.918Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:26.934Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:26.940Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:26.943Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:26.944Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:26.944Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3097): Connecting to null, at 34:FC:EF:11:B1:66
I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 46696 ms, rnd: 5, ex: Connection to 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 25
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:14:27.722Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:27.722Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:27.723Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c51b34 rs_disc_pending=0
E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3097): 2015-11-24T16:14:32.727Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:32.729Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3097): 2015-11-24T16:14:37.737Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:37.738Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:37.738Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:37.739Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3097): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [34:fc:ef:11:b1:66]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 26
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:14:38.481Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:38.482Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:38.482Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c51ec4 rs_disc_pending=0
E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3097): 2015-11-24T16:14:43.483Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:43.484Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:14:48.489Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:48.490Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:48.490Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:14:48.491Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3097): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 4 peers.
I/SS      ( 3097): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3097): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3097): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(4): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3097): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3097): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT4262, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT4262, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 6 peers.
I/SS      ( 3097): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3097): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3097): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3097): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3097): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3097): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x8  CID 0x43
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 27
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:15:40.463Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:15:40.464Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:15:40.464Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/jxcore-log( 3097): 2015-11-24T16:15:45.465Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:15:45.466Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:15:50.469Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:15:50.469Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:15:50.470Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:15:50.470Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3097): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 5 peers.
I/SS      ( 3097): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3097): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 3097): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3097): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x8  CID 0x41
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 28
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:16:46.249Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:16:46.250Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:16:46.251Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:16:51.252Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:16:51.253Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3097): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3097): 2015-11-24T16:16:56.257Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:16:56.257Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:16:56.258Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:16:56.258Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3097): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 29
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:16:57.479Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:16:57.480Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:16:57.497Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:16:57.500Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:16:57.503Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:16:57.503Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:16:57.504Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3097): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 150538 ms, rnd: 5, ex: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Cleared service requests
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 5 peers.
I/SS      ( 3097): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3097): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(5): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3097): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5708","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5708","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT5708, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT5708, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 3097): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3097): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3097): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4262","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT4262, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT4262, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 9 peers.
I/SS      ( 3097): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3097): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3097): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3097): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3097): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(9): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3097): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x1f  CID 0x46
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 30
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:17:26.629Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:17:26.630Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:17:26.630Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3097): 2015-11-24T16:17:31.632Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:17:31.633Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:17:36.637Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:17:36.638Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:17:36.638Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:17:36.639Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3097): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x8  CID 0x47
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 31
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:18:10.404Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:10.408Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:10.409Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:15.410Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:15.410Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:20.414Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:20.415Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:20.420Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:20.422Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3097): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 32
I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:18:25.593Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:25.593Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:25.594Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/        ( 3097): Cleared service requests
,I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 10 peers.
I/SS      ( 3097): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3097): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3097): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3097): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3097): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3097): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(10): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3097): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3097): 2015-11-24T16:18:30.595Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:30.597Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
,I/        ( 3097): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3097): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3097): 2015-11-24T16:18:35.601Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:35.602Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:35.602Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:35.603Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3097): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [08:ec:a9:50:75:41]: 6, f, 6109
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: A3-1
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,W/bt-btif ( 3150): new conn_srvc id:26, app_id:1
W/bt-btif ( 3150): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3150): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3097): Starting to Handshake
I/BTHandshakeSocketThread( 3097): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3097): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread started
,I/BTConnectToThread( 3097): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3097): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5340","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3097): HandshakeOk : samsung-SM-A300FU_PT5340
I/HS      ( 3097): Hand Shake finished outgoing for : samsung-SM-A300FU_PT5340
I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3097): Starting the connected thread incoming : false, samsung-SM-A300FU_PT5340
I/BtToSocketBase( 3097): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3097): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3097): mHTTPPort  set to : 47272
I/BtConnectorHelper( 3097): Request socket is using : 47272
I/BtToRequestSocket( 3097): Now accepting connections
,I/BtConnectorHelper( 3097): Calling ConnectionStatusUpdate with port :47272
I/jxcore-log( 3097): 2015-11-24T16:18:40.619Z SendDataConnector.js: CLIENT connected to 47272, error: null
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:40.620Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3097): 
,I/BtToRequestSocket( 3097): incoming data from: /127.0.0.1, port: 47272
I/BtToRequestSocket( 3097): Set local streams
I/BtToRequestSocket( 3097): rin ended ---------------------------;
,I/jxcore-log( 3097): 2015-11-24T16:18:40.641Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3097): 
,D/        ( 3150): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3097): 2015-11-24T16:18:41.037Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:41.198Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3097): 
,D/        ( 3150): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3097): 2015-11-24T16:18:41.345Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:41.457Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3097): 
,D/        ( 3150): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3097): 2015-11-24T16:18:41.673Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:41.757Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:41.841Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:41.975Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:41.981Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:42.197Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:42.198Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:42.213Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:42.214Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3097): 
,I/BtConnectorHelper( 3097): Disconnect outgoing peer: 08:EC:A9:50:75:41
I/BtToSocketBase( 3097): Stop ReceivingThread
I/BtToSocketBase( 3097): Stop SendingThread
I/BtToSocketBase( 3097): Close local in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3097): Close LocalOutputStream
,I/BtToSocketBase( 3097): Close localHostSocket
I/BtToSocketBase( 3097): Close bt in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3097): Close bt out
I/BtToSocketBase( 3097): Close bt socket
I/BtToRequestSocket( 3097): Close server socket
,I/jxcore-log( 3097): 2015-11-24T16:18:42.252Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:42.254Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:42.254Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:42.254Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3097): Connecting to null, at E0:DB:10:14:E2:C0
I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 104695 ms, rnd: 4, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/SS      ( 3097): Found 3 peers.
I/SS      ( 3097): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3097): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3097): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3097): Added service request
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c51084 rs_disc_pending=0
E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: A3-1
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 34
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:18:47.401Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:47.402Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:47.403Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/        ( 3097): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3097): 2015-11-24T16:18:52.404Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:52.405Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:18:57.413Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:57.413Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:57.414Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:18:57.414Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3097): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 35
I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:19:02.586Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:02.586Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:02.586Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 3 peers.
I/SS      ( 3097): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3097): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3097): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3097): 2015-11-24T16:19:07.586Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:07.587Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:19:12.591Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:12.592Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:12.592Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:12.593Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3097): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 36
I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:19:17.767Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:17.767Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:17.768Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 5 peers.
I/SS      ( 3097): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3097): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3097): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3097): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3097): 2015-11-24T16:19:22.768Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:22.769Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:19:27.772Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:27.773Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:27.773Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:27.774Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3097): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 37
I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:19:32.951Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:32.951Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:32.951Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:19:37.953Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:37.953Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
,I/EventLogService( 1648): Aggregate from 1448379901168 (log), 1448379901168 (data)
,I/jxcore-log( 3097): 2015-11-24T16:19:42.957Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:42.958Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:42.958Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:42.959Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3097): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 38
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:19:48.147Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:48.148Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:19:48.163Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:19:48.169Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:48.172Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:48.173Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:48.173Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 3097): Connecting to null, at 7C:F9:0E:37:96:AB
,I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 65894 ms, rnd: 5, ex: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 39
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:19:53.086Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:53.087Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:53.087Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3097): 2015-11-24T16:19:58.088Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:19:58.089Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:20:03.090Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:03.090Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:03.090Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:03.090Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 3097): Connecting to null, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 40
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:20:03.309Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:20:03.310Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:03.310Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3097): 2015-11-24T16:20:08.310Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:08.310Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:20:13.311Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:13.311Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:13.311Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:13.311Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 3097): Connecting to null, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 41
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:20:14.850Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:14.851Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:14.852Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3097): 2015-11-24T16:20:19.853Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:19.854Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 5 peers.
I/SS      ( 3097): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3097): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3097): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3097): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3097): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3097): 2015-11-24T16:20:24.858Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:24.859Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:24.859Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:24.860Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 3097): Connecting to null, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 42
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:20:25.088Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:25.089Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:25.089Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/        ( 3097): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3097): 2015-11-24T16:20:30.090Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:30.090Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:20:35.090Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:35.091Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:35.091Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:35.091Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 3097): Connecting to null, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 43
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:20:35.316Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:35.317Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:20:35.333Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:20:35.341Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:35.344Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:35.344Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:20:35.350Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3097): Connecting to null, at 00:F4:6F:30:E0:6C
I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 47144 ms, rnd: 5, ex: Connection to 7C:F9:0E:37:96:AB failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 44
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:20:36.609Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:36.610Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:36.610Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/        ( 3097): Cleared service requests
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3097): Found 7 peers.
I/SS      ( 3097): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3097): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3097): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(6): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3097): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3097): Started service discovery
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3097): 2015-11-24T16:20:41.612Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:20:41.612Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/        ( 3097): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3097): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3097): 2015-11-24T16:20:46.634Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:46.634Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:20:46.635Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:20:46.638Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3097): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 45
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:20:47.258Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:47.259Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:47.260Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3097): 2015-11-24T16:20:52.261Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:52.261Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
,I/        ( 3097): Cleared service requests
,I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3097): 2015-11-24T16:20:57.265Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:57.267Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:57.268Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:57.268Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3097): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 7 peers.
I/SS      ( 3097): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3097): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3097): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3097): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 46
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:20:59.993Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:59.993Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:20:59.994Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3097): 2015-11-24T16:21:04.996Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:04.997Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
,I/        ( 3097): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1668"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1668, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1668, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3097): 2015-11-24T16:21:10.001Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:10.002Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:10.003Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:10.003Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3097): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 47
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:21:10.783Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:10.784Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:10.784Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3097): 2015-11-24T16:21:15.785Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:15.786Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 7 peers.
I/SS      ( 3097): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3097): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3097): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3097): 2015-11-24T16:21:20.790Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:20.791Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:20.791Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:20.792Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3097): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3097): Started service discovery
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 48
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:21:21.894Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:21.894Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:21:21.913Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:21:21.918Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:21.922Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:21.922Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:21.923Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3097): Connecting to null, at 44:80:EB:7B:5A:05
I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 46551 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
,W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 49
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:21:23.871Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:23.871Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:23.872Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3097): 2015-11-24T16:21:28.873Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:28.874Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:21:33.879Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:33.880Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:33.880Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:33.881Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3097): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [44:80:eb:7b:5a:05]: 6, f, 410d
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 50
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:21:35.344Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:35.344Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:21:35.349Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3097): 2015-11-24T16:21:40.360Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:40.360Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/jxcore-log( 3097): 2015-11-24T16:21:45.365Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:45.365Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:45.366Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:45.366Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3097): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 51
I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:21:45.552Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:45.553Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:45.553Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3097): 2015-11-24T16:21:50.553Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:50.553Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:21:55.556Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:55.556Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:55.556Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:55.558Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3097): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 52
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:21:55.856Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:55.857Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:21:55.857Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3097): 2015-11-24T16:22:00.858Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:00.859Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:05.860Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:05.860Z SendDataConnector.js: Connect (retry count 4) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:05.860Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:05.860Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3097): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 53
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:22:06.194Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:06.194Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:06.221Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:06.224Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:06.242Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:06.243Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:06.244Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3097): Connecting to null, at 34:FC:EF:9D:93:0B
I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 44280 ms, rnd: 5, ex: Connection to 44:80:EB:7B:5A:05 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3150): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3150): Entering PendingCommandState State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3150): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3150): StableState(): Entering Off State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 3150): new conn_srvc id:26, app_id:1
I/BTConnectToThread( 3097): Starting to Handshake
I/BTHandshakeSocketThread( 3097): Creating BTHandshakeSocketThread
W/bt-btif ( 3150): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3150): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3097): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread started
,I/BTConnectToThread( 3097): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3097): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3097): HandshakeOk : LGE-LG-D802_PT2047
I/HS      ( 3097): Hand Shake finished outgoing for : LGE-LG-D802_PT2047
I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3097): Starting the connected thread incoming : false, LGE-LG-D802_PT2047
I/BtToSocketBase( 3097): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3097): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3097): mHTTPPort  set to : 51825
I/BtConnectorHelper( 3097): Request socket is using : 51825
I/BtToRequestSocket( 3097): Now accepting connections
,I/BtConnectorHelper( 3097): Calling ConnectionStatusUpdate with port :51825
I/jxcore-log( 3097): 2015-11-24T16:22:07.934Z SendDataConnector.js: CLIENT connected to 51825, error: null
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:07.934Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3097): 
,I/BtToRequestSocket( 3097): incoming data from: /127.0.0.1, port: 51825
I/BtToRequestSocket( 3097): Set local streams
I/BtToRequestSocket( 3097): rin ended ---------------------------;
,I/jxcore-log( 3097): 2015-11-24T16:22:07.957Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:08.190Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:08.334Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:08.441Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:08.600Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:08.791Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:08.971Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:09.073Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:09.159Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:09.329Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:09.330Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:09.347Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:09.348Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3097): 
I/BtConnectorHelper( 3097): Disconnect outgoing peer: 34:FC:EF:9D:93:0B
I/BtToSocketBase( 3097): Stop ReceivingThread
I/BtToSocketBase( 3097): Stop SendingThread
I/BtToSocketBase( 3097): Close local in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3097): Close LocalOutputStream
,I/BtToSocketBase( 3097): Close localHostSocket
I/BtToSocketBase( 3097): Close bt in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3097): Close bt out
I/BtToSocketBase( 3097): Close bt socket
I/BtToRequestSocket( 3097): Close server socket
,I/jxcore-log( 3097): 2015-11-24T16:22:09.378Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:09.381Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:09.382Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:09.382Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 3097): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 3088 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 55
I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:22:12.515Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:12.515Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:12.515Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c527ac rs_disc_pending=0
E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: Thali Test's G2
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c5196c rs_disc_pending=0
E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: XT1039
,I/jxcore-log( 3097): 2015-11-24T16:22:17.516Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:17.516Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 4 peers.
I/SS      ( 3097): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(4): G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3097): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3097): 2015-11-24T16:22:22.528Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:22.528Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:22.528Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:22.529Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 3097): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 56
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:22:27.674Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:27.678Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:27.681Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): tBTM_SEC_DEV:0xa3c5196c rs_disc_pending=0
E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3150): bta_dm_check_av:0
,W/bt-btif ( 3150): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: XT1039
,I/jxcore-log( 3097): 2015-11-24T16:22:32.684Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:32.689Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3097): 2015-11-24T16:22:37.697Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:37.698Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:37.699Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:37.699Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 3097): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 57
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:22:42.883Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:42.883Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:42.883Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3097): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3097): 2015-11-24T16:22:47.884Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:47.888Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:22:52.892Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:52.892Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:52.893Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:52.893Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 3097): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 58
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:22:58.069Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:58.069Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:22:58.069Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3097): Found 6 peers.
I/SS      ( 3097): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3097): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3097): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(4): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3097): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3097): 2015-11-24T16:23:03.070Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:03.071Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:23:08.074Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:08.077Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:08.077Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:08.078Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 3097): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 59
I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:23:13.252Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:13.253Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:23:13.254Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:23:13.257Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- gotta redo : F4:F1:E1:5C:3B:E2, try count now: 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:13.257Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:13.257Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:13.257Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3097): Connecting to null, at E0:DB:10:1F:C9:5E
I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 63871 ms, rnd: 5, ex: Connection to F4:F1:E1:5C:3B:E2 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 60
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:23:18.402Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:18.403Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:18.404Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:23:23.406Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:23.406Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:23:28.410Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:28.411Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:28.411Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:28.412Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3097): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 61
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:23:33.599Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:33.600Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:33.600Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/UsageStatsService(  757): User[0] Flushing usage stats to disk
,I/jxcore-log( 3097): 2015-11-24T16:23:38.602Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:38.603Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:23:43.606Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:43.607Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:43.608Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:43.608Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3097): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 62
I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:23:48.781Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:48.781Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:48.781Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:23:53.782Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:53.783Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3097): 2015-11-24T16:23:58.787Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:58.788Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:58.789Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:23:58.789Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3097): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     (  757): Explicit concurrent mark sweep GC freed 52275(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/42MB, paused 1.058ms total 76.686ms
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 8 peers.
I/SS      ( 3097): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3097): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3097): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3097): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3097): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 63
I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:24:04.034Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:24:04.034Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:24:04.035Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/        ( 3097): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3097): 2015-11-24T16:24:09.034Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:24:09.037Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/jxcore-log( 3097): 2015-11-24T16:24:14.041Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:24:14.041Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:24:14.042Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:24:14.042Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3097): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 5 peers.
I/SS      ( 3097): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3097): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3097): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 64
I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:24:19.214Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:24:19.214Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:24:19.216Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:24:19.218Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- gotta redo : E0:DB:10:1F:C9:5E, try count now: 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:24:19.218Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:24:19.218Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:24:19.219Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 3097): Connecting to null, at 58:3F:54:73:64:C0
I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 65957 ms, rnd: 5, ex: Connection to E0:DB:10:1F:C9:5E failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x8  CID 0x4c
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 65
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:24:50.265Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:24:50.268Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:24:50.269Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:24:55.270Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:24:55.271Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:25:00.275Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:25:00.277Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:25:00.278Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:25:00.278Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 3097): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 66
I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:25:05.449Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:25:05.449Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:25:05.449Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:25:10.449Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:25:10.450Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:25:15.453Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:25:15.454Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:25:15.454Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:25:15.455Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 3097): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 6 peers.
I/SS      ( 3097): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3097): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3097): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3097): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3097): Added service request
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x8  CID 0x4e
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 67
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:25:46.230Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:25:46.230Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:25:46.231Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:25:51.231Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:25:51.232Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:25:56.237Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:25:56.238Z SendDataConnector.js: Connect (retry count 3) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:25:56.238Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:25:56.239Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 3097): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 68
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:26:01.411Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:01.411Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:01.412Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:26:06.412Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:06.413Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:26:11.418Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:11.419Z SendDataConnector.js: Connect (retry count 4) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:11.419Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:11.420Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 3097): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3097): Cleared service requests
,I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 3 peers.
I/SS      ( 3097): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3097): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3097): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3097): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x8  CID 0x42
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 69
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3097): 2015-11-24T16:26:42.568Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:42.568Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:26:42.584Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:42.587Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- gotta redo : 58:3F:54:73:64:C0, try count now: 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:42.590Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:42.590Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:42.591Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 3097): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 143351 ms, rnd: 5, ex: Connection to 58:3F:54:73:64:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3150): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 6 peers.
I/SS      ( 3097): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3097): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3097): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3097): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3097): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3097): Added service request
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 3150): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3150): Entering PendingCommandState State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3150): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 3150): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3150): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3150): StableState(): Entering Off State
,W/BluetoothEventManager( 3193): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3193): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3097): Started service discovery
,W/bt-btif ( 3150): new conn_srvc id:26, app_id:1
W/bt-btif ( 3150): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3150): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3097): Starting to Handshake
,I/BTHandshakeSocketThread( 3097): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3097): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread started
,I/BTConnectToThread( 3097): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3097): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3097): HandshakeOk : samsung-SM-G900F_PT2346
I/HS      ( 3097): Hand Shake finished outgoing for : samsung-SM-G900F_PT2346
I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3097): Starting the connected thread incoming : false, samsung-SM-G900F_PT2346
,I/BtToSocketBase( 3097): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3097): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3097): mHTTPPort  set to : 59011
I/BtConnectorHelper( 3097): Request socket is using : 59011
I/BtToRequestSocket( 3097): Now accepting connections
,I/BtConnectorHelper( 3097): Calling ConnectionStatusUpdate with port :59011
I/jxcore-log( 3097): 2015-11-24T16:26:45.838Z SendDataConnector.js: CLIENT connected to 59011, error: null
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:45.839Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3097): 
,I/BtToRequestSocket( 3097): incoming data from: /127.0.0.1, port: 59011
I/BtToRequestSocket( 3097): Set local streams
I/BtToRequestSocket( 3097): rin ended ---------------------------;
,I/jxcore-log( 3097): 2015-11-24T16:26:45.881Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:26:46.487Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:26:46.765Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:26:47.065Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:26:47.139Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:26:47.424Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:26:47.658Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:26:47.853Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:26:48.160Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:26:48.175Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:26:48.235Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:48.236Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:26:48.253Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:48.254Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3097): 
,I/BtConnectorHelper( 3097): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 3097): Stop ReceivingThread
I/BtToSocketBase( 3097): Stop SendingThread
I/BtToSocketBase( 3097): Close local in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3097): Close LocalOutputStream
,I/BtToSocketBase( 3097): Close localHostSocket
I/BtToSocketBase( 3097): Close bt in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3097): Close bt out
I/BtToSocketBase( 3097): Close bt socket
,I/BtToRequestSocket( 3097): Close server socket
I/jxcore-log( 3097): 2015-11-24T16:26:48.300Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ---- round done--------
I/jxcore-log( 3097): 
I/jxcore-log( 3097): do fake peer & start
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:48.301Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:48.301Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:26:48.301Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3097): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback round[0] time: 5646 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: S5-1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3097): timeout now
I/jxcore-log( 3097): 
I/jxcore-log( 3097): dun
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): weAreDoneNow , resultArray.length: 6
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): done, now sending data to server
I/jxcore-log( 3097): 
I/jxcore-log( 3097): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): -- RESULT DATA {"name:":"LGE-Nexus 5_PT474","time":1000136,"result":"TIMEOUT","sendList":[{"name":"58:2A:F7:ED:96:BE","time":7121,"result":"OK","connections":1,"tryCount":1},{"name":"50:2E:6C:AC:21:50","time":50345,"result":"OK","connections":3,"tryCount":1},{"name":"F8:95:C7:87:85:54","time":4696,"result":"OK","connections":1,"tryCount":1},{"name":"08:EC:A9:50:75:41","time":104695,"result":"OK","connections":4,"tryCount":1},{"name":"34:FC:EF:9D:93:0B","time":3088,"result":"OK","connections":1,"tryCount":1},{"name":"7C:F9:0E:34:8A:A0","time":5646,"result":"OK","connections":1,"tryCount":1},{"connections":1,"name":"F8:CF:C5:D9:E5:61","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":1,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":1,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":1,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"conn
,I/jxcore-log( 3097): sendList : 100% : 104695 ms, 99% : 104695 ms, 95 : 104695 ms, 90% : 50345 ms.
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Result count 6, range 3088 ms to  104695 ms.
I/jxcore-log( 3097): 
I/jxcore-log( 3097): sendList failed peers count : 11 [64.70588235294117 %]
I/jxcore-log( 3097): 
I/jxcore-log( 3097): - Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): - Peer ID : F8:95:C7:87:3C:51, Tried : 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): - Peer ID : 80:01:84:8A:B3:68, Tried : 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): - Peer ID : E0:DB:10:14:E2:C0, Tried : 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): - Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): - Peer ID : 44:80:EB:7B:5A:05, Tried : 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): - Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): - Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): - Peer ID : 58:3F:54:73:64:C0, Tried : 1
I/jxcore-log( 3097): 
I/jxcore-log( 3097): sendList never tried peers count : 2 [10.526315789473685 %]
I/jxcore-log( 3097): 
I/jxcore-log( 3097): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3097): 
I/jxcore-log( 3097): - Peer ID : 08:EC:A9:50:76:27
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:27:04.736Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:27:04.737Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3097): 
,I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3097): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED ,
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 8 peers.
I/SS      ( 3097): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3097): Peer(6): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3097): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3097): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3097): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3150): SDP - Rcvd conn cnf with error: 0x8  CID 0x41
E/bt-btif ( 3150): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3150): invalid rfc slot id: 71
,I/BTConnectToThread( 3097): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3097): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3097): 2015-11-24T16:27:40.073Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:27:40.074Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:27:40.074Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3097): 
,I/        ( 3097): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2521","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2521, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2521, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3097): 2015-11-24T16:27:45.075Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:27:45.076Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/jxcore-log( 3097): 2015-11-24T16:27:50.080Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:27:50.080Z SendDataConnector.js: Connect (retry count 1) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:27:50.081Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:27:50.081Z SendDataConnector.js: do connect now
I/jxcore-log( 3097): 
,I/        ( 3097): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3097): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 3097): Starting to connect
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3150): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3150): info:x10
,D/        ( 3150): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 610c
,W/bt-sdp  ( 3150): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: Nexus 6
,W/bt-btif ( 3150): new conn_srvc id:26, app_id:1
W/bt-btif ( 3150): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3150): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3097): Starting to Handshake
I/BTHandshakeSocketThread( 3097): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3097): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread started
,I/BTConnectToThread( 3097): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3097): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5708","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3097): HandshakeOk : motorola-Nexus 6_PT5708
I/HS      ( 3097): Hand Shake finished outgoing for : motorola-Nexus 6_PT5708
,I/BtConnectorHelper( 3097): Starting the connected thread incoming : false, motorola-Nexus 6_PT5708
I/BtToSocketBase( 3097): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3097): Creating BtConnectedRequestSocket
I/BTHandshakeSocketThread( 3097): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3097): mHTTPPort  set to : 44228
I/BtConnectorHelper( 3097): Request socket is using : 44228
I/BtToRequestSocket( 3097): Now accepting connections
,I/BtConnectorHelper( 3097): Calling ConnectionStatusUpdate with port :44228
I/jxcore-log( 3097): 2015-11-24T16:27:51.312Z SendDataConnector.js: CLIENT connected to 44228, error: null
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:27:51.312Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3097): 
,I/BtToRequestSocket( 3097): incoming data from: /127.0.0.1, port: 44228
I/BtToRequestSocket( 3097): Set local streams
I/BtToRequestSocket( 3097): rin ended ---------------------------;
,I/jxcore-log( 3097): 2015-11-24T16:27:51.334Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3097): 
,D/        ( 3150): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3097): 2015-11-24T16:27:51.466Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3097): 
,D/        ( 3150): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16787
,I/jxcore-log( 3097): 2015-11-24T16:27:51.500Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3097): 
,D/        ( 3150): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3097): 2015-11-24T16:27:51.504Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:27:51.561Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3097): 
,D/        ( 3150): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1937
,I/jxcore-log( 3097): 2015-11-24T16:27:51.591Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:27:51.595Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:27:51.644Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:27:51.654Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3097): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3097): 2015-11-24T16:27:51.717Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:27:51.742Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:27:51.743Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:27:51.744Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3097): 
I/jxcore-log( 3097): 2015-11-24T16:27:51.744Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3097): 
,I/BtConnectorHelper( 3097): Disconnect outgoing peer: F8:CF:C5:D9:E5:61
I/BtToSocketBase( 3097): Stop ReceivingThread
I/BtToSocketBase( 3097): Stop SendingThread
I/BtToSocketBase( 3097): Close local in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3097): Close LocalOutputStream
I/BtToSocketBase( 3097): Close localHostSocket
I/BtToSocketBase( 3097): Close bt in
,I/BtToSocketBase( 3097): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3097): Close bt out
I/BtToSocketBase( 3097): Close bt socket
I/BtToRequestSocket( 3097): Close server socket
I/jxcore-log( 3097): 2015-11-24T16:27:51.773Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3097): 
,W/bt-btif ( 3150): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 6 peers.
I/SS      ( 3097): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3097): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3150): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3150): onReceive
,I/BTConnectionReceiver( 1438): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1438): Bluetooth Device Name: Nexus 6
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3097): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3097): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 7 peers.
I/SS      ( 3097): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3097): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3097): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 6 peers.
I/SS      ( 3097): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3097): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3097): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3097): Started service discovery
,I/        ( 3097): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 5 peers.,
I/SS      ( 3097): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3097): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3097): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3097): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3097): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3097): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3097): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3097): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3097): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 8 peers.
I/SS      ( 3097): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3097): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3097): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3097): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3097): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3097): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3097): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5708","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5708","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT5708, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT5708, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 3097): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT2047"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT2047, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT2047, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3097): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3097): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7587","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7587, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7587, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3097): Found 9 peers.
I/SS      ( 3097): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3097): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3097): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3097): Peer(8): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3097): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3097): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,W/bt-smp  ( 3150): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3150): Plain text(LSB ~ MSB) = 04 74 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3150): Encrypted text(LSB ~ MSB) = d6 d0 b7 16 4a a2 f4 dc 94 f4 14 49 37 4c ea 49 
,W/bt-btm  ( 3150): Stopping oneshot timer
,I/        ( 3097): Cleared service requests
I/        ( 3097): Started peer discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3097): Found 7 peers.
I/SS      ( 3097): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3097): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3097): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3097): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3097): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3097): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3097): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3097): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3097): Added service request
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Started service discovery
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3097): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6302","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6302, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6302, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3097): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6452"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6452, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6452, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3097): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4451","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4451, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4451, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3097): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3097): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2346","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2346, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3097): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2346, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3097): DBG, CoordinatorConnector command called
I/jxcore-log( 3097): 
I/jxcore-log( 3097): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): stop tests now !
I/jxcore-log( 3097): 
I/jxcore-log( 3097): stop current!
I/jxcore-log( 3097): 
I/jxcore-log( 3097): testSendData stopped
I/jxcore-log( 3097): 
I/        ( 3097): Stoping All
I/        ( 3097): Stopping services
I/        ( 3097): Stopping services
,I/        ( 3097): Stop Bluetooth
I/        ( 3097): Stop Bluetooth
I/BTListenerThread( 3097): Stopped
,I/jxcore-log( 3097): StopBroadcasting went ok
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): 2015-11-24T16:31:24.515Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3097): 
,I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3097): DBG, CoordinatorConnector command called
I/jxcore-log( 3097): 
I/jxcore-log( 3097): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"34:FC:EF:9D:93:0B\",\"time\":3088,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F8:95:C7:87:85:54\",\"time\":4696,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":5646,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"58:2A:F7:ED:96:BE\",\"time\":7121,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"50:2E:6C:AC:21:50\",\"time\":50345,\"result\":\"OK\",\"connections\":3,\"tryCount\":1},{\"name\":\"08:EC:A9:50:75:41\",\"time\":104695,\"result\":\"OK\",\"connections\":4,\"tryCount\":1}],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"F8:CF:C5:D9:E5:61\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"F8:95:C7:87:3C:51\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"80:01:84:8A:B3:68\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:11:B1:66\",\"time\"
I/jxcore-log( 3097): ****TEST TOOK:  ms ****
I/jxcore-log( 3097): 
I/jxcore-log( 3097): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3097): 
I/jxcore-log( 3097): stop tests now !
I/jxcore-log( 3097): 
I/jxcore-log( 3097): end, event received
I/jxcore-log( 3097): 
I/jxcore-log( 3097): CoordinatorConnector close called
I/jxcore-log( 3097): 
,I/jxcore-log( 3097): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3097): 
I/jxcore-log( 3097): The Coordinator has disconnected!
I/jxcore-log( 3097): 
I/jxcore-log( 3097): The Coordinator has closed!
I/jxcore-log( 3097): 
I/jxcore-log( 3097): stop tests now !
I/jxcore-log( 3097): 
I/jxcore-log( 3097): turning Radios off
I/jxcore-log( 3097): 
I/jxcore-log( 3097): Toggling radios to false
I/jxcore-log( 3097): 
D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  757): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@162e781e mBinding = false
,D/BluetoothManagerService(  757): Message: 2
,D/WifiService(  757): setWifiEnabled: false pid=3097, uid=10270
E/WifiService(  757): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothManagerService(  757): Sending off request.
,D/BluetoothAdapterState( 3150): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3150): Setting state to 13
I/BluetoothAdapterState( 3150): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3150): onBluetoothDisable()
I/BluetoothAdapterState( 3150): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3150): Scan Mode:20
,D/BluetoothAdapterState( 3150): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 3150): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3150): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3150): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3150): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3150): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3150): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3150): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3150): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 3150): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3150): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3150): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 3150): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3150): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  757): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3150): onReceive
D/BluetoothMapService( 3150): STATE_TURNING_OFF
V/BluetoothMapService( 3150): Handler(): got msg=4
D/BluetoothMapService( 3150): MAP Service closeService in
D/BluetoothMapMasInstance( 3150): MAP Service shutdown
V/BluetoothMapService( 3150): MAP Service closeService out
,I/BtOppRfcommListener( 3150): stopping Accept Thread
,I/BtOppRfcommListener( 3150): BluetoothSocket listen thread finished
,E/WifiStateMachine(  757): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/jxcore-log( 3097): Radios toggled
I/jxcore-log( 3097): 
,W/ContextImpl( 3193): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/chromium( 3097): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/DockEventReceiver( 3193): finishStartingService: stopping service
,D/BluetoothPbap( 3193): Proxy object disconnected
D/PbapServerProfile( 3193): Bluetooth service disconnected
,D/AuthorizationBluetoothService( 1321): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/bt_userial( 3150): RX termination
W/bt_userial( 3150): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3150): Leaving userial_read_thread()
,W/bt-btif ( 3150): ag scb idx 1 not allocated
E/bt-btif ( 3150): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3150): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3150): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3150): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3150): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3150): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3150): L2CAP - PSM: 0x0017 not found for deregistration
,D/bt_userial( 3150): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3150): hw_epilog_process
,I/bt_userial_vendor( 3150): device fd = 53 close
,I/GKI_LINUX( 3150): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3150): GKI_exit_task 0 done
I/GKI_LINUX( 3150): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 3150): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3150): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3150): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ccd5833
,D/HeadsetStateMachine( 3150): Exit Disconnected: -1
,D/BluetoothHeadset( 1273): Proxy object disconnected
,D/BluetoothHeadset( 1239): Proxy object disconnected
D/BluetoothHeadset( 1239): Proxy object disconnected
,D/BluetoothHeadset(  757): Proxy object disconnected
,D/A2dpService( 3150): Received stop request...Stopping profile...
D/BluetoothHeadset( 3193): Proxy object disconnected
D/HeadsetProfile( 3193): Bluetooth service disconnected
D/A2dpStateMachine( 3150): Exit Disconnected: -1
,D/BluetoothAdapterService( 3150): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ccd5833
,D/BluetoothA2dp(  757): Proxy object disconnected
,D/BluetoothAdapterState( 3150): Stopping profile services that were post enabled
,D/HidService( 3150): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3150): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ccd5833
D/HeadsetStateMachine( 3150): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3150): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3150): Cleaning up Bluetooth Handsfree callback object
,D/HealthService( 3150): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3150): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ccd5833
,D/PanService( 3150): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3150): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ccd5833
,D/BtGatt.DebugUtils( 3150): handleDebugAction() action=null
,D/BtGatt.GattService( 3150): Received stop request...Stopping profile...
D/BtGatt.GattService( 3150): stop()
D/BtGatt.AdvertiseManager( 3150): advertise clients cleared
,D/BluetoothAdapterService( 3150): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ccd5833
,D/BluetoothA2dp( 3193): Proxy object disconnected
D/A2dpProfile( 3193): Bluetooth service disconnected
,I/GKI_LINUX( 3150): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3150): GKI_exit_task 2 done
I/GKI_LINUX( 3150): GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BluetoothMapService( 3150): Received stop request...Stopping profile...
D/BluetoothInputDevice( 3193): Proxy object disconnected
,D/BluetoothMapService( 3150): stop()
D/HidProfile( 3193): Bluetooth service disconnected
,D/BluetoothPan( 3193): BluetoothPAN Proxy object disconnected
D/BluetoothMapEmailAppObserver( 3150): deinitObservers()
D/PanProfile( 3193): Bluetooth service disconnected
D/BluetoothMapEmailAppObserver( 3150): removeReceiver()
D/BluetoothAdapterService( 3150): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ccd5833
,D/BluetoothMap( 3193): Proxy object disconnected
W/BluetoothHidServiceJni( 3150): Cleaning up Bluetooth HID Interface...
D/MapProfile( 3193): Bluetooth service disconnected
W/bt-btif ( 3150): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3150): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3150): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3150): Cleaning up Bluetooth Health object
,W/BluetoothPanServiceJni( 3150): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3150): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 3150): Handler(): got msg=4
D/BluetoothMapService( 3150): MAP Service closeService in
V/BluetoothMapService( 3150): MAP Service closeService out
,D/BluetoothMapService( 3150): cleanup()
D/BluetoothMapService( 3150): MAP Service closeService in
V/BluetoothMapService( 3150): MAP Service closeService out
D/BluetoothAdapterState( 3150): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3150): Setting state to 10
I/BluetoothAdapterState( 3150): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  757): Broadcasting onBluetoothStateChange(false) to 11 receivers.
I/BluetoothAdapterState( 3150): Entering OffState
D/BluetoothHeadset( 1273): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1239): onBluetoothStateChange: up=false
D/BluetoothA2dp(  757): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1239): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3193): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 3193): onBluetoothStateChange: up=false
,D/BluetoothMap( 3193): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3193): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3193): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  757): onBluetoothStateChange: up=false
D/BluetoothManagerService(  757): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  757): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService(  757): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@162e781e mBinding = false
,D/BluetoothManagerService(  757): Sending unbind request.
,D/BluetoothManagerService(  757): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  898): 916313172: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  898): 916313172: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  898): 916313172: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3150): gki_task task_id=1 [BTIF] terminating
,W/ContextImpl( 3193): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/GKI_LINUX( 3150): GKI_exit_task 1 done
I/GKI_LINUX( 3150): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3150): cleanupNative: return from cleanup
,D/BluetoothAdapter( 1614): 144440293: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1614): 144440293: getState() :  mService = null. Returning STATE_OFF
I/art     ( 3150): System.exit called, status: 0
,I/AndroidRuntime( 3150): VM exiting with result code 0, cleanup skipped.
,D/DockEventReceiver( 3193): finishStartingService: stopping service
,D/AndroidRuntime( 3850): 
D/AndroidRuntime( 3850): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3850): CheckJNI is OFF
,I/ActivityManager(  757): Process com.android.bluetooth (pid 3150) has died
,D/AndroidRuntime( 3850): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  757): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  757): Killing 3097:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  757): Skipping PackageSetting{3e0b714a com.example.hello/10277} due to missing metadata
,I/WindowState(  757): WIN DEATH: Window{94e7c39 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  757): Client connection lost with reason: 4
,I/ActivityManager(  757):   Force finishing activity ActivityRecord{3939dd2a u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  757): Spurious death for ProcessRecord{3d63a61b 3097:com.test.thalitest/u0a270}, curProc for 3097: null
,I/ActivityManager(  757): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/Adreno-EGL(  943): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  943): Initialized EGL, version 1.4
,D/OpenGLRenderer(  943): Enabling debug mode 0
,W/InputMethodManagerService(  757): Got RemoteException sending setActive(false) notification to pid 3097 uid 10270
,I/Keyboard.Facilitator( 1090): onFinishInput()
,I/art     ( 1362): Explicit concurrent mark sweep GC freed 3962(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 519us total 18.835ms
,I/art     ( 1438): Explicit concurrent mark sweep GC freed 66720(3MB) AllocSpace objects, 14(272KB) LOS objects, 24% free, 19MB/25MB, paused 335us total 56.736ms
,I/Keyboard.Facilitator( 1090): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1614): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1090): run()
,I/InputReader(  757): Reconfiguring input devices.  changes=0x00000010
,I/Decoder ( 1090): createOrResetDecoder
,D/BluetoothAdapter( 3193): 203598301: getState() :  mService = null. Returning STATE_OFF
,I/art     (  757): Explicit concurrent mark sweep GC freed 39774(1977KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 3.433ms total 81.568ms
,I/art     (  757): WaitForGcToComplete blocked for 21.672ms for cause Explicit
,I/ConfigService( 1321): onCreate
,I/ActivityManager(  757): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=3924 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1090): run()
,D/BackupManagerService(  757): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  757): Receieved: android.intent.action.PACKAGE_REMOVED
,W/ResourcesManager( 3924): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1090): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1090): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1090): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1090): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1090): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1090): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1090): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1090): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1090): run() : Loaded (exit)
,D/TaskPersister(  757): removeObsoleteFile: deleting file=214_task.xml
I/Keyboard.Facilitator.Delight2FileSweeper( 1090): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1090): run()
I/StatsUtilsManager( 1090): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1090): shouldRecordStats() = Too Soon
I/Launcher( 1362): Deferring update until onResume
,D/AdapterServiceConfig( 3924): Adding HeadsetService
D/AdapterServiceConfig( 3924): Adding A2dpService
,D/AdapterServiceConfig( 3924): Adding HidService
D/AdapterServiceConfig( 3924): Adding HealthService
D/AdapterServiceConfig( 3924): Adding PanService
D/AdapterServiceConfig( 3924): Adding GattService
D/AdapterServiceConfig( 3924): Adding BluetoothMapService
I/ActivityManager(  757): Killing 1493:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/ResourcesManager( 1362): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1362): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  757): Explicit concurrent mark sweep GC freed 11873(618KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.812ms total 174.738ms
,I/Launcher( 1362): Deferring update until onResume
,D/AndroidRuntime( 3850): Shutting down VM
W/libprocessgroup(  757): failed to open /acct/uid_10013/pid_1493/cgroup.procs: No such file or directory
D/AuthorizationBluetoothService( 1321): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/VoicemailCleanupService( 1417): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1438): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1362): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1ccd5833 new=com.google.android.velvet.VelvetApplication@1ccd5833
,I/ActivityManager(  757): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3951 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1438): UpdateCorporaTask done [took 54 ms] updated apps [took 54 ms] 
,W/ContextImpl( 3951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1648): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1648): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1648): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1648): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1321): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1321): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1648): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1648): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1648): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1648): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1648): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1648): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1648): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1648): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1648): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1648): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1648): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1648): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1648): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1648): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  757): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3980 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1648): Using Auth Proxy for data requests.
,W/BaseAppContext( 1648): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1648): App measurement is starting up
,I/PeopleContactsSync( 1648): CP2 sync disabled
,I/Icing   ( 1648): doRemovePackageData com.test.thalitest
,E/SQLiteDatabase( 1648): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1648): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/SQLiteDatabase( 1648): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/SQLiteDatabase( 1648): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1648): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1648): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1648): Runtime exception while performing operation
E/ClearPendingStateOp( 1648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/ClearPendingStateOp( 1648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteOpenHel,per.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1648): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1648): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 1648): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1648): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1648): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1648): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/ClearPendingStateOp( 1648): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1648): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1648): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1648): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1648): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
F/ClearPendingStateOp( 1648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
F/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1648): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1648): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 1648): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1648): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1648): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1648): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
F/ClearPendingStateOp( 1648): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1648): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1648): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1648): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 1648): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1062)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.d.k(SourceFile:281)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.d.e(SourceFile:724)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.ak.n(SourceFile:1003)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.ak.k(SourceFile:1014)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.ak.b(SourceFile:263)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.al.run(SourceFile:162)
E/SQLiteDatabase( 1648): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1648): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.aj.run(SourceFile:272)
E/GMPM-SVC( 1648): Opening the database failed, dropping and recreating it
E/DropBoxManagerService(  757): Can't write: system_app_wtf
E/DropBoxManagerService(  757): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  757): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  757): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  757): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  757): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  757): 	... 5 more
E/SQLiteDatabase( 1648): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.d.k(SourceFile:281)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.d.e(SourceFile:724)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.ak.n(SourceFile:1003)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.ak.k(SourceFile:1014)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.ak.b(SourceFile:263)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.al.run(SourceFile:162)
E/SQLiteDatabase( 1648): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1648): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1648): 	at com.google.android.gms.measurement.internal.aj.run(SourceFile:272)
E/GMPM-SVC( 1648): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
W/GMPM-SVC( 1648): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
E/GMPM-SVC( 1648): Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
W/GMPM-SVC( 1648): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1058)
E/GMPM-SVC( 1648): Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1058)
E/SharedPreferencesImpl( 1648): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1648): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1648): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1648): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1648): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1648): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak

```
