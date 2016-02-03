#### Test 58135655c662d33_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 5432): 
D/AndroidRuntime( 5432): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5432): CheckJNI is OFF
D/AndroidRuntime( 5432): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5451 uid=10500 gids={50500, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5432): Shutting down VM
V/ActivityManager(  882): Display changed displayId=0
W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5451): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5451): Time to load native libraries: 2 ms (timestamps 7516-7518)
,I/LibraryLoader( 5451): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5451): Binding Chromium to main looper Looper (main, tid 1) {3af9f7de}
,I/LibraryLoader( 5451): Expected native library version number "",actual native library version number ""
I/chromium( 5451): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5451): Initializing chromium process, singleProcess=true
,W/art     ( 5451): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5451): ApplicationContext is null in ApplicationStatus
,W/chromium( 5451): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5451): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5451): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5451): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5451): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5451): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5451): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5451): Local Branch: 
I/Adreno-EGL( 5451): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5451): Local Patches: NONE
I/Adreno-EGL( 5451): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21fc6470:true
,D/BluetoothAdapter( 5451): 736244817: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  882): Activity pause timeout for ActivityRecord{33e86535 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 5451): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5451): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5451): CordovaWebView is running on device made by: motorola
,W/art     ( 5451): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5451): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5451): Render dirty regions requested: true
,D/Atlas   ( 5451): Validating map...
,W/chromium( 5451): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5451): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5451): Enabling debug mode 0
,I/Keyboard.Facilitator( 1406): onFinishInput()
,I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,1116
I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +982ms (total +1s116ms)
,W/IInputConnectionWrapper( 5451): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5451): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5451): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5451): Cannot call determinedVisibility() - never saw a connection for the pid: 5451
,D/JsMessageQueue( 5451): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5451): JniHelper::setJavaVM(0xb77fb310), pthread_self() = -1212633384
,I/chromium( 5451): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5451): Initializing JXcore engine
W/jxcore-log( 5451): JXcore engine is ready
,W/Thread-611( 5498): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10500 path="socket:[9859]" dev="sockfs" ino=9859 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-611( 5498): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10500 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-611( 5498): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10500 path="socket:[8521]" dev="sockfs" ino=8521 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-611( 5498): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10500 path="socket:[23283]" dev="sockfs" ino=23283 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5451): Starting JXcore engine
,W/jxcore-log( 5451): Platform android
W/jxcore-log( 5451): 
,W/jxcore-log( 5451): Process ARCH arm
W/jxcore-log( 5451): 
,I/jxcore-log( 5451): JXcore Cordova bridge is ready!
I/jxcore-log( 5451): 
,W/jxcore-log( 5451): JXcore engine is started
,I/jxcore-log( 5451): Toggling radios to true
I/jxcore-log( 5451): 
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  882): enable():  mBluetooth =null mBinding = false
,W/Settings( 1458): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  882): Message: 1
D/BluetoothManagerService(  882): MESSAGE_ENABLE: mBluetooth = null
,W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiService(  882): New client listening to asynchronous messages
,D/WifiService(  882): setWifiEnabled: true pid=5451, uid=10500
E/WifiService(  882): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  882): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5502 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,E/WifiStateMachine(  882): setting operational mode to 1
,W/Settings( 1458): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/jxcore-log( 5451): Radios toggled
I/jxcore-log( 5451): 
,W/Settings( 1458): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1458): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/jxcore-log( 5451): My device name is: motorola-XT1072
I/jxcore-log( 5451): 
,W/ResourcesManager( 5502): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 5502): Adding HeadsetService
,D/AdapterServiceConfig( 5502): Adding A2dpService
D/AdapterServiceConfig( 5502): Adding HidService
D/AdapterServiceConfig( 5502): Adding HealthService
D/AdapterServiceConfig( 5502): Adding PanService
D/AdapterServiceConfig( 5502): Adding GattService
,D/AdapterServiceConfig( 5502): Adding BluetoothMapService
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e801df6:true
D/BluetoothAdapterState( 5502): make
,I/bluedroid( 5502): init
,I/BluetoothAdapterState( 5502): Entering OffState
,I/bte_conf( 5502): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5502): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5502): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5502): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 5502): get_profile_interface socket
I/bluedroid( 5502): get_profile_interface map_client
,I/GKI_LINUX( 5502): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothManagerService(  882): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  882): Message: 40
D/BluetoothManagerService(  882): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 5502): Address is:44:80:EB:7B:5A:05
,D/BluetoothManagerService(  882): Bluetooth Adapter name changed to XT1072
,D/BluetoothManagerService(  882): Stored Bluetooth name: XT1072
,I/bluedroid( 5502): config_hci_snoop_log
D/BluetoothManagerService(  882): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  882): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterProperties( 5502): Name is: XT1072
,D/BluetoothAdapterState( 5502): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 5502): Setting state to 11
I/BluetoothAdapterState( 5502): Bluetooth adapter state changed: 10-> 11
,D/BluetoothBondStateMachine( 5502): make
,D/TCMD    (  482): NL - Read 1008 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
,D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  882): InitialState.processMessage what=4
,D/TCMD    (  482): NL - Read 1008 bytes from update socket.
,D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
I/BluetoothBondStateMachine( 5502): StableState(): Entering Off State
D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothHeadset( 1527): Proxy object connected
D/BluetoothHeadset( 1503): Proxy object connected
,D/BluetoothHeadset(  882): Proxy object connected
,E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
,D/HeadsetService( 5502): Received start request. Starting profile...
,D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothManagerService(  882): Message: 60
D/BluetoothManagerService(  882): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  882): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothHeadsetServiceJni( 5502): classInitNative: succeeds
,D/QsoftapCmd(  291): Got softap fwreload command we are passing on
,D/SoftapController(  291): Softap fwReload - Ok
,D/HeadsetStateMachine( 5502): make
,D/BluetoothHeadset( 1503): Proxy object connected
,D/CommandListener(  291): Setting iface cfg
D/CommandListener(  291): Trying to bring down wlan0
D/CommandListener(  291): Clearing all IP addresses on wlan0
,I/ActivityManager(  882): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5547 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/HeadsetStateMachine( 5502): max_hf_connections = 1
I/bluedroid( 5502): get_profile_interface handsfree
,D/BluetoothAdapterService( 5502): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3af9f7de
,I/BluetoothAdapterState( 5502): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetStateMachine( 5502): Enter Disconnected: -2, size: 0
,D/BluetoothA2dp(  882): Proxy object connected
D/A2dpService( 5502): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 5502): classInitNative: succeeds
I/bluedroid( 5502): get_profile_interface avrcp
,I/wpa_supplicant( 5553): Successfully initialized wpa_supplicant
I/wpa_supplicant( 5553): Long line in configuration file truncated
,I/wpa_supplicant( 5553): rfkill: Cannot open RFKILL control device
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,E/WifiStateMachine(  882): setWifiState: enabling
,E/RemoteController( 5502): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 5502): classInitNative: succeeds
D/A2dpStateMachine( 5502): make
,E/WifiStateMachine(  882): Supplicant start successful
D/WifiMonitor(  882): startMonitoring(wlan0) with mConnected = false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/bluedroid( 5502): get_profile_interface a2dp
,D/Checkin ( 2923): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/GKI_LINUX( 5502): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BluetoothAdapterService( 5502): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3af9f7de
D/A2dpStateMachine( 5502): Enter Disconnected: -2
,D/Checkin ( 2923): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
I/BluetoothHidServiceJni( 5502): classInitNative: succeeds
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/HidService( 5502): Received start request. Starting profile...
I/bluedroid( 5502): get_profile_interface hidhost
,D/BluetoothAdapterService( 5502): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3af9f7de
I/BluetoothHealthServiceJni( 5502): classInitNative: succeeds
,D/HealthService( 5502): Received start request. Starting profile...
,I/bluedroid( 5502): get_profile_interface health
D/BluetoothAdapterService( 5502): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3af9f7de
,I/BluetoothPanServiceJni( 5502): classInitNative(L105): succeeds
,D/PanService( 5502): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5502): initializeNative(L110): pan
,I/bluedroid( 5502): get_profile_interface pan
W/ResourcesManager( 5547): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothAdapterService( 5502): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3af9f7de
,I/BtGatt.JNI( 5502): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 5502): handleDebugAction() action=null
,D/BtGatt.GattService( 5502): Received start request. Starting profile...
D/BtGatt.GattService( 5502): start()
I/bluedroid( 5502): get_profile_interface gatt
,D/BluetoothAdapterService( 5502): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3af9f7de
D/BtGatt.AdvertiseManager( 5502): advertise manager created
,I/libmdmdetect( 5553): ESOC framework not supported
,E/Diag_Lib( 5553):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 5553): baseband property is set to [msm]
I/libmdmdetect( 5553): ESOC framework not supported
,D/BluetoothAdapterService( 5502): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3af9f7de
,D/HeadsetStateMachine( 5502): Proxy object connected
,D/BluetoothMapService( 5502): Received start request. Starting profile...
D/BluetoothMapService( 5502): start()
,D/BluetoothMapEmailSettingsLoader( 5502): Found 0 applications
,E/wpa_supplicant( 5553):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,D/BluetoothMapEmailAppObserver( 5502): createReceiver()
,D/BluetoothMapEmailAppObserver( 5502): initObservers()
D/BluetoothMapEmailAppObserver( 5502): getEnabledAccountItems()
,E/wpa_supplicant( 5553): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5553): card_info[i].card_state: 0x0
E/wpa_supplicant( 5553): card_info[i].error_code: 0x0
E/wpa_supplicant( 5553): SIM/USIM not ready
E/wpa_supplicant( 5553): Error while reading SIM card status
,D/BluetoothAdapterService( 5502): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3af9f7de
,D/HeadsetStateMachine( 5502): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 5502): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 5502): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 5502): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5502): enable
,E/wpa_supplicant( 5553): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5553): card_info[i].card_state: 0x0
E/wpa_supplicant( 5553): card_info[i].error_code: 0x0
E/wpa_supplicant( 5553): SIM/USIM not ready
I/wpa_supplicant( 5553): eap_proxy: Card not ready
,I/GKI_LINUX( 5502): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 5502): init
,I/bt-btu  ( 5502): btu_task pending for preload complete event
,I/bt_vendor( 5502): bt-vendor : init
D/bt_userial_mct( 5502): userial_init
,I/bt_hwcfg( 5502): Starting hciattach daemon
I/bt_hwcfg( 5502): try to set false
,I/bt_hwcfg( 5502): Starting hciattach daemon
I/bt_hwcfg( 5502): try to set true
,I/qcom-bluetooth( 5580): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/ActivityManager(  882): Killing 4968:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/qcom-bluetooth( 5586): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 5587): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 5589): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,E/wpa_supplicant( 5553): Line 31: unknown global field 's'.
E/wpa_supplicant( 5553): Line 31: Invalid configuration line 's'.
I/wpa_supplicant( 5553): rfkill: Cannot open RFKILL control device
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,I/qcom-bluetooth( 5590): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_4968/cgroup.procs: No such file or directory
,I/qcom-bluetooth( 5591): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/wpa_supplicant( 5553): baseband property is set to [msm]
,I/libmdmdetect( 5553): ESOC framework not supported
D/AuthorizationBluetoothService( 1719): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/wpa_supplicant( 5553):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5553): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5553): card_info[i].card_state: 0x0
E/wpa_supplicant( 5553): card_info[i].error_code: 0x0
E/wpa_supplicant( 5553): SIM/USIM not ready
E/wpa_supplicant( 5553): Error while reading SIM card status
,E/wpa_supplicant( 5553): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5553): card_info[i].card_state: 0x0
E/wpa_supplicant( 5553): card_info[i].error_code: 0x0
E/wpa_supplicant( 5553): SIM/USIM not ready
I/wpa_supplicant( 5553): eap_proxy: Card not ready
I/wpa_supplicant( 5553): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,E/WifiStateMachine(  882): setSuspendOptimizations: 2 true
E/WifiStateMachine(  882): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  882): Supplicant connection established
,E/WifiStateMachine(  882): setWifiState: enabled
,D/WifiConfigStore(  882): Loading config and enabling all networks 
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiConfigStore(  882):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  882):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  882): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-HAL(  882): Setting external_sim to 1
D/WifiStateMachine(  882): Setting OUI to DA-A1-19
I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2db689c
D/wifi    (  882): halHandle = 0x0, mVM = 0xb77fb310, mCls = 0x101672
I/WifiNative-HAL(  882): Could not start hal
,E/WifiStateMachine(  882): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/wpa_supplicant( 5553): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/wpa_supplicant( 5553): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5553): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=5598 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,E/native  (  882): do suspend true
,D/WifiP2pService(  882): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  291): Setting iface cfg
D/CommandListener(  291): Trying to bring up p2p0
,D/WifiMonitor(  882): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  882): P2pEnablingState
D/WifiP2pService(  882): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2p socket connection successful
D/WifiP2pService(  882): P2pEnabledState
D/WifiP2pService(  882): sending p2p connection changed broadcast
,D/WifiScanningService(  882): SCAN_AVAILABLE : 3
D/RttService(  882): SCAN_AVAILABLE : 3
D/WifiScanningService(  882): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  882): startHal
D/RttService(  882): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa4ad99cc
D/wifi    (  882): halHandle = 0x0, mVM = 0xb77fb310, mCls = 0x166e
I/WifiNative-HAL(  882): Could not start hal
E/WifiScanningService(  882): could not start HAL
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 26.004ms
,D/WifiNative-HAL(  882): p2pGetDeviceAddress
,D/WifiNative-HAL(  882): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,E/WifiStateMachine(  882): set country code US
D/WifiP2pService(  882): DeviceAddress: 44:80:eb:7b:5a:07
D/WifiP2pService(  882): MCC mode enabled 0
D/WifiP2pService(  882): mP2pAutoConnectSupport = 0
D/WifiP2pService(  882): sending p2p persistent groups changed broadcast
D/WifiP2pService(  882): InactiveState
E/WifiStateMachine(  882): set frequency band 2
I/wpa_supplicant( 5553): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 5553): wlan0: Failed to initiate AP scan
D/WifiP2pService(  882): InactiveState{ when=-3ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-3ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/WifiP2pService(  882): InactiveState{ when=-6ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.005ms
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
,E/WifiStateMachine(  882): setDetailed state send new extra info0x
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/SharedPreferencesImpl(  882): Couldn't create directory for SharedPreferences file shared_prefs/android_preferences.xml
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 23.012ms
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin ( 2923): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2923): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,W/ResourcesManager( 5598): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Killing 5277:com.google.android.gms:car/u0a16 (adj 15): empty #7
,I/MDMCTBK (  294): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  294): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
,I/MDMCTBK (  294): wifi_connect_to_supplicant, current pid is = 294
D/MDMCTBK (  294): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  294): wifi_close_sockets: Exit
,E/MDMCTBK (  294): Attach monitor thread
,I/MDMCTBK (  294): createWifiMonitorThread: Started the wifi monitor thread -1191694536
D/MDMCTBK (  294): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2923): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_5277/cgroup.procs: No such file or directory
,D/Checkin ( 2923): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/MDMCTBK (  294): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  294): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  482): NL - Read 56 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2db68fc
D/wifi    (  882): halHandle = 0x0, mVM = 0xb77fb310, mCls = 0x10197e
I/WifiNative-HAL(  882): Could not start hal
E/WifiStateMachine(  882): [1,454,523,334,654 ms] noteScanEnd no scan source
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@25958fb2 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  882): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  882):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  882): will read network variables netId=0
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  882): will read network variables netId=0
,I/wpa_supplicant( 5553): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  294): Event received = Trying to associate with
,D/WifiMonitor(  882): didn't find BSSID Trying to associate with SSID 'NG700'
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 5553): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiConfigStore(  882): setLastSelectedConfiguration -1
,E/wpa_supplicant( 5553): PNO: In assoc process
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TCMD    (  482): NL - Read 312 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 192 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 80 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 80 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
I/wpa_supplicant( 5553): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  294): Event received = Associated with c0:ff:d4
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
,D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0,
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 5553): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  294): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 5553): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294):  STA Connected !!
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
E/MDMCTBK (  294): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  294): get_freq !!, resp=2412
I/MDMCTBK (  294): get_freq !!, Strip data
,I/MDMCTBK (  294): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=0,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler, Wifi Band changed, call setWifiCutback.
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 0, data=0
I/MDMCTBK (  294): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  294): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1191673680
I/MDMCTBK (  294): return from set_get_from_wpa_supplicant
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  294): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  294): , reply_len: 3, ret: 0
E/MDMCTBK (  294): MdmCutbackHndler, resp=OK
E/MDMCTBK (  294): 
D/MDMCTBK (  294): wifi_set_tx_pwr: Exit
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  882): Network connection established
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
I/qcom-bluetooth( 5635): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 44:80:eb:7b:5a:05 
E/WifiStateMachine(  882): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  882): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  882): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine(  882): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  291): Setting iface cfg
,E/WifiStateMachine(  882): Start Dhcp Watchdog 1
I/qcom-bluetooth( 5637): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend false
,I/bt_hwcfg( 5502): bluetooth satus is on
D/bt_userial_mct( 5502): userial_open(port:0)
,I/bt_userial_vendor( 5502): Done intiailizing UART
,I/bt_userial_vendor( 5502): Done intiailizing UART
I/bt_userial_mct( 5502): CMD=53, EVT=53, ACL_Out=54, ACL_In=54
I/bt_vendor( 5502): Bluetooth Firmware and smd is initialized
D/bt_userial_mct( 5502): Entering userial_read_thread()
,I/bt-btu  ( 5502): btu_task received preload complete event
E/wpa_supplicant( 5553): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
E/wpa_supplicant( 5553): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,I/        ( 5502): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 5502): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5502): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5502): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5502): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5502): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5502): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5502): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5502): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5502): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5502): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5502): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5502): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5502): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5502): BTE_InitTraceLevels -- TRC_BTIF
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledStateupdate channel list
,D/WifiP2pService(  882): InactiveState{ when=-5ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@e6d50af target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-5ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@e6d50af target=com.android.internal.util.StateMachine$SmHandler }
,E/bt-btm  ( 5502): BTM_SecRegister:p_cb_info->p_le_callback == 0xa6d63d85 
,E/bt-btm  ( 5502): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa6d63d85 
,E/bt-btif ( 5502): Calling BTA_HhEnable
,E/bt-btif ( 5502): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 5502): Address is:44:80:EB:7B:5A:05
,D/BluetoothAdapterProperties( 5502): Name is: XT1072
D/BluetoothManagerService(  882): Bluetooth Adapter name changed to XT1072
,D/BluetoothManagerService(  882): Stored Bluetooth name: XT1072
,D/BluetoothAdapterProperties( 5502): Scan Mode:20
D/BluetoothAdapterProperties( 5502): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5502): Adding bonded device:7C:F9:0E:37:96:AB
,D/BluetoothAdapterProperties( 5502): Adding bonded device:E0:DB:10:14:E2:C0
,D/BluetoothAdapterProperties( 5502): Adding bonded device:58:2A:F7:ED:96:BE
,E/BluetoothRemoteDevices( 5502): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:37:96:AB, value is empty for type: 10
,E/BluetoothRemoteDevices( 5502): devicePropertyChangedCallback: bdDevice: E0:DB:10:14:E2:C0, value is empty for type: 10
,E/BluetoothRemoteDevices( 5502): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/bte_conf( 5502): Device ID record 1 : primary
D/bte_conf( 5502):   vendorId            = 000f
D/bte_conf( 5502):   vendorIdSource      = 0001
E/bt_mct  ( 5502): hci lib postload completed
D/bte_conf( 5502):   product             = 1200
D/bte_conf( 5502):   version             = 1436
D/bte_conf( 5502):   clientExecutableURL = 
D/bte_conf( 5502):   serviceDescription  = 
D/bte_conf( 5502):   documentationURL    = 
D/bte_conf( 5502): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 5502): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5502): ScanMode =  20
D/BluetoothAdapterProperties( 5502): State =  11
,D/BluetoothAdapterProperties( 5502): Setting state to 12
I/BluetoothAdapterState( 5502): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  882): Message: 60
D/BluetoothManagerService(  882): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  882): Broadcasting onBluetoothStateChange(true) to 5 receivers.
I/BluetoothAdapterState( 5502): Entering On State
D/BluetoothPanServiceJni( 5502): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothHeadset( 1527): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  882): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1503): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 5502): Scan Mode:21
D/BluetoothAdapterProperties( 5502): Discoverable Timeout:120
,D/BluetoothA2dp(  882): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1503): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  882): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  882): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  882): Message: 40
,D/BluetoothManagerService(  882): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 5502): onReceive
D/BluetoothMapService( 5502): STATE_ON
,D/BluetoothMapMasInstance( 5502): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 5502): MAS initSocket()
D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5502): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothMapMasInstance( 5502): Accepting socket connection...
,W/ContextImpl( 5547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/Telecom ( 1503): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cc848cb:true
,D/HeadsetStateMachine( 5502): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 5502): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 5502): mNumber:  mType: 128
D/HeadsetStateMachine( 5502): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 5502): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/LocalBluetoothProfileManager( 5547): Adding local A2DP profile
,D/BluetoothManagerService(  882): Message: 30
,D/LocalBluetoothProfileManager( 5547): Adding local HEADSET profile
,D/BluetoothManagerService(  882): Message: 30
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5502): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1719): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  882): Message: 30
,D/BluetoothManagerService(  882): Message: 30
,D/LocalBluetoothProfileManager( 5547): Adding local MAP profile
,D/BluetoothMap( 5547): Create BluetoothMap proxy object
,D/BluetoothManagerService(  882): Message: 30
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5502): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 5502): Accept thread started.
,I/MDMCTBK (  294): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  294): NetlinkHandler, interfaceAdded
I/MDMCTBK (  294): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
E/MDMCTBK (  294): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  294): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  294): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  294): , Wifi = 1
I/MDMCTBK (  294): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
,I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
,I/MDMCTBK (  294): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 1, data=0
I/MDMCTBK (  294): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  294): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1191673656
I/MDMCTBK (  294): return from set_get_from_wpa_supplicant
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
D/MDMCTBK (  294): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  294): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  294): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  294): , reply_len: 3, ret: 0
E/MDMCTBK (  294): MdmCutbackHndler, resp=OK
E/MDMCTBK (  294): 
D/MDMCTBK (  294): wifi_set_tx_pwr: Exit
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
D/BluetoothManagerService(  882): Message: 30
,D/LocalBluetoothProfileManager( 5547): LocalBluetoothProfileManager construction complete
,I/MDMCTBK (  294): send SAR ctrl over QMI
,D/DockEventReceiver( 5547): finishStartingService: stopping service
,D/BluetoothA2dp( 5547): Proxy object connected
,D/A2dpProfile( 5547): Bluetooth service connected
,D/BluetoothHeadset( 5547): Proxy object connected
,D/HeadsetProfile( 5547): Bluetooth service connected
,D/BluetoothInputDevice( 5547): Proxy object connected
D/HidProfile( 5547): Bluetooth service connected
,D/BluetoothPan( 5547): BluetoothPAN Proxy object connected
,D/PanProfile( 5547): Bluetooth service connected
,D/BluetoothMap( 5547): Proxy object connected
,D/MapProfile( 5547): Bluetooth service connected
D/BluetoothMap( 5547): getConnectedDevices()
,D/BluetoothPbap( 5547): Proxy object connected
D/PbapServerProfile( 5547): Bluetooth service connected
,E/DHCPCD  ( 5661): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5661): version 5.5.6 starting
,E/DHCPCD  ( 5661): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 5661): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 5661): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 5661): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5661): wlan0: discarding expired lease
I/DHCPCD  ( 5661): wlan0: broadcasting for a lease
D/DHCPCD  ( 5661): wlan0: sending DISCOVER (xid 0x36d6af24), next in 3.71 seconds
,I/DHCPCD  ( 5661): wlan0: offered 192.168.1.123 from 192.168.1.1
D/DHCPCD  ( 5661): wlan0: sending REQUEST (xid 0x36d6af24), next in 3.70 seconds
,I/DHCPCD  ( 5661): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 5661): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 5661): wlan0: adding IP address 192.168.1.123/24
D/TCMD    (  482): NL - Read 60 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 20
D/TCMD    (  482): Listening for incoming client connection request
D/DHCPCD  ( 5661): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 5661): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5661): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5661): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason BOUND
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): WifiStateMachine DHCP successful
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  882): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService(  882): Adding iface wlan0 to network 100
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  882): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  882): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  882): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  882): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  882): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  882): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  882):    accepting network in place of null
,D/ConnectivityService(  882): Setting tx/rx TCP buffers to 131072,262144,3145728,4096,221184,3145728
,D/CSLegacyTypeTracker(  882): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  882): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
,I/ModemStatsDSDetect( 1510): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1510): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1510): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524295
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 18:15:41 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454523338989], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454523338964]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Validated
D/ConnectivityService(  882): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  882): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1290): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1510): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1510): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1510): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1510): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/jxcore-log( 5451): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5451): 
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1458): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2488): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AlarmManagerService(  882): Setting time of day to sec=1454523342
,W/AlarmManagerService(  882): Unable to set rtc to 1454523342: Invalid argument
,W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,V/AlarmManager(  882): send {1383ab88, *alarm*:android.intent.action.TIME_TICK}
,D/PollingManager( 2488): now: 298700 ,futureTime: 9223372036854775807
,D/PollingManager( 2488): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1458): now: 298709 ,futureTime: 86474957
D/Central_PollingManager( 1458): Polling alarm set to expire at: 86474957 Current Time: 298709
,D/PollingManager( 2488): now: 298717 ,futureTime: 9223372036854775807
,D/PollingManager( 2488): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2488): now: 298744 ,futureTime: 9223372036854775807
,I/NetworkMonitor( 5240): type=WIFI subType= reason=null isConnected=true
,V/AlarmManager(  882): done {1383ab88, *alarm*:android.intent.action.TIME_TICK} [70ms]
,V/MusicLeanback( 5240): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/OtaApp  ( 2488): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2488): [debug] > PollingManagerService, now: 298811 ,futureTime: 11960773
D/OtaApp  ( 2488): [debug] > Polling alarm set to expire at: 11960773 Current Time: 298812
,D/MMApiProvisionService( 2488): isDeviceProvisioned: deviceId = 2072049230914535424
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5736 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=5756 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  882): Explicit concurrent mark sweep GC freed 48543(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 2.074ms total 161.994ms
,D/CCE     ( 2488): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2488): createDeviceIdOrLogin update_device
D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2488): Not proxy app, so login/provision not allowed
D/MMApiWebService( 2488): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2488): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,E/GpsLocationProvider(  882): No APN found to select.
,D/DownloadManager( 2520): [92] Starting
D/MMApiProvisionService( 2488): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2488): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2488): createDeviceIdOrLogin update_device
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2488): isDeviceProvisioned: deviceId = 2072049230914535424
,W/ActivityThread( 2520): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/ActivityThread( 4914): Failed to find provider info for com.android.contacts.metadata
,D/GpsLocationProvider(  882): NTP server returned: 1454523341440 (Wed Feb 03 19:15:41 GMT+01:00 2016) reference: 297240 certainty: 11 system time offset: -1835
,D/SyncManager(  882): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 329895, reason: UserStart
,E/LocSvc_ApiV02(  882): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,D/MMApiProvisionService( 2488): isRequestAllowed(): already have outstanding request ... ignoring request
,D/MMApiWebService( 2488): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2488): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2488): generating token using payload instead of using session token
,D/ Nonce  ( 2488):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 4689(220KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 759us total 37.979ms
,D/MMApiProvisionService( 2488): isDeviceProvisioned: deviceId = 2072049230914535424
,V/Mms     ( 5736): mnc/mcc: 
,V/Mms     ( 5736): tag: int value: recipientLimit - 20
V/Mms     ( 5736): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 5736): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 5736): tag: int value: maxSubjectLength - 80
V/Mms     ( 5736): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 5736): tag: bool value: enableGroupMms - false
V/Mms     ( 5736):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/CCE     ( 2488): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2488): createDeviceIdOrLogin update_device
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2488): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2488): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2488): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2488): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 2488): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/OtaApp  ( 2488): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2488): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2488): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2488): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2488): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2488): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2488): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/art     ( 1527): Explicit concurrent mark sweep GC freed 30005(1923KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 4.772ms total 102.871ms
,I/MMApiWSBase( 2488): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,W/ResourcesManager( 5756): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5756): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5736): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5800 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,V/JNIHelp ( 5756): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5756): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5756): Installed default security provider GmsCore_OpenSSL
,E/ConnectivityChangeReceiver( 4914): Ignoring connectivity change
,D/PhoneMonitor( 5800): Register our PhoneStateListener
,D/ConnectivityService(  882): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  882): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  882): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 4914): CM callback handler got msg 524290
,D/MobileConnectivityChangeReceiver( 5800): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5800): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 4914): Checkin interval check for package: unspecified last checkin: 1453417370553 min interval config: 0 actual interval: 1105973328
,I/CheckinService( 4914): Disabling old GoogleServicesFramework version
,I/CheckinService( 4914): Checkin interval check for package: unspecified last checkin: 1453417370553 min interval config: 0 actual interval: 1105973358
,I/CheckinService( 4914): Checking schedule, now: 1454523343962 next: 1453417400535
I/CheckinService( 4914): active receiver: enabled
,I/CheckinService( 4914): Preparing to send checkin request
,I/EventLogService( 4914): Accumulating logs since 1454522773312
,I/iu.SyncManager( 4914): SYNC; picasa accounts
,D/NetworkLogImpl( 4914): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4914): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/DriveInitializer( 4914): Awaiting to be initialized
,W/DriveInitializer( 4914): Background init thread started
,I/iu.UploadsManager( 4914): num queued entries: 0
I/iu.UploadsManager( 4914): num updated entries: 0
,I/iu.SyncManager( 4914): NEXT; no task
,E/YouTube MDX( 5756): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/jxcore-log( 5451): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5451): 
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=5847 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/art     ( 5756): Suspending all threads took: 9.181ms
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5756): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,W/ResourcesManager( 5756): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5756): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/jxcore-log( 5451): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5451): 
,I/jxcore-log( 5451): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5451): 
,I/MMApiWSBase( 2488): doRequest(): error in response: 403
,I/ Nonce  ( 2488):  Nonce Reponse 
D/        ( 2488): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"d8fd175b-2964-4d61-b543-006c75c1d678"}
D/MMApiWSBase( 2488): doRequest(): /v1/gdi/nonce.json resp length: 61
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/ Nonce  ( 2488):  Nonce Handle Reponse 
,I/MMApiWSBase( 2488): doRequest(): error in response: {"error":"INVALID_SESSION","error_text":"Please provide a valid authtoken"}
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2488): mOutstandingReq set to false
,D/MMApiWSBase( 2488): doRequest(): v1/gns/list/messages resp length: 75
,I/MMApiWebService( 2488): inspectMMApiResponse(): found an error from a web service response: ForbiddenError msg: INVALID_SESSION req: 
,I/art     (  882): Explicit concurrent mark sweep GC freed 15974(674KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.756ms total 176.737ms
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2488): inspectMMApiResponse(): received invalid session error from the server.. need to re-login
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,E/Auth.Api.Credentials( 4914): [CredentialSyncAdapter] Unknown sync event.
,I/MMApiWebService( 2488): initiateDeviceLogin(): sending login request
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/GCM     ( 1719): GCM config loaded
,I/MMApiWebService( 2488): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2488): Got request to obtain new Session .. doing so now
I/MMApiProvisionService( 2488): createDeviceIdOrLogin update_device
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2488): Not proxy app, so login/provision not allowed
D/MMApiProvisionService( 2488): Got request to obtain new Session .. doing so now
I/MMApiProvisionService( 2488): createDeviceIdOrLogin update_device
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/jxcore-log( 5451): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5451): 
D/MMApiProvisionService( 2488): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2488): set mOutstandingReq to true.
I/ Nonce  ( 2488):  Nonce getNonce 
I/ Nonce  ( 2488):  Nonce Request 
I/ Nonce  ( 2488):  Nonce execute Request 
D/MMApiProvisionService( 2488): Got request to obtain new Session .. doing so now
I/MMApiProvisionService( 2488): createDeviceIdOrLogin update_device
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2488): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2488): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/jxcore-log( 5451): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5451): 
,I/jxcore-log( 5451): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5451): 
,I/jxcore-log( 5451): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5451): 
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5756): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5756): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5756): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 5756): Found 10016
,D/MMApiWebService( 2488): generating token using payload instead of using session token
,D/MMApiProvisionService( 2488): mForceLogin set to false.
D/MMApiProvisionService( 2488): createDeviceIdOrLogin(): Got request to login .. processing now
,D/ Nonce  ( 2488):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2488): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5756): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,D/BSUtils ( 2488): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1527): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/ActivityManager(  882): Killing 5092:com.android.vending/u0a32 (adj 15): empty #7
,D/Checkin ( 2520): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/dex2oat ( 5879): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads2004333573.jar --oat-fd=38 --oat-location=/data/data/com.google.android.youtube/cache/ads2004333573.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 3676(145KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 581us total 55.525ms
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_5092/cgroup.procs: No such file or directory
,D/DownloadManager( 2520): [92] Finished with status SUCCESS
,I/art     ( 2488): Explicit concurrent mark sweep GC freed 27754(1547KB) AllocSpace objects, 3(94KB) LOS objects, 40% free, 11MB/19MB, paused 1.323ms total 133.884ms
,D/BSUtils ( 2488): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2488): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2488): doRequest() with req : MMApiWSRequest(/v1/gdi/devices.json)
,I/CheckinRequestBuilder( 4914): Checkin reason type: 12 attempt count: 1
,D/MMApiWebService( 2488): generating token using payload instead of using session token
,D/WifiService(  882): New client listening to asynchronous messages
,E/ActivityThread( 4914): Failed to find provider info for com.google.android.wearable.settings
,I/MMApiWSBase( 2488): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/devices.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5921 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5547:com.android.settings/1000 (adj 15): empty #7
,I/dex2oat ( 5879): dex2oat took 553.178ms (threads: 4)
,W/DataUsage( 2488): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.gms/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4914): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
,W/libprocessgroup(  882): failed to open /acct/uid_1000/pid_5547/cgroup.procs: No such file or directory
,W/ResourcesManager( 5921): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 3952): Explicit concurrent mark sweep GC freed 1501(53KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 1.238ms total 26.287ms
,I/MDMCTBK (  294): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  294): NetlinkHandler, interfaceAdded
I/MDMCTBK (  294): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
E/MDMCTBK (  294): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  294): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  294): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  294): , Wifi = 1
I/MDMCTBK (  294): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
,I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  294): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  294): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1191673656
I/MDMCTBK (  294): return from set_get_from_wpa_supplicant
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
D/MDMCTBK (  294): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  294): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  294): , reply_len: 3, ret: 0
E/MDMCTBK (  294): MdmCutbackHndler, resp=OK
E/MDMCTBK (  294): 
D/MDMCTBK (  294): wifi_set_tx_pwr: Exit
,I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
,W/DriveInitializer( 4914): Background init thread ended
,I/ Nonce  ( 2488):  Nonce Reponse 
D/        ( 2488): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"71527af6-43f4-4560-8375-ae9a9759f708"}
D/MMApiWSBase( 2488): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2488):  Nonce Handle Reponse 
D/MMApiProvisionService( 2488): mOutstandingReq set to false
,I/Babel_SMS( 5921): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5921): MmsConfig.loadMmsSettings
I/Babel_SMS( 5921): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5921): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5921): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5921): MmsConfig.loadFromResources
E/Babel_SMS( 5921): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5921): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     (  882): Explicit concurrent mark sweep GC freed 11959(546KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 8.979ms total 144.317ms
,W/GoogleHttpServiceClient( 1719): Timeout on service connection
W/GoogleHttpServiceClient( 1719): java.lang.Throwable
W/GoogleHttpServiceClient( 1719): 	at com.google.android.gms.http.e.a(SourceFile:97)
W/GoogleHttpServiceClient( 1719): 	at com.google.android.gms.http.g.a(SourceFile:146)
W/GoogleHttpServiceClient( 1719): 	at com.google.android.gms.http.GoogleHttpClient.a(SourceFile:757)
W/GoogleHttpServiceClient( 1719): 	at com.google.android.gms.http.GoogleHttpClient.execute(SourceFile:665)
W/GoogleHttpServiceClient( 1719): 	at com.google.android.gms.auth.j.a.a(SourceFile:77)
W/GoogleHttpServiceClient( 1719): 	at com.google.android.gms.auth.j.a.a(SourceFile:114)
W/GoogleHttpServiceClient( 1719): 	at com.google.android.gms.auth.be.account.b.e.a(SourceFile:115)
W/GoogleHttpServiceClient( 1719): 	at com.google.android.gms.auth.be.p.a(SourceFile:355)
W/GoogleHttpServiceClient( 1719): 	at com.google.android.gms.auth.be.o.a(SourceFile:260)
W/GoogleHttpServiceClient( 1719): 	at com.google.android.gms.auth.firstparty.dataservice.y.a(SourceFile:197)
W/GoogleHttpServiceClient( 1719): 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:558)
W/GoogleHttpServiceClient( 1719): 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:196)
W/GoogleHttpServiceClient( 1719): 	at com.google.android.gms.auth.o.a(SourceFile:276)
W/GoogleHttpServiceClient( 1719): 	at com.google.android.gms.auth.o.a(SourceFile:196)
W/GoogleHttpServiceClient( 1719): 	at com.google.android.b.b.onTransact(SourceFile:137)
W/GoogleHttpServiceClient( 1719): 	at android.os.Binder.execTransact(Binder.java:446)
,W/art     ( 4914): Suspending all threads took: 10.784ms
,I/GoogleURLConnFactory( 1719): Using platform SSLCertificateSocketFactory
,I/art     ( 4914): Explicit concurrent mark sweep GC freed 24946(1803KB) AllocSpace objects, 34(544KB) LOS objects, 40% free, 13MB/23MB, paused 43.349ms total 460.575ms
,W/Settings( 5921): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5921): startup - clean
,I/Babel   ( 5921): deleted: false for 0
,D/MMApiProvisionService( 2488):  pTime 1453415958710 sExp 172742 cTime 1454523346281 tTime 1453588700710
D/MMApiProvisionService( 2488): createDeviceIdOrLogin(): Got request to login .. processing now
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5978 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/DataUsage( 2488): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/BSUtils ( 2488): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1527): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/MMApiProvisionService( 2488): ProvisionWS.Response: processing response data: {"error":"ACCESS_DENIED"}
,E/MMApiProvisionService( 2488): ProvisionWS.Response: received error code: ACCESS_DENIED Extra Info: 
D/MMApiWSBase( 2488): doRequest(): /v1/gdi/devices.json resp length: 25
,W/VideoCapabilities( 5921): Unrecognized profile 2130706433 for video/avc
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311357, SEQNUM=4405, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3230, POWER_SUPPLY_CHARGE_COUNTER=-931, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/AudioCapabilities( 5921): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5921): Unsupported mime video/mpeg2
,D/HeadsetStateMachine( 5502): Disconnected process message: 10, size: 0
,I/VideoCapabilities( 5921): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5921): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5921): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5921): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5921): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5921): onServiceConnected
,W/Babel   ( 5921): Attempted to change video mute state without an active call.
,I/Babel   ( 5921): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 5598:com.motorola.context/u0a8 (adj 15): empty #7
,I/DeviceSettingsProvider( 1458):  Number of rows updated 1
,D/MMApiProvisionService( 2488): MMApiProvisionService.handleResponse (update_device) : true (None)
E/MMApiProvisionService( 2488): handleResponse(): got ACCESS_DENIED, nothing can be done with it, so we're bailing...
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2488): notifyProvisioningDone(): Sending Device Provision response intent
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 3419(136KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 741us total 30.604ms
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_5598/cgroup.procs: No such file or directory
,D/CCE     ( 2488): NOT Backing up config to settings provider
D/CCE     ( 2488): NOT Backing up config to settings provider
D/CCE     ( 2488): NOT Backing up config to settings provider
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5978): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager(  882): Killing 5240:com.google.android.music:main/u0a80 (adj 15): empty #7
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5978): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
D/BSUtils ( 2488): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5978): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 5978): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5978):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5978):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5978): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/BSUtils ( 2488): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2488): doRequest() with req : MMApiWSRequest(/v1/gdi/devices.json)
,D/MMApiWebService( 2488): generating token using payload instead of using session token
,I/MMApiWSBase( 2488): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/devices.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_5240/cgroup.procs: No such file or directory
,W/GAv4    ( 5978): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/InstanceID/Rpc( 4914): Found 10016
,W/GAv4    ( 5978): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5978): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/PeopleSync( 4914): onPerformSync() [5005f081]
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6020 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/PhenotypeConfigurator( 1719): Server returned 404
,W/DataUsage( 2488): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  882): Start proc com.google.android.calendar for service com.google.android.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService: pid=6026 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ChimeraCfgMgr( 4914): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4914): Module APK com.google.android.play.games already loaded
,W/ResourcesManager( 6020): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6020): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MultiDex( 6020): VM with version 2.1.0 has multidex support
I/MultiDex( 6020): install
I/MultiDex( 6020): VM has multidex support, MultiDex support library is disabled.
,I/GamesSyncServiceMain( 4914): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 4914): Failed to execute periodic sync, missing client context - aborting
,V/JNIHelp ( 6020): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/SQLiteLog( 6026): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,W/ActivityThread( 6020): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6020): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bdeaa33: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6020): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6020): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6020): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  882): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6074 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6074): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/NativeLibraryUtils( 6020): Install completed successfully. count=14 extracted=0
,W/AbstractGoogleClient( 6026): Application name is not set. Call Builder#setApplicationName.
,I/CalendarProvider2( 6074): Created com.android.providers.calendar.CalendarAlarmManager@2100ea60(com.android.providers.calendar.CalendarProvider2@3b0d3b19)
,I/AnalyticsLogBase( 6026): PlayLogger.onLoggerConnected
,I/AnalyticsLogBase( 6026): PlayLogger.onLoggerConnected
,I/WebViewFactory( 5978): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/MMApiProvisionService( 2488): ProvisionWS.Response: processing response data: {"sessionToken":"0-ba6a76f127dbf93e6b77e7cd7044f4e1436765851","error":"OK","sessionExpiration":"172742","deviceId":"2072049230914535424"}
D/MMApiProvisionService( 2488): ProvisionWS.Response: Completed parsing response.. no settings sent by server
D/MMApiWSBase( 2488): doRequest(): /v1/gdi/devices.json resp length: 137
,I/art     (  882): Explicit concurrent mark sweep GC freed 22116(948KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.731ms total 122.588ms
,I/LibraryLoader( 5978): Time to load native libraries: 6 ms (timestamps 3899-3905)
I/LibraryLoader( 5978): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5978): Binding Chromium to main looper Looper (main, tid 1) {37268623}
,I/LibraryLoader( 5978): Expected native library version number "",actual native library version number ""
I/chromium( 5978): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/BrowserStartupController( 5978): Initializing chromium process, singleProcess=true
W/art     ( 5978): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5978): ApplicationContext is null in ApplicationStatus
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,W/chromium( 5978): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f49000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f49000
,E/libEGL  ( 5978): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5978): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb5524960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb8d762d0, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8d78518, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8e96798, idLength=0xb133a730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=4233419162
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8d69818
D/DrmWidevineDash(  296): message_length=1591, signature=0xb8d69e58, signature_length=2972952340
,I/Adreno-EGL( 5978): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5978): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5978): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5978): Local Branch: 
I/Adreno-EGL( 5978): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5978): Local Patches: NONE
I/Adreno-EGL( 5978): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/DeviceSettingsProvider( 1458):  Number of rows updated 1
,D/MMApiProvisionService( 2488): MMApiProvisionService.handleResponse (update_device) : true (None)
,I/GoogleURLConnFactory( 6020): Using platform SSLCertificateSocketFactory
,I/PeopleSync( 4914): Setting subscription: result=true [5005f081]
I/PeopleSync( 4914): Starting sync, feed=null [5005f081]
,W/BaseAppContext( 4914): Using Auth Proxy for data requests.
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,W/BaseAppContext( 4914): Using Auth Proxy for data requests.
,I/DeviceSettingsProvider( 1458):  Number of rows updated 1
,E/MMApiProvisionService( 2488): Caught IOException:/pds/public/svcs/activation_date: open failed: EACCES (Permission denied)
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,W/BaseAppContext( 4914): Using Auth Proxy for data requests.
W/FileUtils( 2488): Failed to chmod(/pds/public/svcs/activation_date): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
D/MMApiProvisionService( 2488): handleResponse(): Session Expiration alarm set to expire at: Fri Feb 05 19:14:50 GMT+01:00 2016
I/MMApiProvisionService( 2488):  value of type 2072049230914535424 0-ba6a76f127dbf93e6b77e7cd7044f4e1436765851 172742
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2488):  get value of the device MOTO
I/MMApiProvisionService( 2488):  came in moto 
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2488): setMMApiCredInfoToMainApp: storing credential info
I/MMApiProvisionService( 2488): setMMApiCredInfoToMainApp: deviceId = 2072049230914535424
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,W/AudioManagerAndroid( 5978): Requires BLUETOOTH permission
,I/PeopleSync( 4914): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/DeviceSettingsProvider( 1458):  Number of rows updated 1
,I/NSApplication( 5978): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6124 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/DataUsage( 2488): invalid counter update blocked: 'err' by 0
,I/DeviceSettingsProvider( 1458):  Number of rows updated 1
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  882): Killing 5736:com.android.mms/u0a23 (adj 15): empty #7
,I/DeviceSettingsProvider( 1458):  Number of rows updated 1
,E/PhoneInterfaceManager( 1527): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_5736/cgroup.procs: No such file or directory
,I/CalendarProvider2( 6074): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6074): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6147 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 5800:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 297us total 20.724ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.206ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 19.946ms
,I/DeviceSettingsProvider( 1458):  Number of rows updated 1
,I/dex2oat ( 6153): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/the.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/opt/the.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/DeviceSettingsProvider( 1458):  Number of rows updated 1
,I/dex2oat ( 6153): dex2oat took 59.544ms (threads: 4)
,I/DeviceSettingsProvider( 1458):  Number of rows updated 1
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_5800/cgroup.procs: No such file or directory
,I/DeviceSettingsProvider( 1458):  Number of rows updated 1
,W/ResourcesManager( 6147): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/DeviceSettingsProvider( 1458):  Number of rows updated 1
,D/BSUtils ( 2488): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/MMApiProvisionService( 2488):  response.hasSettings() false
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 2488): handleResponse(): no settings sent by the server:
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/MMApiWebService( 2488): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
D/MMApiWebService( 2488): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,D/MMApiWebService( 2488): MMApiWebService told us to retry waiting request since device is successfully provisioned: 1
,D/MMApiWebService( 2488): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/MMApiWSBase( 2488): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/GoogleURLConnFactory( 6020): Using platform SSLCertificateSocketFactory
D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f49000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f49000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb133a960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb8d91ad0, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8d61370, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8e96798, idLength=0xb5424730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=2163874692
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8d79178
D/DrmWidevineDash(  296): message_length=1591, signature=0xb8d797b8, signature_length=3041019668
,I/dex2oat ( 6184): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6190 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  882): Killing 5921:com.google.android.talk/u0a70 (adj 15): empty #7
,I/dex2oat ( 6184): dex2oat took 275.656ms (threads: 4)
,I/ContactLocale( 6190): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 5847:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/Adreno-EGL( 6020): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6020): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6020): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6020): Local Branch: 
I/Adreno-EGL( 6020): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6020): Local Patches: NONE
I/Adreno-EGL( 6020): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6020): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6020): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6020): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6020): Local Branch: 
I/Adreno-EGL( 6020): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6020): Local Patches: NONE
I/Adreno-EGL( 6020): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_5921/cgroup.procs: No such file or directory
W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_5847/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2488): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 2488): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/Adreno-EGL( 6020): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6020): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6020): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6020): Local Branch: 
I/Adreno-EGL( 6020): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6020): Local Patches: NONE
I/Adreno-EGL( 6020): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/SQLiteLog( 2488): (284) automatic index on registration(APP_ID)
D/WaitableIntentService( 2488): ServiceHandler.handleMessage: mWaitCount=1
I/PushService( 2488): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=6216 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/art     ( 3952): Explicit concurrent mark sweep GC freed 2815(109KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 2.611ms total 67.859ms
,I/Adreno-EGL( 6020): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6020): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6020): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6020): Local Branch: 
I/Adreno-EGL( 6020): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6020): Local Patches: NONE
I/Adreno-EGL( 6020): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ResourcesManager( 6216): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/Adreno-EGL( 6020): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6020): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6020): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6020): Local Branch: 
I/Adreno-EGL( 6020): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6020): Local Patches: NONE
I/Adreno-EGL( 6020): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  882): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6243 uid=10096 gids={50096, 9997} abi=armeabi-v7a
,I/dex2oat ( 6242): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads2004333573.jar --oat-fd=94 --oat-location=/data/data/com.google.android.gms/cache/ads2004333573.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  882): Killing 5978:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/dex2oat ( 6242): dex2oat took 73.805ms (threads: 4)
,D/MMApiWSBase( 2488): doRequest(): v1/gns/list/messages resp length: 1363
,D/CCE     ( 2488): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 2488): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,D/Checkin ( 2488): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 2488): handleGetNotificationsResponse(): got 0; more=false
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_5978/cgroup.procs: No such file or directory
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
I/System.out( 6243): TimeService: Loaded Library 
D/TimeService( 6243): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454523351169
D/        ( 6243): TimeServiceNative: User Time to be set is 1454523351169
D/QC-time-services( 6243): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6243): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6243): Lib:time_genoff_operation: pargs->ts_val = 1454523351169
D/QC-time-services( 6243): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  319): Daemon: Connection accepted:time_genoff
D/QC-time-services(  319): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454523351169
D/QC-time-services(  319): Daemon:genoff_opr: Base = 2, val = 1454523351169, operation = 0
D/QC-time-services(  319): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/3/116 18:14:11
D/QC-time-services(  319): Daemon:Value read from RTC seconds = 1454523251000
D/QC-time-services(  319): Daemon:new time 1454523351169 
D/QC-time-services(  319): Daemon: delta 100169 genoff 100169 
D/QC-time-services(  319): Daemon:genoff_persistent_update: Writing genoff = 100169 to memory
D/QC-time-services(  319): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  319): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  319): Updating the TOD offset
D/QC-time-services(  319): Daemon:genoff_persistent_update: Writing genoff = 100169 to memory
D/QC-time-services(  319): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  319): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  319): Daemon:Update to modem bit set
D/QC-time-services(  319): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  319): Daemon: Base = 2, Value being sent to MODEM = 18446743757744851785
E/QC-time-services( 6243): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/ActivityManager(  882): Killing 5756:com.google.android.youtube/u0a101 (adj 15): empty #7
E/QC-time-services(  319): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  319): Daemon: Time-services: Waiting to acceptconnection
D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,I/CalendarSyncAdapter( 6026): Found no pending settings
D/QSEECOMAPI: (  296): Loaded image: APP id = 3
D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f49000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f49000
D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb5524960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb8d637f0, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8d61370, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8e967d8, idLength=0xbe80d2b0
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=453031749
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8d79178
D/DrmWidevineDash(  296): message_length=1626, signature=0xb8d797d8, signature_length=3196113556
,W/libprocessgroup(  882): failed to open /acct/uid_10101/pid_5756/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 6124:com.android.chrome/u0a52 (adj 15): empty #7
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_6124/cgroup.procs: No such file or directory
,W/DataUsage( 2488): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2488): publish the event [tag = MOT_CCE event name = LOG]
,I/CheckinService( 4914): Checkin interval check for package: unspecified last checkin: 1453417370553 min interval config: 0 actual interval: 1105981163
,I/CheckinRequestBuilder( 4914): Classify the device as Phone.
,I/art     (  882): Explicit concurrent mark sweep GC freed 19189(885KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.840ms total 137.721ms
,I/CheckinTask( 4914): Sending checkin request (11063 bytes)
,I/ActivityManager(  882): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=6291 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6310 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinResponseProcessor( 4914): From server: 21 gservices updates and 5 deletes
,W/ContextImpl( 6026): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 6026): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 4914): Google Analytics 8.4.89 is starting up.
,W/ResourcesManager( 6310): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6310): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GAv4    ( 6291): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6291):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6291):   adb logcat -s GAv4
,V/JNIHelp ( 6310): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/GAv4    ( 6291): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 4914): Explicit concurrent mark sweep GC freed 35542(2MB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 14MB/24MB, paused 4.988ms total 141.198ms
,W/System  ( 6310): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6310): Installed default security provider GmsCore_OpenSSL
,W/SQLiteConnectionPool( 4914): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/GAv4    ( 6291): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6291): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.

```
