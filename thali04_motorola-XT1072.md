#### Test 54970261c23922d_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
D/AndroidRuntime( 5412): 
D/AndroidRuntime( 5412): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5412): CheckJNI is OFF
D/AndroidRuntime( 5412): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  891): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  891): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5431 uid=10407 gids={50407, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5412): Shutting down VM
V/ActivityManager(  891): Display changed displayId=0
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5431): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5431): Time to load native libraries: 3 ms (timestamps 7336-7339)
I/LibraryLoader( 5431): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5431): Binding Chromium to main looper Looper (main, tid 1) {2d76be54}
I/LibraryLoader( 5431): Expected native library version number "",actual native library version number ""
I/chromium( 5431): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5431): Initializing chromium process, singleProcess=true
,W/art     ( 5431): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5431): ApplicationContext is null in ApplicationStatus
,W/chromium( 5431): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5431): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5431): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5431): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5431): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5431): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5431): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5431): Local Branch: 
I/Adreno-EGL( 5431): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5431): Local Patches: NONE
I/Adreno-EGL( 5431): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  891): Message: 20
D/BluetoothManagerService(  891): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@178d95f9:true
,D/BluetoothAdapter( 5431): 561825854: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  891): Activity pause timeout for ActivityRecord{ea0d79a u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 5431): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5431): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5431): CordovaWebView is running on device made by: motorola
,W/art     ( 5431): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5431): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5431): Render dirty regions requested: true
,D/Atlas   ( 5431): Validating map...
W/chromium( 5431): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 5431): Initialized EGL, version 1.4
D/OpenGLRenderer( 5431): Enabling debug mode 0
I/Keyboard.Facilitator( 1416): onFinishInput()
I/LaunchCheckinHandler(  891): Displayed com.test.thalitest/.MainActivity,cp,ca,975
I/ActivityManager(  891): Displayed com.test.thalitest/.MainActivity: +898ms (total +975ms)
W/IInputConnectionWrapper( 5431): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 5431): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5431): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 5431): Cannot call determinedVisibility() - never saw a connection for the pid: 5431
D/JsMessageQueue( 5431): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 5431): JniHelper::setJavaVM(0xb7db1310), pthread_self() = -1206651288
D/JX-Cordova( 5431): jxcore cordova android initializing
,W/jxcore-log( 5431): Initializing JXcore engine
W/jxcore-log( 5431): JXcore engine is ready
,W/jxcore-log( 5431): Starting JXcore engine
,W/.test.thalitest( 5431): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10407 path="socket:[6578]" dev="sockfs" ino=6578 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5431): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10407 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5431): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10407 path="socket:[7736]" dev="sockfs" ino=7736 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 5431): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10407 path="socket:[22450]" dev="sockfs" ino=22450 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5431): Platform android
W/jxcore-log( 5431): 
,W/jxcore-log( 5431): Process ARCH arm
W/jxcore-log( 5431): 
,I/jxcore-log( 5431): JXcore Cordova bridge is ready!
I/jxcore-log( 5431): 
W/jxcore-log( 5431): JXcore engine is started
I/chromium( 5431): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 5431): Toggling radios to true
I/jxcore-log( 5431): 
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  891): enable():  mBluetooth =null mBinding = false
W/Settings( 1476): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/BluetoothManagerService(  891): Message: 1
D/BluetoothManagerService(  891): MESSAGE_ENABLE: mBluetooth = null
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
D/WifiService(  891): New client listening to asynchronous messages
D/WifiService(  891): setWifiEnabled: true pid=5431, uid=10407
E/WifiService(  891): Invoking mWifiStateMachine.setWifiEnabled
E/WifiStateMachine(  891): setting operational mode to 1
I/jxcore-log( 5431): Radios toggled
I/jxcore-log( 5431): 
I/ActivityManager(  891): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5491 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
W/Settings( 1476): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
W/Settings( 1476): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
W/Settings( 1476): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
W/ResourcesManager( 5491): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 5491): Adding HeadsetService
D/AdapterServiceConfig( 5491): Adding A2dpService
D/AdapterServiceConfig( 5491): Adding HidService
D/AdapterServiceConfig( 5491): Adding HealthService
D/AdapterServiceConfig( 5491): Adding PanService
D/AdapterServiceConfig( 5491): Adding GattService
D/AdapterServiceConfig( 5491): Adding BluetoothMapService
,D/BluetoothManagerService(  891): Message: 20
D/BluetoothManagerService(  891): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ed12487:true
D/BluetoothAdapterState( 5491): make
,I/bluedroid( 5491): init
I/BluetoothAdapterState( 5491): Entering OffState
,I/bte_conf( 5491): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5491): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5491): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5491): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 5491): get_profile_interface socket
I/bluedroid( 5491): get_profile_interface map_client
,I/GKI_LINUX( 5491): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 5491): Address is:44:80:EB:7B:5A:05
,D/BluetoothAdapterProperties( 5491): Name is: XT1072
D/BluetoothManagerService(  891): Bluetooth Adapter name changed to XT1072
D/BluetoothManagerService(  891): Stored Bluetooth name: XT1072
D/BluetoothManagerService(  891): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  891): Message: 40
D/BluetoothManagerService(  891): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 5491): config_hci_snoop_log
,D/BluetoothManagerService(  891): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  891): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 5491): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 5491): Setting state to 11
,D/TCMD    (  474): NL - Read 1008 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 1008 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
I/BluetoothAdapterState( 5491): Bluetooth adapter state changed: 10-> 11
,D/BluetoothBondStateMachine( 5491): make
D/Tethering(  891): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  891): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/BluetoothBondStateMachine( 5491): StableState(): Entering Off State
,E/Tethering(  891): ApnList is empty for checkDunConfigured()
D/Tethering(  891):  upstream interface types: 
D/Tethering(  891):  0
D/Tethering(  891):  1
D/Tethering(  891):  5
D/Tethering(  891):  7
,D/Tethering(  891): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  891): InitialState.processMessage what=4
D/Tethering(  891): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  891): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  891): ApnList is empty for checkDunConfigured()
D/Tethering(  891):  upstream interface types: 
D/Tethering(  891):  0
D/Tethering(  891):  1
D/Tethering(  891):  5
D/Tethering(  891):  7
,D/QsoftapCmd(  293): Got softap fwreload command we are passing on
,D/Tethering(  891): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothManagerService(  891): Message: 60
D/BluetoothManagerService(  891): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  891): Bluetooth State Change Intent: 10 -> 11
D/SoftapController(  293): Softap fwReload - Ok
,D/BluetoothHeadset( 1548): Proxy object connected
D/BluetoothHeadset(  891): Proxy object connected
,D/BluetoothHeadset( 1513): Proxy object connected
D/HeadsetService( 5491): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 5491): classInitNative: succeeds
,D/HeadsetStateMachine( 5491): make
,D/BluetoothHeadset( 1513): Proxy object connected
,I/ActivityManager(  891): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5535 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/BluetoothAdapterState( 5491): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/CommandListener(  293): Setting iface cfg
D/CommandListener(  293): Trying to bring down wlan0
D/CommandListener(  293): Clearing all IP addresses on wlan0
,D/Checkin ( 3054): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 3054): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/art     (  891): Explicit concurrent mark sweep GC freed 13457(780KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 19MB/29MB, paused 1.856ms total 164.632ms
D/HeadsetStateMachine( 5491): max_hf_connections = 1
I/bluedroid( 5491): get_profile_interface handsfree
,D/HeadsetStateMachine( 5491): Enter Disconnected: -2, size: 0
,I/MDMCTBK (  295): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  295): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): wifi_connect_to_supplicant, current pid is = 295
,D/MDMCTBK (  295): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  295): wifi_close_sockets: Exit
E/MDMCTBK (  295): Attach monitor thread
,I/wpa_supplicant( 5552): Successfully initialized wpa_supplicant
I/wpa_supplicant( 5552): Long line in configuration file truncated
,I/wpa_supplicant( 5552): rfkill: Cannot open RFKILL control device
D/TCMD    (  474): NL - Read 1004 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
,D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/BluetoothAdapterService( 5491): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d76be54
,D/A2dpService( 5491): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 5491): classInitNative: succeeds
D/BluetoothA2dp(  891): Proxy object connected
I/bluedroid( 5491): get_profile_interface avrcp
,E/WifiStateMachine(  891): setWifiState: enabling
E/WifiStateMachine(  891): Supplicant start successful
D/WifiMonitor(  891): startMonitoring(wlan0) with mConnected = false
,I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1300): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1300): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1300): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,W/ResourcesManager( 5535): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/libmdmdetect( 5552): ESOC framework not supported
E/Diag_Lib( 5552):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 5552): baseband property is set to [msm]
I/libmdmdetect( 5552): ESOC framework not supported
,E/RemoteController( 5491): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 5491): classInitNative: succeeds
D/A2dpStateMachine( 5491): make
,I/bluedroid( 5491): get_profile_interface a2dp
I/GKI_LINUX( 5491): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 5491): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d76be54
D/A2dpStateMachine( 5491): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 5491): classInitNative: succeeds
,D/HidService( 5491): Received start request. Starting profile...
I/bluedroid( 5491): get_profile_interface hidhost
D/BluetoothAdapterService( 5491): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d76be54
,I/BluetoothHealthServiceJni( 5491): classInitNative: succeeds
E/wpa_supplicant( 5552):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5552): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5552): card_info[i].card_state: 0x0
E/wpa_supplicant( 5552): card_info[i].error_code: 0x0
,E/wpa_supplicant( 5552): SIM/USIM not ready
E/wpa_supplicant( 5552): Error while reading SIM card status
D/HealthService( 5491): Received start request. Starting profile...
,I/bluedroid( 5491): get_profile_interface health
D/BluetoothAdapterService( 5491): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d76be54
I/BluetoothPanServiceJni( 5491): classInitNative(L105): succeeds
,D/PanService( 5491): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5491): initializeNative(L110): pan
I/bluedroid( 5491): get_profile_interface pan
E/wpa_supplicant( 5552): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5552): card_info[i].card_state: 0x0
E/wpa_supplicant( 5552): card_info[i].error_code: 0x0
E/wpa_supplicant( 5552): SIM/USIM not ready
I/wpa_supplicant( 5552): eap_proxy: Card not ready
,D/BluetoothAdapterService( 5491): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d76be54
I/BtGatt.JNI( 5491): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 5491): handleDebugAction() action=null
,D/BtGatt.GattService( 5491): Received start request. Starting profile...
D/BtGatt.GattService( 5491): start()
I/bluedroid( 5491): get_profile_interface gatt
D/BluetoothAdapterService( 5491): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d76be54
D/BtGatt.AdvertiseManager( 5491): advertise manager created
,D/BluetoothAdapterService( 5491): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d76be54
,D/BluetoothMapService( 5491): Received start request. Starting profile...
D/BluetoothMapService( 5491): start()
,D/BluetoothMapEmailSettingsLoader( 5491): Found 0 applications
D/BluetoothMapEmailAppObserver( 5491): createReceiver()
,D/BluetoothMapEmailAppObserver( 5491): initObservers()
D/BluetoothMapEmailAppObserver( 5491): getEnabledAccountItems()
,D/BluetoothAdapterService( 5491): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d76be54
D/HeadsetStateMachine( 5491): Proxy object connected
,D/BluetoothAdapterState( 5491): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5491): enable
D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 5491): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5491): Disconnected process message: 11, size: 0
,I/GKI_LINUX( 5491): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 5491): init
,I/bt-btu  ( 5491): btu_task pending for preload complete event
,I/bt_vendor( 5491): bt-vendor : init
D/bt_userial_mct( 5491): userial_init
,I/bt_hwcfg( 5491): Starting hciattach daemon
I/bt_hwcfg( 5491): try to set false
,I/bt_hwcfg( 5491): Starting hciattach daemon
I/bt_hwcfg( 5491): try to set true
,I/ActivityManager(  891): Killing 5181:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/qcom-bluetooth( 5568): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/qcom-bluetooth( 5574): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 5575): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/wpa_supplicant( 5552): rfkill: Cannot open RFKILL control device
,D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
,D/TCMD    (  474): Listening for incoming client connection request
,I/qcom-bluetooth( 5577): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,E/wpa_supplicant( 5552): baseband property is set to [msm]
I/libmdmdetect( 5552): ESOC framework not supported
,I/qcom-bluetooth( 5578): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,E/wpa_supplicant( 5552):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5552): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5552): card_info[i].card_state: 0x0
E/wpa_supplicant( 5552): card_info[i].error_code: 0x0
E/wpa_supplicant( 5552): SIM/USIM not ready
E/wpa_supplicant( 5552): Error while reading SIM card status
,I/qcom-bluetooth( 5579): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/wpa_supplicant( 5552): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5552): card_info[i].card_state: 0x0
E/wpa_supplicant( 5552): card_info[i].error_code: 0x0
E/wpa_supplicant( 5552): SIM/USIM not ready
I/wpa_supplicant( 5552): eap_proxy: Card not ready
,I/MDMCTBK (  295): createWifiMonitorThread: Started the wifi monitor thread -1200869080
I/wpa_supplicant( 5552): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,D/MDMCTBK (  295): wifi_wait_on_socket: Enter monitor thread
D/MDMCTBK (  295): reply_len: 73 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  295): Event received = CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,E/WifiStateMachine(  891): setSuspendOptimizations: 2 true
,E/WifiStateMachine(  891): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  891): Supplicant connection established
,E/WifiStateMachine(  891): setWifiState: enabled
,W/libprocessgroup(  891): failed to open /acct/uid_10090/pid_5181/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiConfigStore(  891): Loading config and enabling all networks 
,I/SBar.MotoNetworkCtrlr( 1300): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/AuthorizationBluetoothService( 1703): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/WifiConfigStore(  891):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  891):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  891): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  891): Setting external_sim to 1
,D/WifiStateMachine(  891): Setting OUI to DA-A1-19
I/WifiNative-HAL(  891): startHal
E/wifi    (  891): getStaticLongField sWifiHalHandle 0xa2e7e89c
,D/wifi    (  891): halHandle = 0x0, mVM = 0xb7db1310, mCls = 0x201956
I/WifiNative-HAL(  891): Could not start hal
,E/WifiStateMachine(  891): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 5552): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  891): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/MDMCTBK (  295): reply_len: 73 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:0
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:0
,I/wpa_supplicant( 5552): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  295): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5552): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-AVOID-FREQ ra
,D/MDMCTBK (  295): Event received = CTRL-EVENT-AVOID-FREQ ra
,I/ActivityManager(  891): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=5586 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
E/native  (  891): do suspend true
D/WifiP2pService(  891): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  293): Setting iface cfg
D/CommandListener(  293): Trying to bring up p2p0
D/WifiMonitor(  891): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  891): P2pEnablingState
D/WifiScanningService(  891): SCAN_AVAILABLE : 3
D/RttService(  891): SCAN_AVAILABLE : 3
D/WifiScanningService(  891): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  891): startHal
D/RttService(  891): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnablingState{ when=-2ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2p socket connection successful
D/WifiP2pService(  891): P2pEnabledState
,D/WifiP2pService(  891): sending p2p connection changed broadcast
,E/wifi    (  891): getStaticLongField sWifiHalHandle 0xa19a79cc
D/wifi    (  891): halHandle = 0x0, mVM = 0xb7db1310, mCls = 0x20194a
I/WifiNative-HAL(  891): Could not start hal
,E/WifiScanningService(  891): could not start HAL
,E/WifiStateMachine(  891): set country code US
,D/WifiNative-HAL(  891): p2pGetDeviceAddress
D/WifiNative-HAL(  891): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,E/WifiStateMachine(  891): set frequency band 2
D/WifiP2pService(  891): DeviceAddress: 44:80:eb:7b:5a:07
D/WifiP2pService(  891): MCC mode enabled 0
D/WifiP2pService(  891): mP2pAutoConnectSupport = 0
D/WifiP2pService(  891): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  891): InactiveState
,D/WifiP2pService(  891): InactiveState{ when=-6ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  891): P2pEnabledState{ when=-6ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5552): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 5552): wlan0: Failed to initiate AP scan
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>Reject scan trigger sinc
D/MDMCTBK (  295): Event received = Reject scan trigger sinc
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <4>Failed to initiate AP sc
D/MDMCTBK (  295): Event received = Failed to initiate AP sc
D/WifiP2pService(  891): InactiveState{ when=-8ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-8ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  891): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine(  891): setDetailed state send new extra info0x
I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  891): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/SharedPreferencesImpl(  891): Couldn't create directory for SharedPreferences file shared_prefs/android_preferences.xml
W/ResourcesManager( 5586): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Killing 5111:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10039/pid_5111/cgroup.procs: No such file or directory
,D/Checkin ( 3054): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 3054): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/Checkin ( 3054): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c
D/MDMCTBK (  295): Event received = CTRL-EVENT-BSS-ADDED 0 c
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  295): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  295): Event received = WPS-AP-AVAILABLE 
,I/WifiNative-HAL(  891): startHal
E/wifi    (  891): getStaticLongField sWifiHalHandle 0xa2e7e8fc
D/wifi    (  891): halHandle = 0x0, mVM = 0xb7db1310, mCls = 0x18aa
I/WifiNative-HAL(  891): Could not start hal
E/WifiStateMachine(  891): [1,451,923,689,466 ms] noteScanEnd no scan source
,E/WifiStateMachine(  891): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2f442bc8 sup_state=SCANNING debouncing=false
,D/Checkin ( 3054): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,E/WifiStateMachine(  891): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  891):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  891): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  891): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  891): will read network variables netId=0
,E/WifiStateMachine(  891): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  891): will read network variables netId=0
,I/wpa_supplicant( 5552): wlan0: Trying to associate with SSID 'NG700'
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  295): Event received = Trying to associate with
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 5552): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/WifiMonitor(  891): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiConfigStore(  891): setLastSelectedConfiguration -1
,E/wpa_supplicant( 5552): PNO: In assoc process
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TCMD    (  474): NL - Read 312 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 192 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 80 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 80 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 5552): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  295): Event received = Associated with c0:ff:d4
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  891): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  891): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  891): ApnList is empty for checkDunConfigured()
D/Tethering(  891):  upstream interface types: 
D/Tethering(  891):  0
D/Tethering(  891):  1
,D/Tethering(  891):  5
D/Tethering(  891):  7
E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  891): setDetailed state send new extra info"NG700"
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 5552): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  295): Event received = WPA: Key negotiation com
I/wpa_supplicant( 5552): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  295): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  295):  STA Connected !!
D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,E/MDMCTBK (  295): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  295): get_freq !!, resp=2412
I/MDMCTBK (  295): get_freq !!, Strip data
I/MDMCTBK (  295): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): get_property_value, Enter
I/MDMCTBK (  295): get_property_value, Values read from property=0,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  295): get_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
,I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler, Wifi Band changed, call setWifiCutback.
I/MDMCTBK (  295): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 0, data=0
I/MDMCTBK (  295): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  295): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): get_property_value, Enter
I/MDMCTBK (  295): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  295): get_property_value, Exit
I/MDMCTBK (  295): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1200853264
I/MDMCTBK (  295): return from set_get_from_wpa_supplicant
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  295): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  295): , reply_len: 3, ret: 0
E/MDMCTBK (  295): MdmCutbackHndler, resp=OK
E/MDMCTBK (  295): 
D/MDMCTBK (  295): wifi_set_tx_pwr: Exit
D/Tethering(  891): sendTetherStateChangedBroadcast 1, 0, 0,
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/qcom-bluetooth( 5619): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 44:80:eb:7b:5a:05 
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  891): Network connection established
E/WifiStateMachine(  891): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiP2pService(  891): InactiveState{ when=-2ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiP2pService(  891): P2pEnabledState{ when=-2ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledStateupdate channel list
,I/qcom-bluetooth( 5621): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  891): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  891): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  891): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  891): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  891): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine(  891): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  891): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  293): Setting iface cfg
,E/WifiStateMachine(  891): Start Dhcp Watchdog 1
,I/bt_hwcfg( 5491): bluetooth satus is on
,E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/bt_userial_mct( 5491): userial_open(port:0)
,I/bt_userial_vendor( 5491): Done intiailizing UART
,I/bt_userial_vendor( 5491): Done intiailizing UART
I/bt_userial_mct( 5491): CMD=53, EVT=53, ACL_Out=54, ACL_In=54
I/bt_vendor( 5491): Bluetooth Firmware and smd is initialized
I/bt-btu  ( 5491): btu_task received preload complete event
,D/bt_userial_mct( 5491): Entering userial_read_thread()
,I/        ( 5491): BTE_InitTraceLevels -- TRC_HCI
I/        ( 5491): BTE_InitTraceLevels -- TRC_L2CAP
,I/        ( 5491): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5491): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5491): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5491): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5491): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5491): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5491): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5491): BTE_InitTraceLevels -- TRC_PAN
,I/        ( 5491): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5491): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5491): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5491): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5491): BTE_InitTraceLevels -- TRC_BTIF
,E/WifiStateMachine(  891): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  891): do suspend false
,E/wpa_supplicant( 5552): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  891): Unexpected BatchedScanResults :null
E/wpa_supplicant( 5552): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  891): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1212595e target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1212595e target=com.android.internal.util.StateMachine$SmHandler }
,E/bt-btm  ( 5491): BTM_SecRegister:p_cb_info->p_le_callback == 0xa6e3fd85 
E/bt-btm  ( 5491): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa6e3fd85 
,E/bt-btif ( 5491): Calling BTA_HhEnable
,E/bt-btif ( 5491): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 5491): Address is:44:80:EB:7B:5A:05
,D/BluetoothAdapterProperties( 5491): Name is: XT1072
D/BluetoothManagerService(  891): Bluetooth Adapter name changed to XT1072
D/BluetoothManagerService(  891): Stored Bluetooth name: XT1072
,D/BluetoothAdapterProperties( 5491): Scan Mode:20
,D/BluetoothAdapterProperties( 5491): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5491): Adding bonded device:7C:F9:0E:37:96:AB
,D/BluetoothAdapterProperties( 5491): Adding bonded device:E0:DB:10:14:E2:C0
,D/BluetoothAdapterProperties( 5491): Adding bonded device:58:2A:F7:ED:96:BE
E/BluetoothRemoteDevices( 5491): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:37:96:AB, value is empty for type: 10
,E/BluetoothRemoteDevices( 5491): devicePropertyChangedCallback: bdDevice: E0:DB:10:14:E2:C0, value is empty for type: 10
,E/BluetoothRemoteDevices( 5491): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,E/bt_mct  ( 5491): hci lib postload completed
,D/bte_conf( 5491): Device ID record 1 : primary
D/bte_conf( 5491):   vendorId            = 000f
D/bte_conf( 5491):   vendorIdSource      = 0001
,D/bte_conf( 5491):   product             = 1200
D/bte_conf( 5491):   version             = 1436
D/bte_conf( 5491):   clientExecutableURL = 
D/bte_conf( 5491):   serviceDescription  = 
D/bte_conf( 5491):   documentationURL    = 
D/bte_conf( 5491): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 5491): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5491): ScanMode =  20
D/BluetoothAdapterProperties( 5491): State =  11
D/BluetoothPanServiceJni( 5491): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterProperties( 5491): Scan Mode:21
D/BluetoothAdapterProperties( 5491): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5491): Setting state to 12
I/BluetoothAdapterState( 5491): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  891): Message: 60
D/BluetoothManagerService(  891): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  891): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothA2dp(  891): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 5491): Entering On State
D/BluetoothHeadset( 1513): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1513): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1548): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  891): onBluetoothStateChange: up=true
D/BluetoothManagerService(  891): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  891): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  891): Message: 40
D/BluetoothManagerService(  891): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 5491): onReceive
D/BluetoothMapService( 5491): STATE_ON
,D/BluetoothMapMasInstance( 5491): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 5491): MAS initSocket()
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5491): getBluetoothService() called with no BluetoothManagerCallback
,I/Telecom ( 1513): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/BluetoothMapMasInstance( 5491): Accepting socket connection...
,D/HeadsetStateMachine( 5491): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 5491): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 5491): mNumber:  mType: 128
W/ContextImpl( 5535): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/HeadsetStateMachine( 5491): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 5491): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothManagerService(  891): Message: 20
D/BluetoothManagerService(  891): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34a525b:true
,D/LocalBluetoothProfileManager( 5535): Adding local A2DP profile
,D/BluetoothManagerService(  891): Message: 30
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/LocalBluetoothProfileManager( 5535): Adding local HEADSET profile
,D/AuthorizationBluetoothService( 1703): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/BluetoothAdapter( 5491): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  891): Message: 30
,D/BluetoothManagerService(  891): Message: 30
,D/BluetoothManagerService(  891): Message: 30
,D/LocalBluetoothProfileManager( 5535): Adding local MAP profile
,D/BluetoothMap( 5535): Create BluetoothMap proxy object
,D/BluetoothManagerService(  891): Message: 30
,D/BluetoothManagerService(  891): Message: 30
,D/LocalBluetoothProfileManager( 5535): LocalBluetoothProfileManager construction complete
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5491): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 5491): Accept thread started.
,D/DockEventReceiver( 5535): finishStartingService: stopping service
,D/BluetoothA2dp( 5535): Proxy object connected
,D/A2dpProfile( 5535): Bluetooth service connected
,D/BluetoothHeadset( 5535): Proxy object connected
,D/HeadsetProfile( 5535): Bluetooth service connected
,D/BluetoothInputDevice( 5535): Proxy object connected
D/HidProfile( 5535): Bluetooth service connected
,D/BluetoothPan( 5535): BluetoothPAN Proxy object connected
D/PanProfile( 5535): Bluetooth service connected
,D/BluetoothMap( 5535): Proxy object connected
,D/MapProfile( 5535): Bluetooth service connected
,D/BluetoothMap( 5535): getConnectedDevices()
,D/BluetoothPbap( 5535): Proxy object connected
,D/PbapServerProfile( 5535): Bluetooth service connected
,E/DHCPCD  ( 5644): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5644): version 5.5.6 starting
E/DHCPCD  ( 5644): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 5644): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 5644): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 5644): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5644): wlan0: discarding expired lease
,I/DHCPCD  ( 5644): wlan0: broadcasting for a lease
D/DHCPCD  ( 5644): wlan0: sending DISCOVER (xid 0xd762587e), next in 4.44 seconds
,I/MDMCTBK (  295): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  295): NetlinkHandler, interfaceAdded
I/MDMCTBK (  295): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
E/MDMCTBK (  295): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  295): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  295): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  295): , Wifi = 1
I/MDMCTBK (  295): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
,I/MDMCTBK (  295): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 1, data=0
I/MDMCTBK (  295): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  295): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): get_property_value, Enter
I/MDMCTBK (  295): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  295): get_property_value, Exit
I/MDMCTBK (  295): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1200853264
I/MDMCTBK (  295): return from set_get_from_wpa_supplicant
I/MDMCTBK (  295): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
D/MDMCTBK (  295): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
I/MDMCTBK (  295): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
E/MDMCTBK (  295): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  295): , reply_len: 3, ret: 0
E/MDMCTBK (  295): MdmCutbackHndler, resp=OK
E/MDMCTBK (  295): 
D/MDMCTBK (  295): wifi_set_tx_pwr: Exit
,I/MDMCTBK (  295): send SAR ctrl over QMI
,I/DHCPCD  ( 5644): wlan0: offered 192.168.1.123 from 192.168.1.1
D/DHCPCD  ( 5644): wlan0: sending REQUEST (xid 0xd762587e), next in 4.16 seconds
,I/DHCPCD  ( 5644): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 5644): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 5644): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 5644): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 5644): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5644): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5644): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason BOUND
D/TCMD    (  474): NL - Read 60 bytes from update socket.
D/TCMD    (  474): NL - ignore NL message, type = 20
D/TCMD    (  474): Listening for incoming client connection request
,E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,E/WifiStateMachine(  891): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  891): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  891): do suspend true
,D/WifiP2pService(  891): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  891): WifiStateMachine DHCP successful
E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  891): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  891): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  891): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  891): Adding iface wlan0 to network 100
I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  891): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  891): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/Checkin (  891): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  891): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  891): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
E/WifiStateMachine(  891): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/SBar.MotoNetworkCtrlr( 1300): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/ConnectivityService(  891): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  891): Setting Dns servers for network 100 to [/192.168.1.1]
D/Checkin (  891): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Nat464Xlat(  891): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  891): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  891): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  891): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  891):    accepting network in place of null
,D/ConnectivityService(  891): Setting tx/rx TCP buffers to 131072,262144,3145728,4096,221184,3145728
,D/CSLegacyTypeTracker(  891): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1300): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  891): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1300): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  891): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  891): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1300): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1949): CM callback handler got msg 524290
,E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  891): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  891): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  891): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1300): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1949): CM callback handler got msg 524295
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 04 Jan 2016 16:08:12 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451923692874], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451923692854]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Validated
,D/ConnectivityService(  891): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  891): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  891): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  891): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1300): CM callback handler got msg 524290
,D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1949): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1530): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1530): Inetcondition changed, white->blue
I/SBar.MotoNetworkCtrlr( 1300): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1300): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1300): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1300): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ProcessCpuTracker(  891): Skipping unknown process pid 5694
,W/ProcessCpuTracker(  891): Skipping unknown process pid 5695
,W/ProcessCpuTracker(  891): Skipping unknown process pid 5704
,D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  891): MasterInitialState.processMessage what=3
,D/PollingManager( 2615): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2615): now: 359679 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1476): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2615): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2615): now: 359704 ,futureTime: 9223372036854775807
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/PollingManager( 2615): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  891): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5718 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PollingManager( 2615): now: 359752 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2615): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1476): now: 359758 ,futureTime: 86474950
,D/Central_PollingManager( 1476): Polling alarm set to expire at: 86474950 Current Time: 359758
D/AlarmManagerService(  891): Setting time of day to sec=1451923695
W/AlarmManagerService(  891): Unable to set rtc to 1451923695: Invalid argument
V/AlarmManager(  891): send {163f07bd, *alarm*:android.intent.action.TIME_TICK}
,D/OtaApp  ( 2615): [debug] > PollingManagerService, now: 359781 ,futureTime: 9223372036854775807
,D/MMApiProvisionService( 2615): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2615): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2615): createDeviceIdOrLogin update_device
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2615): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2615): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2615): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,E/GpsLocationProvider(  891): No APN found to select.
,D/MMApiProvisionService( 2615): isDeviceProvisioned: deviceId = 2072049230914535424
V/AlarmManager(  891): done {163f07bd, *alarm*:android.intent.action.TIME_TICK} [105ms]
,D/CCE     ( 2615): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2615): createDeviceIdOrLogin update_device
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,D/GpsLocationProvider(  891): NTP server returned: 1451923695423 (Mon Jan 04 17:08:15 GMT+01:00 2016) reference: 359751 certainty: 9 system time offset: -177
,E/LocSvc_ApiV02(  891): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,E/ActivityThread( 1949): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  891): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 392472, reason: UserStart
,I/art     ( 2615): Explicit concurrent mark sweep GC freed 24568(1876KB) AllocSpace objects, 4(57KB) LOS objects, 40% free, 11MB/18MB, paused 1.754ms total 100.651ms
,D/MMApiProvisionService( 2615): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2615): isRequestAllowed(): already have outstanding request ... ignoring request
,D/MMApiWebService( 2615): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2615): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2615): generating token using payload instead of using session token
,I/art     (  891): Explicit concurrent mark sweep GC freed 49438(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.750ms total 163.784ms
,E/Auth.Api.Credentials( 1949): [CredentialSyncAdapter] Unknown sync event.
,D/MMApiProvisionService( 2615): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2615): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2615): createDeviceIdOrLogin update_device
D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2615): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2615): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2615): [debug] > CusSM.onRadioUp
,D/ChimeraCfgMgr( 1949): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1949): Module APK com.google.android.play.games already loaded
,D/OtaApp  ( 2615): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2615): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2615): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,I/MusicStore( 5718): Database version: 120
,D/OtaApp  ( 2615): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2615): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2615): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2615): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/art     ( 1476): Explicit concurrent mark sweep GC freed 5013(233KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 8.556ms total 91.977ms
,D/ Nonce  ( 2615):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/GoogleURLConnFactory( 1703): Using platform SSLCertificateSocketFactory
,I/MMApiWSBase( 2615): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG],
,I/MMApiWSBase( 2615): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/PhenotypeConfigurator( 1703): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,I/GamesSyncServiceMain( 1949): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 1949): Failed to execute periodic sync, missing client context - aborting
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5718): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5718): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5718): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 5718): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5718): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5718): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  891): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=5769 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 22.872ms
,W/ActivityThread( 5718): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5718): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@fcd61b0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5718): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5718): GMSCore installation verified
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 21.217ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 22.336ms
,I/ConfigStore( 5718): Config Database version: 1
,I/MediaRouter( 5718): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5718): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5718): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5718): type=WIFI subType= reason=null isConnected=true
,W/ResourcesManager( 5769): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5769): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5799 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 5718): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5718): Using platform SSLCertificateSocketFactory
,V/JNIHelp ( 5769): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5769): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5769): Installed default security provider GmsCore_OpenSSL
,V/Mms     ( 5799): mnc/mcc: 
,V/Mms     ( 5799): tag: int value: recipientLimit - 20
V/Mms     ( 5799): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 5799): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 5799): tag: int value: maxSubjectLength - 80
V/Mms     ( 5799): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 5799): tag: bool value: enableGroupMms - false
V/Mms     ( 5799):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/MMApiWSBase( 2615): doRequest(): error in response: 403
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWSBase( 2615): doRequest(): error in response: {"error":"INVALID_SESSION","error_text":"Please provide a valid authtoken"}
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWSBase( 2615): doRequest(): v1/gns/list/messages resp length: 75
,I/MMApiWebService( 2615): inspectMMApiResponse(): found an error from a web service response: ForbiddenError msg: INVALID_SESSION req: 
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2615): inspectMMApiResponse(): received invalid session error from the server.. need to re-login
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2615): initiateDeviceLogin(): sending login request
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2615): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2615): Got request to obtain new Session .. doing so now
I/MMApiProvisionService( 2615): createDeviceIdOrLogin update_device
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2615): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2615): Got request to obtain new Session .. doing so now
I/MMApiProvisionService( 2615): createDeviceIdOrLogin update_device
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2615): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2615): isRequestAllowed(): already have outstanding request ... ignoring request
,D/MMApiProvisionService( 2615): Got request to obtain new Session .. doing so now
I/MMApiProvisionService( 2615): createDeviceIdOrLogin update_device
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2615): Not proxy app, so login/provision not allowed
,I/ Nonce  ( 2615):  Nonce Reponse 
D/        ( 2615): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"25fd45fe-38a1-4b5a-9d9b-63119a28ec1f"}
D/MMApiWSBase( 2615): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2615):  Nonce Handle Reponse 
,D/MMApiProvisionService( 2615): mOutstandingReq set to false
,W/ResourcesManager( 5799): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5831 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,W/PhenotypeConfigurator( 1703): Server returned 404
,D/DownloadManager( 2656): [88] Starting
,E/YouTube MDX( 5769): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/MMApiProvisionService( 2615): mForceLogin set to false.
D/MMApiProvisionService( 2615): createDeviceIdOrLogin(): Got request to login .. processing now
,W/ActivityThread( 2656): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5769): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/art     ( 1548): Explicit concurrent mark sweep GC freed 30050(1923KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.964ms total 84.333ms
,I/PeopleSync( 1949): onPerformSync() [5005f081]
,I/art     (  891): Explicit concurrent mark sweep GC freed 21036(890KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.757ms total 137.654ms
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BSUtils ( 2615): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1548): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/PhoneMonitor( 5831): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 5831): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5831): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  891): Killing 5270:com.google.android.gms:car/u0a16 (adj 15): empty #7
,W/ResourcesManager( 5769): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5769): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/DataUsage( 2615): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  891): failed to open /acct/uid_10016/pid_5270/cgroup.procs: No such file or directory
,I/dex2oat ( 5877): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1321260635.jar --oat-fd=38 --oat-location=/data/data/com.google.android.youtube/cache/ads-1321260635.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/CheckinService( 1949): Checkin interval check for package: unspecified last checkin: 1451341491846 min interval config: 0 actual interval: 582205895
,D/BSUtils ( 2615): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/CheckinService( 1949): Checking schedule, now: 1451923697774 next: 1451341521816
I/CheckinService( 1949): active receiver: enabled
,I/art     ( 1703): Explicit concurrent mark sweep GC freed 48935(2MB) AllocSpace objects, 14(247KB) LOS objects, 40% free, 13MB/22MB, paused 1.322ms total 121.477ms
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@161df626)
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@13259267)
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3c44e814)
E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3b8518bd)
E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4634eb2)
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2feeee03)
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@e927180)
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1bef83b9)
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3933a3fe)
E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2b68675f)
,I/iu.SyncManager( 1949): SYNC; picasa accounts
,I/CheckinService( 1949): Preparing to send checkin request
I/EventLogService( 1949): Accumulating logs since 1451923395126
,I/BSUtils ( 2615): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/NetworkLogImpl( 1949): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1949): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/MMApiWebService( 2615): doRequest() with req : MMApiWSRequest(/v1/gdi/devices.json)
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5769): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,I/dex2oat ( 5877): dex2oat took 213.614ms (threads: 4)
,W/ContextImpl( 5769): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5769): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,I/iu.UploadsManager( 1949): num queued entries: 0
I/iu.UploadsManager( 1949): num updated entries: 0
,I/iu.SyncManager( 1949): NEXT; no task
,I/ActivityManager(  891): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=5895 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/InstanceID/Rpc( 5769): Found 10016
,D/Checkin ( 2656): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,D/DownloadManager( 2656): [88] Finished with status SUCCESS
,D/MMApiWebService( 2615): generating token using payload instead of using session token
I/CheckinRequestBuilder( 1949): Checkin reason type: 8 attempt count: 1
,I/MMApiWSBase( 2615): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/devices.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/WifiService(  891): New client listening to asynchronous messages
D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5769): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  891): Start proc com.google.android.calendar for service com.google.android.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService: pid=5918 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 1949): Failed to find provider info for com.google.android.wearable.settings
,I/MDMCTBK (  295): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  295): NetlinkHandler, interfaceAdded
I/MDMCTBK (  295): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
E/MDMCTBK (  295): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  295): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  295): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  295): , Wifi = 1
I/MDMCTBK (  295): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  295): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  295): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  295): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): get_property_value, Enter
I/MDMCTBK (  295): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  295): get_property_value, Exit
,I/MDMCTBK (  295): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1200853264
I/MDMCTBK (  295): return from set_get_from_wpa_supplicant
I/MDMCTBK (  295): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
D/MDMCTBK (  295): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  295): set_property_value, Exit
E/MDMCTBK (  295): MdmCutbackHndler,Airplane Mode Enabled !! =1
,E/MDMCTBK (  295): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  295): , reply_len: 3, ret: 0
E/MDMCTBK (  295): MdmCutbackHndler, resp=OK
E/MDMCTBK (  295): 
,D/MDMCTBK (  295): wifi_set_tx_pwr: Exit
,I/ActivityManager(  891): Killing 5210:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10032/pid_5210/cgroup.procs: No such file or directory
,I/art     ( 5005): Explicit concurrent mark sweep GC freed 1545(68KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 929us total 28.197ms
,I/ActivityManager(  891): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5967 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/SQLiteLog( 5918): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  891): Killing 5535:com.android.settings/1000 (adj 15): empty #7
,I/GCM     ( 1703): GCM config loaded
,D/MMApiProvisionService( 2615): ProvisionWS.Response: processing response data: {"sessionToken":"0-591961430f222c61d228db40762d941436765851","error":"OK","sessionExpiration":"172742","deviceId":"2072049230914535424"}
,D/MMApiProvisionService( 2615): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 2615): doRequest(): /v1/gdi/devices.json resp length: 136
,I/ActivityManager(  891): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5993 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DeviceSettingsProvider( 1476):  Number of rows updated 1
,D/MMApiProvisionService( 2615): MMApiProvisionService.handleResponse (update_device) : true (None)
,W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_5535/cgroup.procs: No such file or directory
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5967): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5993): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/PeopleSync( 1949): Setting subscription: result=true [5005f081]
I/PeopleSync( 1949): Starting sync, feed=null [5005f081]
,W/AbstractGoogleClient( 5918): Application name is not set. Call Builder#setApplicationName.
,I/art     (  891): Explicit concurrent mark sweep GC freed 11382(555KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.499ms total 121.251ms
,I/CalendarProvider2( 5993): Created com.android.providers.calendar.CalendarAlarmManager@2e0fd266(com.android.providers.calendar.CalendarProvider2@fbbd9a7)
,I/ActivityManager(  891): Killing 5586:com.motorola.context/u0a8 (adj 15): empty #7
,I/DeviceSettingsProvider( 1476):  Number of rows updated 1
,E/MMApiProvisionService( 2615): Caught IOException:/pds/public/svcs/activation_date: open failed: EACCES (Permission denied)
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,W/FileUtils( 2615): Failed to chmod(/pds/public/svcs/activation_date): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
D/MMApiProvisionService( 2615): handleResponse(): Session Expiration alarm set to expire at: Wed Jan 06 17:07:21 GMT+01:00 2016
I/MMApiProvisionService( 2615):  value of type 2072049230914535424 0-591961430f222c61d228db40762d941436765851 172742
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2615):  get value of the device MOTO
I/MMApiProvisionService( 2615):  came in moto 
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2615): setMMApiCredInfoToMainApp: storing credential info
I/MMApiProvisionService( 2615): setMMApiCredInfoToMainApp: deviceId = 2072049230914535424
D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,W/DataUsage( 2615): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,I/DeviceSettingsProvider( 1476):  Number of rows updated 1
,I/DeviceSettingsProvider( 1476):  Number of rows updated 1
,I/DeviceSettingsProvider( 1476):  Number of rows updated 1
,E/PhoneInterfaceManager( 1548): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/libprocessgroup(  891): failed to open /acct/uid_10008/pid_5586/cgroup.procs: No such file or directory
,I/art     ( 1476): Explicit concurrent mark sweep GC freed 4177(163KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.113ms total 50.421ms
,I/AnalyticsLogBase( 5918): PlayLogger.onLoggerConnected
,I/AnalyticsLogBase( 5918): PlayLogger.onLoggerConnected
,W/BaseAppContext( 1949): Using Auth Proxy for data requests.
,I/DeviceSettingsProvider( 1476):  Number of rows updated 1
,W/BaseAppContext( 1949): Using Auth Proxy for data requests.
,W/BaseAppContext( 1949): Using Auth Proxy for data requests.
,I/PeopleSync( 1949): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/chromium( 5431): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Babel_SMS( 5967): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5967): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5967): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 5967): MmsConfig.loadFromDatabase
,I/DeviceSettingsProvider( 1476):  Number of rows updated 1
,E/Babel_SMS( 5967): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5967): MmsConfig.loadFromResources
,E/Babel_SMS( 5967): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5967): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/DeviceSettingsProvider( 1476):  Number of rows updated 1
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=252, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309928, SEQNUM=4444, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13020, POWER_SUPPLY_CHARGE_COUNTER=-676, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,W/Settings( 5967): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5967): startup - clean
,D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,I/Babel   ( 5967): deleted: false for 0
,I/DeviceSettingsProvider( 1476):  Number of rows updated 1
,I/DeviceSettingsProvider( 1476):  Number of rows updated 1
,D/BSUtils ( 2615): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/ActivityManager(  891): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6035 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MMApiProvisionService( 2615):  response.hasSettings() false
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 2615): handleResponse(): no settings sent by the server:
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2615): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
D/MMApiWebService( 2615): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,D/MMApiWebService( 2615): MMApiWebService told us to retry waiting request since device is successfully provisioned: 1
,D/MMApiWebService( 2615): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,W/VideoCapabilities( 5967): Unrecognized profile 2130706433 for video/avc
,I/MMApiWSBase( 2615): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,W/AudioCapabilities( 5967): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5967): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5967): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5967): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5967): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5967): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5967): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5967): onServiceConnected
W/Babel   ( 5967): Attempted to change video mute state without an active call.
,I/Babel   ( 5967): connection state changed from UNKNOWN to CONNECTED
,I/CalendarProvider2( 5993): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5993): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6035): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6035): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6035): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6035): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6035): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6035):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6035):   adb logcat -s GAv4
,W/GAv4    ( 6035): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6035): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6035): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  891): Killing 5718:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10080/pid_5718/cgroup.procs: No such file or directory
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 6035): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6035): Time to load native libraries: 2 ms (timestamps 5382-5384)
,I/LibraryLoader( 6035): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6035): Binding Chromium to main looper Looper (main, tid 1) {236e2081}
I/LibraryLoader( 6035): Expected native library version number "",actual native library version number ""
I/chromium( 6035): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/MMApiWSBase( 2615): doRequest(): v1/gns/list/messages resp length: 1363
,D/CCE     ( 2615): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 2615): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/BrowserStartupController( 6035): Initializing chromium process, singleProcess=true
W/art     ( 6035): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6035): ApplicationContext is null in ApplicationStatus
,W/chromium( 6035): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6035): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6035): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6035): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6035): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6035): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6035): Local Branch: 
I/Adreno-EGL( 6035): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6035): Local Patches: NONE
I/Adreno-EGL( 6035): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/Checkin ( 2615): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 2615): handleGetNotificationsResponse(): got 0; more=false
,I/ActivityManager(  891): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6096 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/AudioManagerAndroid( 6035): Requires BLUETOOTH permission
,W/ResourcesManager( 6096): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6096): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NSApplication( 6035): Starting up...
,I/MultiDex( 6096): VM with version 2.1.0 has multidex support
I/MultiDex( 6096): install
I/MultiDex( 6096): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  891): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6130 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 5799:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10023/pid_5799/cgroup.procs: No such file or directory
,V/JNIHelp ( 6096): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6096): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6096): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1987d111: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6096): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6096): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6096): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/CalendarSyncAdapter( 5918): Found no pending settings
,I/ActivityManager(  891): Killing 5831:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10035/pid_5831/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Killing 5895:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/WVCdm   (  297): Instantiating CDM.
I/WVCdm   (  297): CdmEngine::OpenSession
,I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
,D/NativeLibraryUtils( 6096): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  891): failed to open /acct/uid_10088/pid_5895/cgroup.procs: No such file or directory
W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,I/ActivityManager(  891): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6163 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff1000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff1000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
,D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,I/ActivityManager(  891): Killing 5993:com.android.providers.calendar/u0a5 (adj 15): empty #7
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb54bf960
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb769c480, dataLength=8
,D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76247e8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb776a7a0, idLength=0xb13fa730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=1716643781
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7630d58
,D/DrmWidevineDash(  297): message_length=1591, signature=0xb760d380, signature_length=2973738772
,W/libprocessgroup(  891): failed to open /acct/uid_10005/pid_5993/cgroup.procs: No such file or directory
,W/ResourcesManager( 6163): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,W/DataUsage( 2615): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,I/art     (  891): Explicit concurrent mark sweep GC freed 21685(1044KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.901ms total 140.254ms
,I/GoogleURLConnFactory( 6096): Using platform SSLCertificateSocketFactory
,I/art     ( 1949): Explicit concurrent mark sweep GC freed 21797(1542KB) AllocSpace objects, 33(528KB) LOS objects, 40% free, 15MB/25MB, paused 1.400ms total 145.650ms
,I/ActivityManager(  891): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6202 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 20.703ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 20.607ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 21.074ms
,D/EmailService.MarketingOptInSetter( 2615): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 2615): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,E/SQLiteLog( 2615): (284) automatic index on registration(APP_ID)
D/WaitableIntentService( 2615): ServiceHandler.handleMessage: mWaitCount=1
,I/PushService( 2615): started with background data enabled, making sure notification mechanism is enabled
,I/dex2oat ( 6200): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads-418892484.jar --oat-fd=104 --oat-location=/data/data/com.google.android.gms/cache/ads-418892484.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  891): Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=6229 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ContactLocale( 6202): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  891): Killing 5967:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10070/pid_5967/cgroup.procs: No such file or directory
,W/ResourcesManager( 6229): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6251 uid=10096 gids={50096, 9997} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6035:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/dex2oat ( 6200): dex2oat took 265.245ms (threads: 4)
,W/libprocessgroup(  891): failed to open /acct/uid_10081/pid_6035/cgroup.procs: No such file or directory
,I/System.out( 6251): TimeService: Loaded Library 
D/TimeService( 6251): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1451923703376
D/        ( 6251): TimeServiceNative: User Time to be set is 1451923703376
D/QC-time-services( 6251): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6251): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6251): Lib:time_genoff_operation: pargs->ts_val = 1451923703376
D/QC-time-services( 6251): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  318): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  318): Daemon:Received base = 2, unit = 1, operation = 0,value = 1451923703376
D/QC-time-services(  318): Daemon:genoff_opr: Base = 2, val = 1451923703376, operation = 0
D/QC-time-services(  318): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/4/116 16:6:56
D/QC-time-services(  318): Daemon:Value read from RTC seconds = 1451923616000
D/QC-time-services(  318): Daemon:new time 1451923703376 
D/QC-time-services(  318): Daemon: delta 87376 genoff 87376 
D/QC-time-services(  318): Daemon:genoff_persistent_update: Writing genoff = 87376 to memory
D/QC-time-services(  318): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  318): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  318): Updating the TOD offset
D/QC-time-services(  318): Daemon:genoff_persistent_update: Writing genoff = 87376 to memory
D/QC-time-services(  318): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  318): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  318): Daemon:Update to modem bit set
D/QC-time-services(  318): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  318): Daemon: Base = 2, Value being sent to MODEM = 18446743757744838992
E/QC-time-services( 6251): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  891): Killing 6130:com.android.chrome/u0a52 (adj 15): empty #7
,E/QC-time-services(  318): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  318): Daemon: Time-services: Waiting to acceptconnection
,W/ContextImpl( 5918): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/dex2oat ( 6286): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=33 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  891): failed to open /acct/uid_10052/pid_6130/cgroup.procs: No such file or directory
,I/GAV2    ( 5918): Thread[GAThread,5,main]: No campaign data found.
,I/CheckinService( 1949): Checkin interval check for package: unspecified last checkin: 1451341491846 min interval config: 0 actual interval: 582212126
,I/dex2oat ( 6286): dex2oat took 332.747ms (threads: 4)
,W/ProcessCpuTracker(  891): Skipping unknown process pid 6295
W/ProcessCpuTracker(  891): Skipping unknown process pid 6296
W/ProcessCpuTracker(  891): Skipping unknown process pid 6302
W/ProcessCpuTracker(  891): Skipping unknown process pid 6303
W/ProcessCpuTracker(  891): Skipping unknown process pid 6308
,I/Adreno-EGL( 6096): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6096): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6096): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6096): Local Branch: 
I/Adreno-EGL( 6096): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6096): Local Patches: NONE
I/Adreno-EGL( 6096): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/GCM-DMM ( 1703): Force release of GOOGLE_C2DM lock
,I/Adreno-EGL( 6096): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6096): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6096): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6096): Local Branch: 
I/Adreno-EGL( 6096): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6096): Local Patches: NONE
I/Adreno-EGL( 6096): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  891): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=6322 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     ( 5005): Explicit concurrent mark sweep GC freed 2913(114KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 346us total 102.247ms
,W/art     ( 6163): Attempt to remove local handle scope entry from IRT, ignoring
,I/GAv4    ( 6322): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6322):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6322):   adb logcat -s GAv4
,W/GAv4    ( 6322): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 6096): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6096): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6096): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6096): Local Branch: 
I/Adreno-EGL( 6096): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6096): Local Patches: NONE
I/Adreno-EGL( 6096): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/Volley  ( 1949): [177] BasicNetwork.performRequest: Unexpected response code 410 for https://www.googleapis.com/plus/v2whitelisted/people/me/people/all?prettyPrint=false&fields=items(etag,id,names,nicknames,images,urls,sortKeys,taglines,emails,phoneNumbers,addresses,metadata,memberships,legacyFields/mobileOwnerId),nextPageToken,nextSyncToken&customResponseMaskingType=menagerie&includeAffinity=gplusAutocomplete&includeAffinity=chatAutocomplete&includeAffinity=emailAutocomplete&includeOthers=true&maxResults=100&orderBy=modified&syncToken=CLnt7YmeKhIBMRjeEioECAEQAQ
,I/PeopleSync( 1949): Sync Token out of date, syncing all people/gaia-map
,W/GAv4    ( 6322): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6322): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 6096): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6096): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6096): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6096): Local Branch: 
I/Adreno-EGL( 6096): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6096): Local Patches: NONE
I/Adreno-EGL( 6096): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  891): Killing 6202:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10007/pid_6202/cgroup.procs: No such file or directory
,D/OtaApp  ( 2615): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2615): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2615): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  891): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,D/OtaApp  ( 2615): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2615): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2615): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2615): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2615): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2615): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2615): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2615): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1416): onFinishInput()
,W/IInputConnectionWrapper( 5431): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  891): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,151
,I/ActivityManager(  891): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6364 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/WVCdm   (  297): Instantiating CDM.
,I/WVCdm   (  297): CdmEngine::OpenSession
,I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  297): App is not loaded in QSEE
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe4000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe4000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb54bf960
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb760d3a8, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb761c010, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb776a7e0, idLength=0xb55bf730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=1513531664
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7630d58
D/DrmWidevineDash(  297): message_length=1626, signature=0xb760d3f0, signature_length=3042703124
,I/PeopleSync( 1949): Sync finished, successful=true, took 6003ms
,I/PeopleContactsSync( 1949): CP2 sync start [5005f081]
,I/PhenotypeConfigurator( 1703): Scheduling Phenotype for one-off execution 11208 seconds from now (1451923705941)
,D/GetConfigurationSnapshotOperation( 1703): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
,D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/PeopleContactsSync( 1949): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/CheckinRequestBuilder( 1949): Classify the device as Phone.
,I/PeopleContactsSync( 1949): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/ActivityManager(  891): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6389 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/DictionaryProvider:UpdateHandler( 1416): downloadFinished() : DownloadId = 88
,I/ActivityManager(  891): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6415 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/PhenotypeFlagCommitter( 1703): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/ActivityManager(  891): Killing 6229:com.motorola.context/u0a8 (adj 15): empty #7
,I/GoogleURLConnFactory( 1703): Using platform SSLCertificateSocketFactory
,I/ContactLocale( 6389): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  891): failed to open /acct/uid_10008/pid_6229/cgroup.procs: No such file or directory
,W/ResourcesManager( 6415): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ConfigService( 1703): onCreate
,I/PeopleContactsSync( 1949): CP2 cleanup done, kept= duration=413 ms
,I/CheckinTask( 1949): Sending checkin request (10517 bytes)
,I/art     (  891): Explicit concurrent mark sweep GC freed 23825(1092KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.596ms total 125.029ms
,I/ActivityManager(  891): Killing 5918:com.google.android.calendar/u0a49 (adj 15): empty #7
,I/PeopleContactsSync( 1949): ===CP2 sync finished, success=true, time=544,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,W/libprocessgroup(  891): failed to open /acct/uid_10049/pid_5918/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Killing 6251:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,I/PeopleSync( 1949): ***Sync finished***, duration: 9219 [5005f081]
,W/libprocessgroup(  891): failed to open /acct/uid_10096/pid_6251/cgroup.procs: No such file or directory
,I/GoogleURLConnFactory( 1949): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel_SMS( 6415): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6415): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6415): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6415): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6415): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6415): MmsConfig.loadFromResources
E/Babel_SMS( 6415): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6415): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/CheckinRequestBuilder( 1949): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1949): Failed to find provider info for com.google.android.wearable.settings
,I/GCoreUlr( 1703): Uploading GCM registration ID for account#2#
,W/Settings( 6415): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/BaseAppContext( 1703): Using Auth Proxy for data requests.
,I/Babel_Crash( 6415): startup - clean
,E/BaseAppContext( 1703): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/Babel   ( 6415): deleted: false for 0
,I/GCM     ( 1949): Message from null null
,E/GCM     ( 1949): Dropping message from null
,W/VideoCapabilities( 6415): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6415): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6415): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6415): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6415): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6415): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6415): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6415): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6415): onServiceConnected
,W/Babel   ( 6415): Attempted to change video mute state without an active call.
,I/CheckinRequestBuilder( 1949): Classify the device as Phone.
,I/CheckinTask( 1949): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1949): Checking schedule, now: 1451923707399 next: 1452524844391
I/CheckinService( 1949): active receiver: disabled
,D/CheckinService( 1949): Recording last checkin time for package unspecified as 1451923707435
,I/SundryService( 2615): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
I/SundryService( 2615): Received shoulder tap
,I/ActivityManager(  891): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6461 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/WaitableIntentService( 2615): setWaitEnabled(): mWaitCount=2 isWaitEnabled=true
,D/GetNotificationsWS( 2615): GetNotificationsWS.Request: message={"request":{"wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","requestFormat":"json","httpMethod":"post","baseUrl":"v1\/gns\/list\/messages","isSecure":true,"useOAuth":true,"retries":"-1","appendDeviceId":true,"queryParams":{"appid":"6R1TANEX3ZMQ6EU1UH43P34C8B868KTE"},"payload":{"type":"json","data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}"}}}
,D/GetNotificationsWS( 2615): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 2615): ServiceHandler.handleMessage: mWaitCount=2
,D/MMApiWebService( 2615): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,W/ResourcesManager( 6461): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=6479 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DictionaryProvider:UpdateHandler( 1416): downloadFinished() : Success = true
I/DictionaryProvider:UpdateHandler( 1416): downloadFinished() : Metadata Success
,I/art     ( 2615): Explicit concurrent mark sweep GC freed 46177(2MB) AllocSpace objects, 7(158KB) LOS objects, 40% free, 11MB/19MB, paused 1.652ms total 105.217ms
,I/ActivityManager(  891): Killing 6322:com.google.android.deskclock/u0a55 (adj 15): empty #7
,I/Keyboard.Facilitator( 1416): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1416): run()
,I/Decoder ( 1416): createOrResetDecoder
,I/MMApiWSBase( 2615): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  891): failed to open /acct/uid_10055/pid_6322/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): run()
,E/SQLiteLog( 6479): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = history
,I/ActivityManager(  891): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6503 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = user
,I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1548): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6503): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6503): Created com.android.providers.calendar.CalendarAlarmManager@2e0fd266(com.android.providers.calendar.CalendarProvider2@fbbd9a7)
,D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  891): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  891): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1416): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1416): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1416): run()
I/StatsUtilsManager( 1416): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1416): shouldRecordStats() = Too Soon
,I/Launcher( 1566): Deferring update until onResume
,D/TaskPersister(  891): removeObsoleteFile: deleting file=2_task.xml
,V/BackupManagerService(  891): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  891): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@316f9b29
,I/GCoreNlp( 1703): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/MMApiWSBase( 2615): doRequest(): v1/gns/list/messages resp length: 1363
D/CCE     ( 2615): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
D/CCE     ( 2615): AppWSProxy - sendAIDLWSResponse() sending reponse
D/Checkin ( 2615): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 2615): handleGetNotificationsResponse(): got 0; more=false
,I/SundryService( 2615): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 2615): setWaitEnabled(): mWaitCount=1 isWaitEnabled=false
D/SundryService( 2615): onHandleIntent(): isWaitEnabled=true
D/WaitableIntentService( 2615): ServiceHandler.handleMessage: mWaitCount=1
,I/AnalyticsLogBase( 6479): PlayLogger.onLoggerConnected
,W/SQLiteConnectionPool( 1949): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/art     ( 1703): Background sticky concurrent mark sweep GC freed 113564(6MB) AllocSpace objects, 35(560KB) LOS objects, 32% free, 15MB/22MB, paused 10.817ms total 124.464ms
,I/ActivityManager(  891): Killing 6364:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@ebe2edd)
E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@152f7a52)
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29e84123)
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1fce9620)
E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3973dbd9)
E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2626e99e)
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@27f3cc7f)
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3456f44c)
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@63d5c95)
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@a9401aa)
,I/art     ( 1703): Explicit concurrent mark sweep GC freed 30513(1388KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 13MB/23MB, paused 1.288ms total 91.518ms
,I/ActivityManager(  891): Killing 5769:com.google.android.youtube/u0a101 (adj 15): empty #8
,I/DictionaryProvider:UpdateHandler( 1416): downloadFinished() : Success = true
I/DictionaryProvider:UpdateHandler( 1416): downloadFinished() : Metadata Success
,W/libprocessgroup(  891): failed to open /acct/uid_10101/pid_5769/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator( 1416): resetDictionaries() : en_US
,W/libprocessgroup(  891): failed to open /acct/uid_10088/pid_6364/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator.DecoderInitializer( 1416): run()
,I/Decoder ( 1416): createOrResetDecoder
,D/WearableService( 1703): callingUid 10016, callindPid: 1703
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): run()
,D/AuthorizationBluetoothService( 1703): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1949): Restart initialization of location
,E/MDM     ( 1703): [179] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ActivityManager(  891): Killing 6389:android.process.acore/u0a7 (adj 15): empty #7
,W/DataUsage( 2615): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2615): publish the event [tag = MOT_CCE event name = LOG]
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = contacts
,W/libprocessgroup(  891): failed to open /acct/uid_10007/pid_6389/cgroup.procs: No such file or directory
V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  891): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6543 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  891): Explicit concurrent mark sweep GC freed 26771(1279KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 2.352ms total 126.926ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1416): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1416): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1416): run()
I/StatsUtilsManager( 1416): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1416): shouldRecordStats() = Too Soon
,W/GCoreFlp( 1703): No location to return for getLastLocation()
,W/FusedLocationProvider( 1703): location=null
,D/ChimeraCfgMgr( 1949): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1949): Module APK com.google.android.play.games already loaded
,W/PlaySystemBroadcastReceiver( 1949): Processed handlePeopleChanged at 373640
,D/ChimeraCfgMgr( 1949): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1949): Module APK com.google.android.play.games already loaded
,I/GCoreUlr( 1703): GCM ID uploaded for account#2#
,I/Gmail   ( 6543): getAccountsCursor
,W/DataBroker( 1949): No player ID found and calling context is not the dest app
,I/ActivityManager(  891): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6573 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 377us total 25.848ms
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityThread( 6543): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 25.409ms
,I/GCoreUlr( 1703): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 409us total 23.595ms
,I/ActivityManager(  891): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=6592 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CalendarProvider2( 6503): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6503): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/GCoreUlr( 1703): DispatchingService.onCreate()
,W/ActivityManager(  891): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 6543): Observing account changes for notifications
,W/GAV2    ( 6543): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Exchange( 6592): EasService.onCreate
,D/PhoneMonitor( 6573): Register our PhoneStateListener
,E/SQLiteLog( 1949): (284) automatic index on invitations(external_inviter_id)
,I/ActivityManager(  891): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6619 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/Exchange( 6592): RestartPingTask
,I/Exchange( 6592): RestartPingsTask did not start any pings.
I/Exchange( 6592): PSS stopIfIdle
I/Exchange( 6592): PSS has no active accounts; stopping service.
,I/Gmail   ( 6543): getAccountsCursor
,V/SetupWizard( 6573): Connected to Gservices successfully
,W/Gmail   ( 6543): Sync started for account: account:61035162
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 6592): onDestroy
,I/ActivityManager(  891): Killing 6163:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/GCoreUlr( 1703): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/libprocessgroup(  891): failed to open /acct/uid_10090/pid_6163/cgroup.procs: No such file or directory
,D/GCM     ( 1703): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/SQLiteLog( 6543): (283) recovered 112 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/ActivityManager(  891): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6649 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1703): Unbound from all location providers
I/GCoreUlr( 1703): Place inference reporting - stopped
,I/GCoreUlr( 1703): DispatchingService.onDestroy()
I/GCoreUlr( 1703): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1703): Unbound from all location providers
I/GCoreUlr( 1703): Place inference reporting - stopped
,I/ActivityManager(  891): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6668 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ContactLocale( 6668): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  891): Killing 6415:com.google.android.talk/u0a70 (adj 15): empty #7
,I/GAv4    ( 6619): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6619):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6619):   adb logcat -s GAv4
,W/libprocessgroup(  891): failed to open /acct/uid_10070/pid_6415/cgroup.procs: No such file or directory
,W/GAv4    ( 6619): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6619): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6619): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 6619): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,I/Gmail   ( 6543): notifyAccountChanged
,I/Gmail   ( 6543): getAccountsCursor
,I/Gmail   ( 6543): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6543): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6543): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6543): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  891): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6701 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6719 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6461:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10008/pid_6461/cgroup.procs: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6619): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,I/ActivityManager(  891): Killing 6503:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/ResourcesManager( 6719): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Gmail   ( 6543): notifyAccountChanged
,W/ResourcesManager( 6619): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6619): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6619): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6619): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  891): failed to open /acct/uid_10005/pid_6503/cgroup.procs: No such file or directory
,I/art     ( 5005): Explicit concurrent mark sweep GC freed 3098(125KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 391us total 37.819ms
,V/JNIHelp ( 6619): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  891): Killing 6573:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/System  ( 6619): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6619): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  891): failed to open /acct/uid_10035/pid_6573/cgroup.procs: No such file or directory
,I/Babel_SMS( 6719): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6719): MmsConfig.loadMmsSettings
I/Babel_SMS( 6719): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6719): MmsConfig.loadFromDatabase
,D/WifiService(  891): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@11559ef6}
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel_SMS( 6719): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6719): MmsConfig.loadFromResources
E/Babel_SMS( 6719): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6719): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Flag    ( 6619): Duration spec must be at least 2 characters long
,I/art     (  891): Explicit concurrent mark sweep GC freed 18982(927KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.277ms total 137.122ms
,W/Settings( 6719): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6719): startup - clean
,I/Babel   ( 6719): deleted: false for 0
,I/Gmail   ( 6543): getAccountsCursor
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/VideoCapabilities( 6719): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  891): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6760 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6719): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6719): Unsupported mime video/mpeg2
,I/Gmail   ( 6543): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 13763, normalSync: true
,W/asset   ( 6760): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6760): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6760): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6760): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 6719): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6719): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6719): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6719): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6719): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6719): onServiceConnected
W/Babel   ( 6719): Attempted to change video mute state without an active call.
,D/PackageBroadcastService( 1949): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1949): Null package name or gms related package.  Ignoreing.
,W/ResourcesManager( 6719): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 6649): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1566): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@217cc83e new=com.google.android.velvet.VelvetApplication@217cc83e
,W/ResourcesManager( 6719): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Icing   ( 1949): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  891): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6792 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/JNIHelp ( 6719): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 6543): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6543): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6792): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/System  ( 6719): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6719): Installed default security provider GmsCore_OpenSSL
,I/UpdateIcingCorporaServi( 6649): UpdateCorporaTask done [took 187 ms] updated apps [took 186 ms] 
,I/ActivityManager(  891): Killing 6592:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,V/JNIHelp ( 6543): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 6543): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6543): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  891): failed to open /acct/uid_10060/pid_6592/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  891): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6823 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6701:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10019/pid_6701/cgroup.procs: No such file or directory
,D/Finsky  ( 6823): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/art     ( 6719): Attempt to remove local handle scope entry from IRT, ignoring
,W/ContextImpl( 6479): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 6479): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 6823): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Settings( 6823): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6823): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 6823): Skipping gmscore version check
,D/Finsky  ( 6823): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6823): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  891): Killing 6096:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/Icing   ( 1949): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,W/libprocessgroup(  891): failed to open /acct/uid_10016/pid_6096/cgroup.procs: No such file or directory
,I/SundryService( 2615): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 2615): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 2615): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 2615): ServiceHandler.handleMessage: mWaitCount=0
,D/Finsky  ( 6823): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  891): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6900 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 1949): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,D/GetNotificationsWS( 2615): unbindWebServices(): un-registering our AIDL callback...
,D/Finsky  ( 6823): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  891): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6919 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 23.210ms
,W/ResourcesManager( 6900): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 20.285ms
,W/ResourcesManager( 6919): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.523ms
,I/CalendarProvider2( 6900): Created com.android.providers.calendar.CalendarAlarmManager@2e0fd266(com.android.providers.calendar.CalendarProvider2@fbbd9a7)
,I/ActivityManager(  891): Killing 6760:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,D/WifiService(  891): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@11559ef6}
,W/libprocessgroup(  891): failed to open /acct/uid_10027/pid_6760/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Killing 6649:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10039/pid_6649/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=6945 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6719): Note: end time exceeds epoch: 
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6945): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6945): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,V/AlarmManager(  891): send {142e2a20, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  891): done {142e2a20, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [4ms]
D/Finsky  ( 6823): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/GAv4    ( 6945): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6945):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6945):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6945): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 6719): Account registration complete:1-Redacted-21
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6945): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6945): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 6719): ProcessRegisterDeviceResponse
I/Babel   ( 6719): Perform warm sync in case there are messages missed before the device is registered for account Redacted-21
,V/AlarmManager(  891): send {3a7ce25, *walarm*:com.google.android.apps.hangouts.SYNC}
,W/GAv4    ( 6945): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/ConfigService( 1703): onDestroy
W/GAv4    ( 6945): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  891): done {3a7ce25, *walarm*:com.google.android.apps.hangouts.SYNC} [23ms]
,I/art     (  891): Explicit concurrent mark sweep GC freed 17497(875KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.520ms total 117.506ms
,W/Herrevad( 1703): mobile connection type with no cell id
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 6900): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6900): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/WebViewFactory( 6945): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6945): Time to load native libraries: 1 ms (timestamps 8838-8839)
I/LibraryLoader( 6945): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6945): Binding Chromium to main looper Looper (main, tid 1) {236e2081}
,I/LibraryLoader( 6945): Expected native library version number "",actual native library version number ""
I/chromium( 6945): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6945): Initializing chromium process, singleProcess=true
,W/art     ( 6945): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6945): ApplicationContext is null in ApplicationStatus
,W/chromium( 6945): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6945): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6945): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6945): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6945): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6945): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6945): Local Branch: 
I/Adreno-EGL( 6945): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6945): Local Patches: NONE
I/Adreno-EGL( 6945): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AudioManagerAndroid( 6945): Requires BLUETOOTH permission
,I/NSApplication( 6945): Starting up...
,I/qtaguid ( 6823): Failed write_ctrl(u 40) res=-1 errno=22
,I/qtaguid ( 6823): Untagging socket 40 failed errno=-22
W/NetworkManagementSocketTagger( 6823): untagSocket(40) failed with errno -22
,D/Finsky  ( 6823): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/SyncAdapterService( 6945): Ignoring sync request for non-current account
,I/ActivityManager(  891): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7041 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 6543): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  891): Killing 6668:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10007/pid_6668/cgroup.procs: No such file or directory
,W/ResourcesManager( 7041): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7041): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Start proc com.google.android.apps.docs.editors.sheets for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService: pid=7061 uid=10105 gids={50105, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MultiDex( 7041): VM with version 2.1.0 has multidex support
I/MultiDex( 7041): install
I/MultiDex( 7041): VM has multidex support, MultiDex support library is disabled.
,E/Babel   ( 6719): Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
E/Babel   ( 6719): Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
,V/JNIHelp ( 7041): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 6823): Failed write_ctrl(u 40) res=-1 errno=22
,I/qtaguid ( 6823): Untagging socket 40 failed errno=-22
W/NetworkManagementSocketTagger( 6823): untagSocket(40) failed with errno -22
,W/ActivityThread( 7041): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7041): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1987d111: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7041): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1703): callingUid 10016, callindPid: 1703
,E/MDM     ( 1703): [207] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1949): Restart initialization of location
,D/AuthorizationBluetoothService( 1703): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 7041): Reading stored module config
W/GCoreFlp( 1703): No location to return for getLastLocation()
W/FusedLocationProvider( 1703): location=null
,D/ChimeraCfgMgr( 7041): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/art     ( 6543): Explicit concurrent mark sweep GC freed 110980(3MB) AllocSpace objects, 0(0B) LOS objects, 25% free, 10MB/14MB, paused 689us total 81.957ms
,I/Gmail   ( 6543): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 13938, normalSync: true
I/Gmail   ( 6543): lowestBackward conversation id 0
,D/CAR.SERVICE( 7041): Connecting to CarCallService...
,I/art     ( 7041): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7041): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7041): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 7041): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 7041): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 7041): Creating a new PhoneAdapter instance
,W/ActivityManager(  891): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 7041): setListener: com.google.android.gms.car.dn@32bcdf14
,W/ActivityManager(  891): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 7041): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 7041): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 7041): Package validated; name: com.android.vending
,V/Finsky  ( 6823): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/Gmail   ( 6543): notifyAccountChanged
,I/Gmail   ( 6543): getAccountsCursor
,I/art     ( 6719): Note: end time exceeds epoch: 
V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6543): notifyAccountChanged
,W/Gmail   ( 6543): Sync complete for account: account:61035162
,I/Gmail   ( 6543): getAccountsCursor
,I/ActivityManager(  891): Killing 6792:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  891): failed to open /acct/uid_10090/pid_6792/cgroup.procs: No such file or directory
,I/GoogleHttpClient( 5005): GMS http client unavailable, use old client
,I/ActivityManager(  891): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7108 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/GAv4    ( 7061): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7061):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7061):   adb logcat -s GAv4
,W/GAv4    ( 7061): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7061): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7061): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ContactLocale( 7108): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
W/AnalyticsTrackerProxyImpl( 7061): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.312.11.30
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 7061): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs.editors.sheets/databases/DocList.db-wal
,W/art     ( 7061): Suspending all threads took: 13.314ms
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 6823): Failed write_ctrl(u 40) res=-1 errno=22
I/qtaguid ( 6823): Untagging socket 40 failed errno=-22
W/NetworkManagementSocketTagger( 6823): untagSocket(40) failed with errno -22
,D/Finsky  ( 6823): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.googlequicksearchbox to true
,D/Finsky  ( 6823): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.googlequicksearchbox from  to d_AAAAAAADF8w=
,D/WifiService(  891): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@3a0f0907}
,W/ResourcesManager( 6823): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6823): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1949): Indexing 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A from com.google.android.gm
,W/ResourcesManager( 7061): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7061): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ValidateNoPeople(  891): mEvictionCount: 0
,V/JNIHelp ( 7061): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Flag    ( 7061): Duration spec must be at least 2 characters long
,I/art     (  891): Explicit concurrent mark sweep GC freed 21812(915KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.044ms total 130.160ms
,I/Gmail   ( 6543): Backfilling search sequence table
,I/ProviderInstaller( 7061): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 6823): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/Icing   ( 1949): Content incarnation mismatch: Expected [47d163a23208aa33] found [f48abb81d7d48b02]
I/Icing   ( 1949): Indexing done 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A
,E/Icing   ( 1949): Aborting indexing of corpus messages/com.google/thalitester%40gmail.com
,I/Icing   ( 1949): Removing corpus key 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A for package com.google.android.gm
,D/Finsky  ( 6823): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  891): send {1ca3cf1b, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,V/AlarmManager(  891): done {1ca3cf1b, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [69ms]
,D/DeviceConnectionService( 1703): client connected with version: 8296000
,D/Finsky  ( 6823): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
D/Finsky  ( 6823): [790] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6823): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,D/Finsky  ( 6823): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 6823): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/Finsky  ( 6823): [791] VerifyInstalledPackagesTask.doInBackground$4f3371dc: Adding com.google.android.apps.docs.editors.sheets for verification
,D/Finsky  ( 6823): [791] VerifyInstalledPackagesTask.doInBackground$4f3371dc: Adding com.google.android.apps.messaging for verification
,E/SQLiteLog( 7108): (284) automatic index on sqlite_sq_B80C0F50(STAT_DATA_ID)
D/Finsky  ( 6823): [791] VerifyInstalledPackagesTask.doInBackground$4f3371dc: Adding com.google.android.apps.genie.geniewidget for verification
,D/Finsky  ( 6823): [791] VerifyInstalledPackagesTask.doInBackground$4f3371dc: Adding com.google.android.apps.fitness for verification
E/SQLiteLog( 7108): (284) automatic index on sqlite_sq_B80C2228(STAT_DATA_ID)
,D/Finsky  ( 6823): [791] VerifyInstalledPackagesTask.doInBackground$4f3371dc: Adding com.google.android.GoogleCamera for verification
,D/Finsky  ( 6823): [791] VerifyInstalledPackagesTask.doInBackground$4f3371dc: Adding com.google.earth for verification
,E/SQLiteLog( 7108): (284) automatic index on sqlite_sq_B801D9B8(STAT_DATA_ID)
,E/SQLiteLog( 7108): (284) automatic index on sqlite_sq_B80C7A58(STAT_DATA_ID)
,I/ActivityManager(  891): Killing 6619:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10057/pid_6619/cgroup.procs: No such file or directory
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 5005): Explicit concurrent mark sweep GC freed 14623(755KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 7MB/13MB, paused 822us total 42.657ms
,I/Icing   ( 1949): Indexing 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A from com.google.android.gm
,I/Icing   ( 1949): Indexing done 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A
,I/ActivityManager(  891): Killing 6919:com.motorola.context/u0a8 (adj 15): empty #7
,I/ActivityManager(  891): Killing 6900:com.android.providers.calendar/u0a5 (adj 15): empty #8
,W/libprocessgroup(  891): failed to open /acct/uid_10008/pid_6919/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_10005/pid_6900/cgroup.procs: No such file or directory
,W/BaseAppContext( 1949): Using Auth Proxy for data requests.
,W/BaseAppContext( 1949): Using Auth Proxy for data requests.
,W/BaseAppContext( 1949): Using Auth Proxy for data requests.
W/BaseAppContext( 1949): Using Auth Proxy for data requests.
,W/BaseAppContext( 1949): Using Auth Proxy for data requests.
,W/BaseAppContext( 1949): Using Auth Proxy for data requests.
,W/BaseAppContext( 1949): Using Auth Proxy for data requests.
,I/ActivityManager(  891): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=7192 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MusicStore( 7192): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7192): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7192): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7192): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7192): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7192): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7192): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7192): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7192): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@fcd61b0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7192): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7192): GMSCore installation verified
,I/ConfigStore( 7192): Config Database version: 1
,I/ActivityManager(  891): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7221 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7221): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/WifiService(  891): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@3a0f0907}
,I/ActivityManager(  891): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=7252 uid=10053 gids={50053, 9997, 3003, 1028} abi=armeabi-v7a
,I/CalendarProvider2( 7221): Created com.android.providers.calendar.CalendarAlarmManager@2e0fd266(com.android.providers.calendar.CalendarProvider2@fbbd9a7)
,I/MediaRouter( 7192): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 7192): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7192): Using platform SSLCertificateSocketFactory
,I/NetworkMonitor( 7192): type=WIFI subType= reason=null isConnected=true
,I/MusicLifecycle( 7192): Sync started
,I/NetworkMonitor( 7192): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 7192): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7192): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  891): Start proc com.google.android.apps.cloudprint for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService: pid=7278 uid=10053 gids={50053, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6945:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10081/pid_6945/cgroup.procs: No such file or directory
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 7252): Sync request not initiated by GCP app. Dropping
,I/ActivityManager(  891): Killing 7041:com.google.android.gms:car/u0a16 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10016/pid_7041/cgroup.procs: No such file or directory
W/ActivityManager(  891): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  891): Killing 6823:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10032/pid_6823/cgroup.procs: No such file or directory
,E/Auth.Api.Credentials( 1949): [CredentialSyncAdapter] Unknown sync event.
,I/RemindersSync( 1949): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=303:priority=5:group=main]
,W/AbstractGoogleClient( 6479): Application name is not set. Call Builder#setApplicationName.
,I/art     (  891): Explicit concurrent mark sweep GC freed 21070(972KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 20MB/30MB, paused 1.606ms total 141.520ms
,I/AnalyticsLogBase( 6479): PlayLogger.onLoggerConnected
,I/MusicSyncAdapter( 7192): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 7192): Periodic update
,W/MusicApiClient( 7192): Activity events list is null or empty. Skip reporting.
,I/ActivityManager(  891): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=7321 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NDK_Model( 7061): setting up template
,I/MusicLifecycle( 7192): Sync ended
,I/CalendarProvider2( 7221): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 7221): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  891): Killing 7108:android.process.acore/u0a7 (adj 15): empty #7
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=274, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309337, SEQNUM=4480, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-768, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/libprocessgroup(  891): failed to open /acct/uid_10007/pid_7108/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,I/art     ( 5005): Explicit concurrent mark sweep GC freed 4378(177KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 386us total 25.408ms
,D/Finsky  ( 7321): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7321): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7321): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/NDK_Model( 7061): Compile Source0
W/Settings( 7321): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7321): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7321): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7321): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Ads     ( 7321): Skipping gmscore version check
,D/Finsky  ( 7321): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7192): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/JSVM    ( 7061): Starting JSVM with App Version: explorer_2015-50-Thu_RC2
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7192): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/cache
,I/ActivityManager(  891): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=7377 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/MusicLeanback( 7192): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 7192): Stop autocaching.
W/ResourcesManager( 7377): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Killing 6543:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10063/pid_6543/cgroup.procs: No such file or directory
,I/CalendarSyncAdapter( 6479): Found no pending settings
,D/WearableService( 1703): callingUid 10016, callindPid: 1703
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7192): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/cache
,I/ActivityManager(  891): Killing 7061:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10105/pid_7061/cgroup.procs: No such file or directory
,E/GmsUtils( 7192): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 7192): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  891): Killing 7278:com.google.android.apps.cloudprint/u0a53 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10053/pid_7278/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Killing 6719:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10070/pid_6719/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  891): Waited long enough for: ServiceRecord{3dbdc0e5 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/MusicLeanback( 7192): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 7192): Stop autocaching.
,E/GmsUtils( 7192): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7192): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/AlarmManager(  891): send {1e09452d, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED}
V/AlarmManager(  891): send {74e2cf1, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  891): done {1e09452d, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED} [2ms]
,V/AlarmManager(  891): done {74e2cf1, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/ActivityManager(  891): Killing 7321:com.android.vending/u0a32 (adj 15): empty #7
,I/ActivityManager(  891): Killing 7252:com.google.android.apps.cloudprint:sync/u0a53 (adj 15): empty #8
,W/libprocessgroup(  891): failed to open /acct/uid_10032/pid_7321/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_10053/pid_7252/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7444 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  891): send {2160c0d6, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
V/AlarmManager(  891): done {2160c0d6, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [42ms]
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 37.399ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 5.805ms total 37.759ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 42.227ms
,D/Finsky  ( 7444): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7444): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7444): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7444): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7444): Skipping gmscore version check
,D/Finsky  ( 7444): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7444): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7444): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7444): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Finsky  ( 7444): [845] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7444): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  891): Killing 7377:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10008/pid_7377/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310292, SEQNUM=4497, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-822, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ActivityManager(  891): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7510 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ContactLocale( 7510): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/IcingInternalCorpora( 1949): getNumBytesRead when not calculated.
,I/ActivityManager(  891): Killing 7221:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10005/pid_7221/cgroup.procs: No such file or directory
,I/art     ( 1703): Explicit concurrent mark sweep GC freed 76200(4MB) AllocSpace objects, 36(573KB) LOS objects, 39% free, 14MB/24MB, paused 1.472ms total 116.735ms
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@31a8768b)
E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@335b0368)
E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@233a5381)
E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1c0d0c26)
,E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@36a5f067)
E/DataBuffer( 1703): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2a90ee14)
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  891): send {163f07bd, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  891): send {74e2cf1, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  891): done {74e2cf1, *walarm*:android.content.syncmanager.SYNC_ALARM} [18ms]
,V/AlarmManager(  891): done {163f07bd, *alarm*:android.intent.action.TIME_TICK} [58ms]
,D/ChimeraCfgMgr( 1949): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1949): Module APK com.google.android.play.games already loaded
,E/ActivityThread( 1949): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  891): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 484998, reason: UserStart
,I/ActivityManager(  891): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7553 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 1949): 0 accounts found with uca feature
,I/GamesSyncAdapter( 1949): Starting sync for 3a3529a
,I/GamesSyncAdapter( 1949): Sync duration for 3a3529a: 8
,D/ChimeraCfgMgr( 1949): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1949): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  891): Start proc com.google.android.apps.docs.editors.sheets for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService: pid=7576 uid=10105 gids={50105, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ChimeraCfgMgr( 1949): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1949): Module APK com.google.android.play.games already loaded
,I/art     (  891): Explicit concurrent mark sweep GC freed 22345(991KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.547ms total 114.776ms
,I/GAv4    ( 7553): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7553):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7553):   adb logcat -s GAv4
,W/GAv4    ( 7553): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7553): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7553): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7553): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteLog( 7553): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7553): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 7553): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7553): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7553): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7553): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GAv4    ( 7576): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7576):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7576):   adb logcat -s GAv4
,W/GAv4    ( 7576): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/JNIHelp ( 7553): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/GAv4    ( 7576): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7576): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7576): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.312.11.30
,W/System  ( 7553): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7553): Installed default security provider GmsCore_OpenSSL
,E/SQLiteLog( 7576): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs.editors.sheets/databases/DocList.db-wal
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  891): Killing 6479:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10049/pid_6479/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Killing 7192:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10080/pid_7192/cgroup.procs: No such file or directory
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 7576): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7576): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7576): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 7576): Installed default security provider GmsCore_OpenSSL
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=251, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310483, SEQNUM=4509, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11919, POWER_SUPPLY_CHARGE_COUNTER=-884, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=245, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310690, SEQNUM=4511, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10316, POWER_SUPPLY_CHARGE_COUNTER=-939, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  891): send {74e2cf1, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  891): done {74e2cf1, *walarm*:android.content.syncmanager.SYNC_ALARM} [5ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ClearcutLoggerApiImpl( 1703): disconnect managed GoogleApiClient
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ClearcutLoggerApiImpl( 1949): disconnect managed GoogleApiClient
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  891): send {163f07bd, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  891): send {22211445, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  891): done {22211445, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [10ms]
,V/AlarmManager(  891): done {163f07bd, *alarm*:android.intent.action.TIME_TICK} [108ms]
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=238, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310578, SEQNUM=4515, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10316, POWER_SUPPLY_CHARGE_COUNTER=-1095, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,D/CdsService( 2615): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/Xb5mJtPfKUzeGqhewQ0g6nb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mTxUo3Y5RyjODPZBCtRHXpNPpl9SM4BEYpQK4G7MDeTuZRU5yyyKyAbMhMkdCLaYwTZ8SdL2xLaAQOoipZ5AD7EbyX2rREts4fN5jGwpa3gLxLQoVImVDRoGbNT%2FBRJJQtG%2BbMMvYzhbn0C8fd7RZjjNzryDfsTVXC3f%2BQldLG9Lpm3q5Y67bZFrymNmP6M4x54iZVBQRiXw4rLlDrSw2USW28w550lg0LVuDqUdj54ZL5aefW%2BdkjHOPasqmqwRFQM8QaoyZ015btHZNXSwmdDFWXFIyUEeXgAVMCjXoE9SE%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/v8NUeCqaV6Z%2B78usC1%2B0eHb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZ
,D/CdsService( 2615): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/Xb5mJtPfKUzeGqhewQ0g6nb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mTxUo3Y5RyjODPZBCtRHXpNPpl9SM4BEYpQK4G7MDeTuZRU5yyyKyAbMhMkdCLaYwTZ8SdL2xLaAQOoipZ5AD7EbyX2rREts4fN5jGwpa3gLxLQoVImVDRoGbNT%2FBRJJQtG%2BbMMvYzhbn0C8fd7RZjjNzryDfsTVXC3f%2BQldLG9Lpm3q5Y67bZFrymNmP6M4x54iZVBQRiXw4rLlDrSw2USW28w550lg0LVuDqUdj54ZL5aefW%2BdkjHOPasqmqwRFQM8QaoyZ015btHZNXSwmdDFWXFIyUEeXgAVMCjXoE9SE%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/v8NUeCqaV6Z%2B78usC1%2B0eHb9
,I/OtaApp  ( 2615): [info] > OTAUpgradeSource.handleCheckWSResponse: check_for_update : 200 : {"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/Xb5mJtPfKUzeGqhewQ0g6nb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mTxUo3Y5RyjODPZBCtRHXpNPpl9SM4BEYpQK4G7MDeTuZRU5yyyKyAbMhMkdCLaYwTZ8SdL2xLaAQOoipZ5AD7EbyX2rREts4fN5jGwpa3gLxLQoVImVDRoGbNT%2FBRJJQtG%2BbMMvYzhbn0C8fd7RZjjNzryDfsTVXC3f%2BQldLG9Lpm3q5Y67bZFrymNmP6M4x54iZVBQRiXw4rLlDrSw2USW28w550lg0LVuDqUdj54ZL5aefW%2BdkjHOPasqmqwRFQM8QaoyZ015btHZNXSwmdDFWXFIyUEeXgAVMCjXoE9SE%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/v8NUeCqaV6Z%2B78usC1%2B0eHb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050W
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2615): [debug] > AndroidPollingManager.handleIntent: com.motorola.blur.service.blur.upgrade_poll
,I/OtaApp  ( 2615): [info] > Next Polling is scheduled at 1439 mins from now
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2615): [debug] > PollingManagerService, registerApp(): cUsPollingService
,D/OtaApp  ( 2615): [debug] > PollingManagerService, registerApp(): shortest interval is 86399000
,I/OtaApp  ( 2615): [info] > CusSM.handleNewVersion: was notified of a new version : src Blur_Version.22.21.28.thea_reteu.reteuall.en.EU: dest Blur_Version.22.46.12.thea_reteu.reteuall.en.EU: current Blur_Version.22.21.28.thea_reteu.reteuall.en.EU: size 263329787: contentTimeStamp 1445419042000
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2615): [info] > Device is NOT rooted. persist.qe=qe 0/0
,D/OtaApp  ( 2615): [debug] > Polling alarm set to expire at: 86927914 Current Time: 528928
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,E/OtaApp  ( 2615): [error] > UpgradeSource.isUpgradeAcceptable succeeded 
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2615): [debug] > prevDestVersion = Blur_Version.22.46.12.thea_reteu.reteuall.en.EU
,W/OtaApp  ( 2615): [warn] > CusSM.handleNewVersion: already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,E/OtaApp  ( 2615): [error] > CusSM.failNotify: notification failed from repository upgrade for reason already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK; additional information: polling initiated upgrade
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2615): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1451923864625, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/OtaApp  ( 2615): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1451923864633, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/OtaApp  ( 2615): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
D/OtaApp  ( 2615): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  NotifiedBlur_Version.22.21.28.thea_reteu.reteuall.en.EUBlur_Version.22.46.12.thea_reteu.reteuall.en.EURepository: upgrade; Location: null; AddOnInfo: polling initiated upgradehttps://motorola-global-en-uk.custhelp.com/app/answers/prod_answer_detail/a_id/1073741451923864643true
,D/OtaApp  ( 2615): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; src: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; dest: Blur_Version.22.46.12.thea_reteu.reteuall.en.EU; upgradeSource:upgrade; Repository: upgrade; Location: null; AddOnInfo: polling initiated upgrade; reportingTag: ; trackingId: 1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E; metaDataVersion: null; ro.carrier: reteu. time: 1451923864
,E/CdsService( 2615): [e] > Failed to parse int value from string null exception :java.lang.NumberFormatException: Invalid int: "null"
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2615): [d] > Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/CdsService( 2615): [d] > State Request getUrl(): url is https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072
,I/OtaApp  ( 2615): [info] > OTAUpgradeSource.handleCheckWSResponse: check_for_update handle new version returned false
I/CdsService( 2615): [i] > Received web service call for request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2615): [d] > appending web service request to serviceHandler
,D/OtaApp  ( 2615): [debug] > BotaFotaResolver.parse got the following check order (bota); assuming only bota is enabled
D/OtaApp  ( 2615): [debug] > OTAUpgradeSource.handleCheckWSResponse: authoritative response from BOTA ERR_NOTFOUND
,D/OtaApp  ( 2615): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/OtaApp  ( 2615): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2615): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2615): [debug] > CusSM.runStateMachine: server told to :wait
D/CdsService( 2615): [d] > appending web service response to serviceHandler
,D/CdsService( 2615): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/check/ctx/ota/key/XT1072 from queue
,D/CdsService( 2615): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}
,D/CdsService( 2615): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}}
,D/OtaApp  ( 2615): [debug] > Inside handleStateResponse
D/OtaApp  ( 2615): [debug] > exec delete from status where _id=1
,D/OtaApp  ( 2615): [debug] > stopTimer, cancel()
,D/OtaApp  ( 2615): [debug] > handleStateResponse server told to : continue
,D/OtaApp  ( 2615): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
D/OtaApp  ( 2615): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  ResultBlur_Version.22.21.28.thea_reteu.reteuall.en.EUBlur_Version.22.46.12.thea_reteu.reteuall.en.EUalready working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OKhttps://motorola-global-en-uk.custhelp.com/app/answers/prod_answer_detail/a_id/1073741451923866215true
,D/OtaApp  ( 2615): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; src: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; dest: Blur_Version.22.46.12.thea_reteu.reteuall.en.EU; upgradeSource:upgrade; already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK; reportingTag: ; trackingId: 1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E; metaDataVersion: null; ro.carrier: reteu. time: 1451923864
,E/CdsService( 2615): [e] > Failed to parse int value from string null exception :java.lang.NumberFormatException: Invalid int: "null"
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2615): [d] > Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/CdsService( 2615): [d] > State Request getUrl(): url is https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072
,I/CdsService( 2615): [i] > Received web service call for request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2615): [d] > appending web service request to serviceHandler
,D/OtaApp  ( 2615): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2615): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2615): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2615): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2615): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2615): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2615): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2615): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  891): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2615): [debug] > CusSM.sendUpgradeStatus: already sending status
D/OtaApp  ( 2615): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/CdsService( 2615): [d] > appending web service response to serviceHandler
,D/CdsService( 2615): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072 from queue
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2615): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2615): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2615): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2615): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2615): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2615): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2615): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2615): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2615): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}
,D/CdsService( 2615): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}}
,D/OtaApp  ( 2615): [debug] > Inside handleStateResponse
D/OtaApp  ( 2615): [debug] > exec delete from status where _id=2
,D/OtaApp  ( 2615): [debug] > stopTimer, have stoped, do nothing
,D/OtaApp  ( 2615): [debug] > handleStateResponse server told to : continue
D/OtaApp  ( 2615): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2615): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2615): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2615): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2615): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2615): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2615): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2615): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2615): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  891): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2615): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2615): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2615): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/OtaApp  ( 2615): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2615): [d] > appending web service response to serviceHandler
,D/OtaApp  ( 2615): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2615): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2615): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072 from queue
D/CdsService( 2615): [d] > No pending web request. shutdown webservice
,D/OtaApp  ( 2615): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2615): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2615): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2615): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,I/CdsService( 2615): [i] > Stopping webservice android service
,D/Checkin ( 2615): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1703): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LaunchCheckinHandler(  891): cleanup(): cleared. Last call was 190704 ms ago
I/ActivityManager(  891): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=7746 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7746): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7746): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7746): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7746): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7746): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 7746): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7746): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/YouTube MDX( 7746): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 7790): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1321260635.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-1321260635.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7746): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/dex2oat ( 7790): dex2oat took 90.935ms (threads: 4)
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7746): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7746): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7746): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 7746): Found 10016
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7746): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  891): Killing 7444:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10032/pid_7444/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  891): send {163f07bd, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  891): send {16a61b39, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  891): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7858 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  891): done {163f07bd, *alarm*:android.intent.action.TIME_TICK} [93ms]
,I/GAv4    ( 7858): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7858):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7858):   adb logcat -s GAv4
,W/GAv4    ( 7858): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7858): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7858): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  891): done {16a61b39, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [292ms]
,I/ActivityManager(  891): Killing 7510:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10007/pid_7510/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  891): send {39808189, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  891): done {39808189, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [8ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ClearcutLoggerApiImpl( 1703): disconnect managed GoogleApiClient
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=229, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309900, SEQNUM=4541, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-15625, POWER_SUPPLY_CHARGE_COUNTER=-2672, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs.editors.sheets/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7576): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs.editors.sheets/files
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/UsageStatsService(  891): User[0] Flushing usage stats to disk
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,V/AlarmManager(  891): send {163f07bd, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  891): send {81b257e, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  891): done {81b257e, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [27ms]
,V/AlarmManager(  891): done {163f07bd, *alarm*:android.intent.action.TIME_TICK} [47ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=225, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310428, SEQNUM=4550, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-3577, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=225, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310410, SEQNUM=4551, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-37, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5491): Disconnected process message: 10, size: 0
,V/AlarmManager(  891): send {163f07bd, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  891): send {39808189, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  891): done {39808189, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [8ms]
,V/AlarmManager(  891): done {163f07bd, *alarm*:android.intent.action.TIME_TICK} [52ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,V/AlarmManager(  891): send {163f07bd, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  891): send {366f8adf, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  891): done {366f8adf, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [23ms]
,V/AlarmManager(  891): done {163f07bd, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:25000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7946): 
D/AndroidRuntime( 7946): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7946): CheckJNI is OFF
D/AndroidRuntime( 7946): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  891): Force stopping com.test.thalitest appid=10407 user=-1: uninstall pkg
I/ActivityManager(  891): Killing 5431:com.test.thalitest/u0a407 (adj 9): stop com.test.thalitest
W/PackageSettings(  891): Skipping PackageSetting{29618a55 com.example.hello/10406} due to missing metadata
D/WifiService(  891): Client connection lost with reason: 4
I/WindowState(  891): WIN DEATH: Window{2202ef69 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  891):   Force finishing activity ActivityRecord{ea0d79a u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  891): Spurious death for ProcessRecord{204431f5 5431:com.test.thalitest/u0a407}, curProc for 5431: null
I/ActivityManager(  891): Force stopping com.test.thalitest appid=10407 user=0: pkg removed
I/ActivityManager(  891):   Force finishing activity ActivityRecord{ea0d79a u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  891): Duplicate finish request for ActivityRecord{ea0d79a u0 com.test.thalitest/.MainActivity t3 f}
I/art     ( 3054): Explicit concurrent mark sweep GC freed 13549(2MB) AllocSpace objects, 35(560KB) LOS objects, 39% free, 7MB/12MB, paused 1.851ms total 44.098ms
I/ProcessStatsService(  891): Prepared write state in 20ms
I/ProcessStatsService(  891): Prepared write state in 7ms
I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1949): Explicit concurrent mark sweep GC freed 17519(1002KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 16MB/21MB, paused 1.087ms total 124.386ms
I/Keyboard.Facilitator( 1416): resetDictionaries() : en_US
W/GeofencerStateMachine( 1703): Ignoring removeGeofence because network location is disabled.
I/art     ( 1566): Explicit concurrent mark sweep GC freed 7689(549KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 518us total 142.236ms
I/Keyboard.Facilitator.DecoderInitializer( 1416): run()
I/Decoder ( 1416): createOrResetDecoder
I/ActivityManager(  891): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7975 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     (  891): Explicit concurrent mark sweep GC freed 30888(1960KB) AllocSpace objects, 10(223KB) LOS objects, 33% free, 20MB/30MB, paused 1.663ms total 154.430ms
I/art     (  891): WaitForGcToComplete blocked for 22.604ms for cause Explicit
I/ConfigService( 1703): onCreate
D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  891): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  891): removeObsoleteFile: deleting file=3_task.xml
I/art     (  891): Explicit concurrent mark sweep GC freed 4963(279KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.636ms total 158.109ms
I/ProcessStatsService(  891): Pruning old procstats: /data/system/procstats/state-2016-01-03-12-00-01.bin
I/CheckinRequestBuilder( 1703): Classify the device as Phone.
D/VoicemailCleanupService( 7975): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  891): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8006 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 7975): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  891): Killing 7553:com.google.android.apps.docs/u0a57 (adj 15): empty #7
D/AndroidRuntime( 7946): Shutting down VM
W/libprocessgroup(  891): failed to open /acct/uid_10057/pid_7553/cgroup.procs: No such file or directory
W/asset   ( 8006): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8006): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8006): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8006): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Launcher( 1566): Deferring update until onResume
I/ActivityManager(  891): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8028 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
W/ContextImpl( 8028): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1949): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1949): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1949): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1949): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1949): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1949): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1949): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1703): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1703): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1949): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1949): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1949): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1949): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1949): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1949): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1949): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1949): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1949): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1949): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1949): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1949): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1949): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  891): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8057 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
V/AlarmManager(  891): send {163f07bd, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  891): send {81b257e, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
I/ActivityManager(  891): Killing 7576:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): run()
V/AlarmManager(  891): send {37488d9b, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
V/AlarmManager(  891): send {5ebb538, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
W/libprocessgroup(  891): failed to open /acct/uid_10105/pid_7576/cgroup.procs: No such file or directory
I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
E/SQLiteLog( 1949): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
V/AlarmManager(  891): send {29fd1a76, *alarm*:com.google.android.gms/.common.download.DownloadAlarmReceiver}
V/AlarmManager(  891): send {87471f2, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1416): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1416): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1416): run()
I/StatsUtilsManager( 1416): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1416): shouldRecordStats() = Too Soon
W/FileUtils( 1949): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 1949): Failed to open Apps corpus file.
I/Icing   ( 1949): doRemovePackageData com.test.thalitest
E/Icing   ( 1949): Failed to open Apps corpus file.
--------- beginning of crash
E/AndroidRuntime( 1949): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1949): Process: com.google.android.gms, PID: 1949
E/AndroidRuntime( 1949): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1949): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1949): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1949): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1949): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1949): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1949): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1949): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1949): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 1949): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1949): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1949): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1949): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1949): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1949): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SharedPreferencesImpl( 1949): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
V/AlarmManager(  891): done {163f07bd, *alarm*:android.intent.action.TIME_TICK} [160ms]
W/Icing   ( 1949): Failed to write entries to Apps corpus file.: java.io.IOException: open failed: EROFS (Read-only file system)
I/Process ( 1949): Sending signal. PID: 1949 SIG: 9
E/DropBoxManagerService(  891): Can't write: system_app_crash
E/DropBoxManagerService(  891): java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  891): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  891): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  891): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  891): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  891): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  891): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  891): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  891): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  891): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  891): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  891): 	... 5 more
D/WifiService(  891): Client connection lost with reason: 4
D/ConnectivityService(  891): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1d96f55a)
D/ConnectivityService(  891): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]

```
