#### Test 55613145ac448d4_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
D/AndroidRuntime( 5540): 
D/AndroidRuntime( 5540): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5540): CheckJNI is OFF
D/AndroidRuntime( 5540): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5559 uid=10441 gids={50441, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5540): Shutting down VM
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5559): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5559): Time to load native libraries: 2 ms (timestamps 7407-7409)
,I/LibraryLoader( 5559): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5559): Binding Chromium to main looper Looper (main, tid 1) {1ed166fd}
,I/LibraryLoader( 5559): Expected native library version number "",actual native library version number ""
,I/chromium( 5559): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5559): Initializing chromium process, singleProcess=true
,W/art     ( 5559): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5559): ApplicationContext is null in ApplicationStatus
,W/chromium( 5559): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5559): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5559): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5559): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5559): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5559): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5559): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5559): Local Branch: 
I/Adreno-EGL( 5559): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5559): Local Patches: NONE
I/Adreno-EGL( 5559): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9911fb2:true
,D/BluetoothAdapter( 5559): 245647678: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  881): Activity pause timeout for ActivityRecord{149d116f u0 com.test.thalitest/.MainActivity t3}
W/art     ( 5559): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5559): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5559): CordovaWebView is running on device made by: motorola
W/art     ( 5559): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5559): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5559): Render dirty regions requested: true
D/Atlas   ( 5559): Validating map...
W/chromium( 5559): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 5559): Initialized EGL, version 1.4
D/OpenGLRenderer( 5559): Enabling debug mode 0
I/Keyboard.Facilitator( 1409): onFinishInput()
I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,965
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +891ms (total +966ms)
W/IInputConnectionWrapper( 5559): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 5559): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5559): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 5559): Cannot call determinedVisibility() - never saw a connection for the pid: 5559
D/JsMessageQueue( 5559): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5559): JniHelper::setJavaVM(0xb8993310), pthread_self() = -1194177896
,D/JX-Cordova( 5559): jxcore cordova android initializing
,W/jxcore-log( 5559): Initializing JXcore engine
W/jxcore-log( 5559): JXcore engine is ready
,W/jxcore-log( 5559): Starting JXcore engine
,W/.test.thalitest( 5559): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10441 path="socket:[7310]" dev="sockfs" ino=7310 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5559): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10441 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5559): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10441 path="socket:[9488]" dev="sockfs" ino=9488 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5559): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10441 path="socket:[25603]" dev="sockfs" ino=25603 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5559): Platform android
W/jxcore-log( 5559): 
W/jxcore-log( 5559): Process ARCH arm
W/jxcore-log( 5559): 
,I/jxcore-log( 5559): JXcore Cordova bridge is ready!
I/jxcore-log( 5559): 
,W/jxcore-log( 5559): JXcore engine is started
I/Choreographer( 5559): Skipped 169 frames!  The application may be doing too much work on its main thread.
I/chromium( 5559): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5559): Toggling radios to true
I/jxcore-log( 5559): 
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  881): enable():  mBluetooth =null mBinding = false
,W/Settings( 1464): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  881): Message: 1
D/BluetoothManagerService(  881): MESSAGE_ENABLE: mBluetooth = null
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiService(  881): New client listening to asynchronous messages
D/WifiService(  881): setWifiEnabled: true pid=5559, uid=10441
,E/WifiService(  881): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine(  881): setting operational mode to 1
,I/jxcore-log( 5559): Radios toggled
I/jxcore-log( 5559): 
I/jxcore-log( 5559): My device name is: motorola-XT1072
I/jxcore-log( 5559): 
,I/ActivityManager(  881): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5611 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
W/Settings( 1464): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1464): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1464): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/ResourcesManager( 5611): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 5611): Adding HeadsetService
D/AdapterServiceConfig( 5611): Adding A2dpService
D/AdapterServiceConfig( 5611): Adding HidService
D/AdapterServiceConfig( 5611): Adding HealthService
D/AdapterServiceConfig( 5611): Adding PanService
D/AdapterServiceConfig( 5611): Adding GattService
D/AdapterServiceConfig( 5611): Adding BluetoothMapService
,D/BluetoothManagerService(  881): Message: 20
,D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20e4c8c8:true
,D/BluetoothAdapterState( 5611): make
,I/bluedroid( 5611): init
I/BluetoothAdapterState( 5611): Entering OffState
,I/bte_conf( 5611): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5611): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 5611): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5611): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 5611): get_profile_interface socket
I/bluedroid( 5611): get_profile_interface map_client
,I/GKI_LINUX( 5611): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothManagerService(  881): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  881): Message: 40
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothAdapterProperties( 5611): Address is:44:80:EB:7B:5A:05
I/bluedroid( 5611): config_hci_snoop_log
D/BluetoothAdapterProperties( 5611): Name is: XT1072
D/BluetoothManagerService(  881): Bluetooth Adapter name changed to XT1072
D/BluetoothManagerService(  881): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  881): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothManagerService(  881): Stored Bluetooth name: XT1072
,D/BluetoothAdapterState( 5611): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 5611): Setting state to 11
,I/BluetoothAdapterState( 5611): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  881): Message: 60
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  881): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 5611): make
,I/BluetoothBondStateMachine( 5611): StableState(): Entering Off State
,D/Tethering(  881): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  0
,D/Tethering(  881):  1
D/Tethering(  881):  5
,D/Tethering(  881):  7
,I/ActivityManager(  881): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5652 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TCMD    (  482): NL - Read 1008 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/Tethering(  881): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering(  881): InitialState.processMessage what=4
,D/Tethering(  881): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  0
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
D/Tethering(  881): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  482): NL - Read 1008 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/QsoftapCmd(  303): Got softap fwreload command we are passing on
,D/SoftapController(  303): Softap fwReload - Ok
,D/BluetoothHeadset(  881): Proxy object connected
,D/HeadsetService( 5611): Received start request. Starting profile...
D/BluetoothHeadset( 1501): Proxy object connected
I/BluetoothHeadsetServiceJni( 5611): classInitNative: succeeds
D/BluetoothHeadset( 1537): Proxy object connected
,D/HeadsetStateMachine( 5611): make
,I/BluetoothAdapterState( 5611): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/CommandListener(  303): Setting iface cfg
D/CommandListener(  303): Trying to bring down wlan0
,D/CommandListener(  303): Clearing all IP addresses on wlan0
,D/BluetoothHeadset( 1501): Proxy object connected
,D/HeadsetStateMachine( 5611): max_hf_connections = 1
I/bluedroid( 5611): get_profile_interface handsfree
,D/HeadsetStateMachine( 5611): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 5611): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ed166fd
,D/Checkin ( 3106): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/BluetoothA2dp(  881): Proxy object connected
,D/A2dpService( 5611): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 5611): classInitNative: succeeds
I/bluedroid( 5611): get_profile_interface avrcp
,D/Checkin ( 3106): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,W/ResourcesManager( 5652): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,E/RemoteController( 5611): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 5611): classInitNative: succeeds
D/A2dpStateMachine( 5611): make
,I/bluedroid( 5611): get_profile_interface a2dp
I/GKI_LINUX( 5611): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 5611): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ed166fd
I/BluetoothHidServiceJni( 5611): classInitNative: succeeds
,D/A2dpStateMachine( 5611): Enter Disconnected: -2
,D/HidService( 5611): Received start request. Starting profile...
I/bluedroid( 5611): get_profile_interface hidhost
D/BluetoothAdapterService( 5611): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ed166fd
I/BluetoothHealthServiceJni( 5611): classInitNative: succeeds
,D/HealthService( 5611): Received start request. Starting profile...
,I/bluedroid( 5611): get_profile_interface health
D/BluetoothAdapterService( 5611): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ed166fd
,I/BluetoothPanServiceJni( 5611): classInitNative(L105): succeeds
,D/PanService( 5611): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5611): initializeNative(L110): pan
I/bluedroid( 5611): get_profile_interface pan
,D/BluetoothAdapterService( 5611): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ed166fd
,I/BtGatt.JNI( 5611): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 5611): handleDebugAction() action=null
,D/BtGatt.GattService( 5611): Received start request. Starting profile...
D/BtGatt.GattService( 5611): start()
I/bluedroid( 5611): get_profile_interface gatt
,D/BluetoothAdapterService( 5611): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ed166fd
D/BtGatt.AdvertiseManager( 5611): advertise manager created
,D/BluetoothAdapterService( 5611): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ed166fd
,D/BluetoothMapService( 5611): Received start request. Starting profile...
D/BluetoothMapService( 5611): start()
,D/BluetoothMapEmailSettingsLoader( 5611): Found 0 applications
D/BluetoothMapEmailAppObserver( 5611): createReceiver()
,D/BluetoothMapEmailAppObserver( 5611): initObservers()
D/BluetoothMapEmailAppObserver( 5611): getEnabledAccountItems()
,D/BluetoothAdapterService( 5611): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ed166fd
,D/HeadsetStateMachine( 5611): Proxy object connected
D/HeadsetStateMachine( 5611): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 5611): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5611): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 5611): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5611): enable
,I/GKI_LINUX( 5611): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 5611): init
,I/bt-btu  ( 5611): btu_task pending for preload complete event
,I/bt_vendor( 5611): bt-vendor : init
D/bt_userial_mct( 5611): userial_init
,I/bt_hwcfg( 5611): Starting hciattach daemon
I/bt_hwcfg( 5611): try to set false
,I/bt_hwcfg( 5611): Starting hciattach daemon
I/bt_hwcfg( 5611): try to set true
,I/wpa_supplicant( 5674): Successfully initialized wpa_supplicant
I/wpa_supplicant( 5674): Long line in configuration file truncated
I/wpa_supplicant( 5674): rfkill: Cannot open RFKILL control device
D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,I/qcom-bluetooth( 5687): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
E/WifiStateMachine(  881): setWifiState: enabling
E/WifiStateMachine(  881): Supplicant start successful
,D/WifiMonitor(  881): startMonitoring(wlan0) with mConnected = false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
I/ActivityManager(  881): Killing 5380:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/libmdmdetect( 5674): ESOC framework not supported
E/Diag_Lib( 5674):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 5674): baseband property is set to [msm]
I/libmdmdetect( 5674): ESOC framework not supported
,E/wpa_supplicant( 5674):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5674): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5674): card_info[i].card_state: 0x0
,E/wpa_supplicant( 5674): card_info[i].error_code: 0x0
E/wpa_supplicant( 5674): SIM/USIM not ready
E/wpa_supplicant( 5674): Error while reading SIM card status
,E/wpa_supplicant( 5674): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5674): card_info[i].card_state: 0x0
E/wpa_supplicant( 5674): card_info[i].error_code: 0x0
E/wpa_supplicant( 5674): SIM/USIM not ready
I/wpa_supplicant( 5674): eap_proxy: Card not ready
I/qcom-bluetooth( 5694): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 5695): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 5697): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5698): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 5699): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,W/libprocessgroup(  881): failed to open /acct/uid_10057/pid_5380/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 1714): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/wpa_supplicant( 5674): Line 31: unknown global field '.'.
E/wpa_supplicant( 5674): Line 31: Invalid configuration line '.'.
I/wpa_supplicant( 5674): rfkill: Cannot open RFKILL control device
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,E/wpa_supplicant( 5674): baseband property is set to [msm]
I/libmdmdetect( 5674): ESOC framework not supported
,E/wpa_supplicant( 5674):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5674): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5674): card_info[i].card_state: 0x0
E/wpa_supplicant( 5674): card_info[i].error_code: 0x0
,E/wpa_supplicant( 5674): SIM/USIM not ready
E/wpa_supplicant( 5674): Error while reading SIM card status
E/wpa_supplicant( 5674): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5674): card_info[i].card_state: 0x0
E/wpa_supplicant( 5674): card_info[i].error_code: 0x0
E/wpa_supplicant( 5674): SIM/USIM not ready
I/wpa_supplicant( 5674): eap_proxy: Card not ready
I/wpa_supplicant( 5674): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,E/WifiStateMachine(  881): setSuspendOptimizations: 2 true
,E/WifiStateMachine(  881): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  881): Supplicant connection established
E/WifiStateMachine(  881): setWifiState: enabled
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/WifiConfigStore(  881): Loading config and enabling all networks 
,E/WifiConfigStore(  881):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  881):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  881): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  881): Setting external_sim to 1
,D/WifiStateMachine(  881): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  881): startHal
,E/wifi    (  881): getStaticLongField sWifiHalHandle 0xa2cbf89c
D/wifi    (  881): halHandle = 0x0, mVM = 0xb8993310, mCls = 0x100c1e
I/WifiNative-HAL(  881): Could not start hal
E/WifiStateMachine(  881): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 5674): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/wpa_supplicant( 5674): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5674): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=5705 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,E/native  (  881): do suspend true
,D/WifiP2pService(  881): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  303): Setting iface cfg
,D/CommandListener(  303): Trying to bring up p2p0
D/WifiScanningService(  881): SCAN_AVAILABLE : 3
D/WifiMonitor(  881): startMonitoring(p2p0) with mConnected = true
D/RttService(  881): SCAN_AVAILABLE : 3
D/WifiP2pService(  881): P2pEnablingState
D/WifiP2pService(  881): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2p socket connection successful
D/WifiP2pService(  881): P2pEnabledState
,D/WifiScanningService(  881): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  881): startHal
E/wifi    (  881): getStaticLongField sWifiHalHandle 0xa19f69cc
D/wifi    (  881): halHandle = 0x0, mVM = 0xb8993310, mCls = 0x100c12
D/WifiP2pService(  881): sending p2p connection changed broadcast
I/WifiNative-HAL(  881): Could not start hal
E/WifiScanningService(  881): could not start HAL
D/RttService(  881): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-HAL(  881): p2pGetDeviceAddress
,D/WifiNative-HAL(  881): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,D/WifiP2pService(  881): DeviceAddress: 44:80:eb:7b:5a:07
,D/WifiP2pService(  881): MCC mode enabled 0
,D/WifiP2pService(  881): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  881): sending p2p persistent groups changed broadcast
,E/WifiStateMachine(  881): set country code US
D/WifiP2pService(  881): InactiveState
,E/WifiStateMachine(  881): set frequency band 2
,D/WifiP2pService(  881): InactiveState{ when=-2ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5674): wlan0: Reject scan trigger since one is already pending,
W/wpa_supplicant( 5674): wlan0: Failed to initiate AP scan
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/WifiP2pService(  881): InactiveState{ when=-4ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-4ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,I/MDMCTBK (  306): NetlinkHandler, wifiStateChanged 1
,I/MDMCTBK (  306): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): wifi_connect_to_supplicant, current pid is = 306
D/MDMCTBK (  306): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  306): wifi_close_sockets: Exit
,E/MDMCTBK (  306): Attach monitor thread
,I/MDMCTBK (  306): createWifiMonitorThread: Started the wifi monitor thread -1207423248
D/MDMCTBK (  306): wifi_wait_on_socket: Enter monitor thread
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin ( 3106): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 3106): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info0x
,E/SharedPreferencesImpl(  881): Couldn't create directory for SharedPreferences file shared_prefs/android_preferences.xml
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 5705): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Killing 5276:android.process.acore/u0a7 (adj 15): empty #7
,D/Checkin ( 3106): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_5276/cgroup.procs: No such file or directory
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/Checkin ( 3106): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  482): NL - Read 56 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/MDMCTBK (  306): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  306): Event received = WPS-AP-AVAILABLE 
,I/WifiNative-HAL(  881): startHal
E/wifi    (  881): getStaticLongField sWifiHalHandle 0xa2cbf8fc
D/wifi    (  881): halHandle = 0x0, mVM = 0xb8993310, mCls = 0x1786
I/WifiNative-HAL(  881): Could not start hal
E/WifiStateMachine(  881): [1,452,596,569,968 ms] noteScanEnd no scan source
,E/WifiStateMachine(  881): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@4ca8961 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  881): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  881):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  881): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  881): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,I/qcom-bluetooth( 5739): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 44:80:eb:7b:5a:05 
E/WifiConfigStore(  881): will read network variables netId=0
,E/WifiStateMachine(  881): CMD_AUTO_CONNECT did save config ->  nid=0
,I/qcom-bluetooth( 5740): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
E/WifiConfigStore(  881): will read network variables netId=0
,I/wpa_supplicant( 5674): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  306): Event received = Trying to associate with
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
E/wpa_supplicant( 5674): DSDS: eapol_sm_notify_config config->sim_num = 1
D/WifiMonitor(  881): didn't find BSSID Trying to associate with SSID 'NG700'
E/WifiConfigStore(  881): setLastSelectedConfiguration -1
,E/wpa_supplicant( 5674): PNO: In assoc process
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/bt_hwcfg( 5611): bluetooth satus is on
,D/bt_userial_mct( 5611): userial_open(port:0)
,I/bt_userial_vendor( 5611): Done intiailizing UART
,I/bt_userial_vendor( 5611): Done intiailizing UART
I/bt_userial_mct( 5611): CMD=53, EVT=53, ACL_Out=54, ACL_In=54
I/bt_vendor( 5611): Bluetooth Firmware and smd is initialized
D/bt_userial_mct( 5611): Entering userial_read_thread()
,I/bt-btu  ( 5611): btu_task received preload complete event
I/        ( 5611): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 5611): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5611): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5611): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5611): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5611): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5611): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5611): BTE_InitTraceLevels -- TRC_BTM
,I/        ( 5611): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5611): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5611): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5611): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5611): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5611): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5611): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 5611): BTM_SecRegister:p_cb_info->p_le_callback == 0xa6d79d85 
E/bt-btm  ( 5611): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa6d79d85 
,E/bt-btif ( 5611): Calling BTA_HhEnable
,E/bt-btif ( 5611): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 5611): Address is:44:80:EB:7B:5A:05
,D/BluetoothManagerService(  881): Bluetooth Adapter name changed to XT1072
D/BluetoothManagerService(  881): Stored Bluetooth name: XT1072
D/BluetoothAdapterProperties( 5611): Name is: XT1072
,D/BluetoothAdapterProperties( 5611): Scan Mode:20
D/BluetoothAdapterProperties( 5611): Discoverable Timeout:120
D/BluetoothAdapterProperties( 5611): Adding bonded device:7C:F9:0E:37:96:AB
D/BluetoothAdapterProperties( 5611): Adding bonded device:E0:DB:10:14:E2:C0
D/BluetoothAdapterProperties( 5611): Adding bonded device:58:2A:F7:ED:96:BE
,E/BluetoothRemoteDevices( 5611): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:37:96:AB, value is empty for type: 10
,E/BluetoothRemoteDevices( 5611): devicePropertyChangedCallback: bdDevice: E0:DB:10:14:E2:C0, value is empty for type: 10
,E/BluetoothRemoteDevices( 5611): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,E/bt_mct  ( 5611): hci lib postload completed
,D/bte_conf( 5611): Device ID record 1 : primary
D/bte_conf( 5611):   vendorId            = 000f
D/bte_conf( 5611):   vendorIdSource      = 0001
D/bte_conf( 5611):   product             = 1200
D/bte_conf( 5611):   version             = 1436
D/bte_conf( 5611):   clientExecutableURL = 
D/bte_conf( 5611):   serviceDescription  = 
D/bte_conf( 5611):   documentationURL    = 
D/bte_conf( 5611): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 5611): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5611): ScanMode =  20
D/BluetoothAdapterProperties( 5611): State =  11
D/BluetoothAdapterProperties( 5611): Setting state to 12
I/BluetoothAdapterState( 5611): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  881): Message: 60
D/BluetoothPanServiceJni( 5611): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  881): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset(  881): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 5611): Entering On State
D/BluetoothHeadset( 1501): onBluetoothStateChange: up=true
,D/BluetoothAdapterProperties( 5611): Scan Mode:21
,D/BluetoothAdapterProperties( 5611): Discoverable Timeout:120
D/BluetoothHeadset( 1537): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1501): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  881): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  881): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  881): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 5611): onReceive
D/BluetoothMapService( 5611): STATE_ON
D/BluetoothManagerService(  881): Message: 40
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapMasInstance( 5611): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 5611): MAS initSocket()
,W/ContextImpl( 5652): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5611): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 5611): Accepting socket connection...
,I/Telecom ( 1501): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/HeadsetStateMachine( 5611): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 5611): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 5611): mNumber:  mType: 128
D/HeadsetStateMachine( 5611): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 5611): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2184ce58:true
,D/LocalBluetoothProfileManager( 5652): Adding local A2DP profile
,D/BluetoothManagerService(  881): Message: 30
,D/LocalBluetoothProfileManager( 5652): Adding local HEADSET profile
,D/AuthorizationBluetoothService( 1714): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledStateupdate channel list
,I/MDMCTBK (  306): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  306): NetlinkHandler, interfaceAdded
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
E/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  306): , Wifi = 0
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  306): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
,D/TCMD    (  482): NL - Read 312 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 192 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
I/MDMCTBK (  306): send SAR ctrl over QMI
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/TCMD    (  482): NL - Read 80 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 80 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
I/wpa_supplicant( 5674): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  306): Event received = Associated with c0:ff:d4
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info"NG700"
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 5674): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5674): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  306): Event received = WPA: Key negotiation com
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  306): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  306):  STA Connected !!
D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/Tethering(  881): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  0
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
E/MDMCTBK (  306): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  306): get_freq !!, resp=2412
I/MDMCTBK (  306): get_freq !!, Strip data
I/MDMCTBK (  306): get_freq !!, band = 2, freq = 2412
,I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=0,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  306): get_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler, Wifi Band changed, call setWifiCutback.
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
,I/MDMCTBK (  306): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 1, data=0
I/MDMCTBK (  306): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  306): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  306): get_property_value, Exit
I/MDMCTBK (  306): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1207407336
I/MDMCTBK (  306): return from set_get_from_wpa_supplicant
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  306): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  306): , reply_len: 3, ret: 0
E/MDMCTBK (  306): MdmCutbackHndler, resp=OK
E/MDMCTBK (  306): 
D/MDMCTBK (  306): wifi_set_tx_pwr: Exit
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/Tethering(  881): sendTetherStateChangedBroadcast 1, 0, 0
D/BluetoothManagerService(  881): Message: 30
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
W/BluetoothAdapter( 5611): getBluetoothService() called with no BluetoothManagerCallback
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): Network connection established
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
W/BluetoothAdapter( 5611): getBluetoothService() called with no BluetoothManagerCallback
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/BtOppRfcommListener( 5611): Accept thread started.
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/BluetoothManagerService(  881): Message: 30
D/ConnectivityService(  881): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  881): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  881): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  881): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine(  881): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BluetoothManagerService(  881): Message: 30
D/CommandListener(  303): Setting iface cfg
E/WifiStateMachine(  881): Start Dhcp Watchdog 1
D/LocalBluetoothProfileManager( 5652): Adding local MAP profile
D/BluetoothMap( 5652): Create BluetoothMap proxy object
D/BluetoothManagerService(  881): Message: 30
E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/BluetoothManagerService(  881): Message: 30
D/LocalBluetoothProfileManager( 5652): LocalBluetoothProfileManager construction complete
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend false
D/DockEventReceiver( 5652): finishStartingService: stopping service
D/BluetoothA2dp( 5652): Proxy object connected
E/wpa_supplicant( 5674): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  881): Unexpected BatchedScanResults :null
D/A2dpProfile( 5652): Bluetooth service connected
E/wpa_supplicant( 5674): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  881): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@9ba4400 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@9ba4400 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothHeadset( 5652): Proxy object connected
D/HeadsetProfile( 5652): Bluetooth service connected
D/BluetoothInputDevice( 5652): Proxy object connected
D/HidProfile( 5652): Bluetooth service connected
D/BluetoothPan( 5652): BluetoothPAN Proxy object connected
D/PanProfile( 5652): Bluetooth service connected
D/BluetoothMap( 5652): Proxy object connected
D/MapProfile( 5652): Bluetooth service connected
D/BluetoothMap( 5652): getConnectedDevices()
D/BluetoothPbap( 5652): Proxy object connected
D/PbapServerProfile( 5652): Bluetooth service connected
,E/DHCPCD  ( 5766): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5766): version 5.5.6 starting
,E/DHCPCD  ( 5766): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 5766): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 5766): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 5766): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 5766): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 5766): wlan0: sending REQUEST (xid 0x2ea3cfd4), next in 4.04 seconds
,I/DHCPCD  ( 5766): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 5766): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 5766): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 5766): wlan0: adding route to 192.168.1.0/24
D/TCMD    (  482): NL - Read 60 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 20
D/TCMD    (  482): Listening for incoming client connection request
D/DHCPCD  ( 5766): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5766): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5766): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend true
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  881): WifiStateMachine DHCP successful
E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  881): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  881): Adding iface wlan0 to network 100
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): ConnectedState Enter  mScreenOn=false scanperiod=20000
,E/ConnectivityService(  881): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  881): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  881): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  881): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  881): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  881): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  881):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  881): Setting tx/rx TCP buffers to 131072,262144,3145728,4096,221184,3145728
,D/CSLegacyTypeTracker(  881): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  881): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1508): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1508): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1508): onReceive() - done, currentInetCondition=0
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1939): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jan 2016 11:02:51 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452596571456], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452596571418]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Validated
D/ConnectivityService(  881): Validated NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  881): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1939): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1508): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1290): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1508): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1508): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1508): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  881): send {62ccaf5, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  881): done {62ccaf5, *walarm*:com.google.android.intent.action.SEND_IDLE} [3ms]
,E/global frequency( 2469): no tags to log
,D/Checkin ( 2469): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2469): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  881): Explicit concurrent mark sweep GC freed 44929(2MB) AllocSpace objects, 4(226KB) LOS objects, 33% free, 20MB/30MB, paused 1.994ms total 130.112ms
,D/BSUtils ( 2469): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2469): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2469): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 38407(2MB) AllocSpace objects, 16(571KB) LOS objects, 39% free, 7MB/12MB, paused 742us total 34.817ms
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,D/BSUtils ( 2469): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2469): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2469): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2469): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2469): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2469): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2469): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2469): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2469): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2469): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2469): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2469): BcsDSCheckin.events found events 273
,D/Checkin ( 2469): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2469): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2469): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 3524(139KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 757us total 29.565ms
,I/MMApiWSBase( 2469): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2469): publish the event [tag = MOT_CCE event name = LOG]
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2469): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2469): now: 197841 ,futureTime: 9223372036854775807
D/PollingManager( 2469): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1464): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2469): now: 197842 ,futureTime: 9223372036854775807
D/PollingManager( 2469): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  881): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  881): Setting time of day to sec=1452596574
,W/AlarmManagerService(  881): Unable to set rtc to 1452596574: Invalid argument
,D/PollingManager( 2469): now: 197886 ,futureTime: 9223372036854775807
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5841 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  881): send {c004476, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,D/OtaApp  ( 2469): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1464): now: 197940 ,futureTime: 86476140
D/Central_PollingManager( 1464): Polling alarm set to expire at: 86476140 Current Time: 197940
,D/OtaApp  ( 2469): [debug] > PollingManagerService, now: 197948 ,futureTime: 25281068
D/OtaApp  ( 2469): [debug] > Polling alarm set to expire at: 25281068 Current Time: 197949
,D/MMApiProvisionService( 2469): isDeviceProvisioned: deviceId = 2072049230914535424
,E/GpsLocationProvider(  881): No APN found to select.
,D/GpsLocationProvider(  881): NTP server returned: 1452596571931 (Tue Jan 12 12:02:51 GMT+01:00 2016) reference: 194903 certainty: 14 system time offset: -3145
,I/art     ( 2469): Explicit concurrent mark sweep GC freed 22441(1327KB) AllocSpace objects, 2(55KB) LOS objects, 40% free, 11MB/19MB, paused 992us total 93.986ms
,E/LocSvc_ApiV02(  881): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,D/CCE     ( 2469): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2469): createDeviceIdOrLogin update_device
,D/Checkin ( 2469): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2469): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2469): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2469): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,E/ActivityThread( 1939): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  881): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 230311, reason: UserStart
,I/art     (  881): Explicit concurrent mark sweep GC freed 12364(576KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.706ms total 127.186ms
,D/MMApiProvisionService( 2469): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2469): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2469): createDeviceIdOrLogin update_device
D/Checkin ( 2469): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWSBase( 2469): doRequest(): v1/cs/checkin resp length: 4
,D/MMApiProvisionService( 2469): isDeviceProvisioned: deviceId = 2072049230914535424
,I/MusicStore( 5841): Database version: 120
,D/CCE     ( 2469): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
D/CCE     ( 2469): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/global frequency( 2469): BcsCore.status() called with error code=ERROR_OK
,D/MMApiWebService( 2469): generating token using payload instead of using session token
,D/Checkin ( 2469): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/MMApiProvisionService( 2469): isRequestAllowed(): already have outstanding request ... ignoring request
,D/MMApiWebService( 2469): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2469): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiProvisionService( 2469): isDeviceProvisioned: deviceId = 2072049230914535424
,D/ Nonce  ( 2469):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/CCE     ( 2469): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2469): createDeviceIdOrLogin update_device
,D/Checkin ( 2469): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2469): Not proxy app, so login/provision not allowed
,I/MMApiWSBase( 2469): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2469): publish the event [tag = MOT_CCE event name = LOG]
,D/OtaApp  ( 2469): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2469): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2469): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2469): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2469): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2469): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2469): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2469): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2469): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2469): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5841): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/MMApiWSBase( 2469): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2469): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5841): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5841): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/CheckinProvider(  881): 273 events delete 0 left
,E/Auth.Api.Credentials( 1939): [CredentialSyncAdapter] Unknown sync event.
,D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games,
,D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
,W/ResourcesManager( 5841): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5841): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5841): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/GoogleURLConnFactory( 1714): Using platform SSLCertificateSocketFactory
,W/ActivityThread( 5841): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5841): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5078d29: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5841): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5841): GMSCore installation verified
,I/ConfigStore( 5841): Config Database version: 1
,I/GamesSyncServiceMain( 1939): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 1939): Failed to execute periodic sync, missing client context - aborting
,I/PhenotypeConfigurator( 1714): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/MediaRouter( 5841): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,W/DataUsage( 2469): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2469): publish the event [tag = MOT_CCE event name = LOG]
,V/MusicLeanback( 5841): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5841): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5841): type=WIFI subType= reason=null isConnected=true
,I/ Nonce  ( 2469):  Nonce Reponse 
D/        ( 2469): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"0f694ab4-e6f2-4b96-99be-7e1207e7e252"}
D/MMApiWSBase( 2469): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2469):  Nonce Handle Reponse 
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5907 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/MMApiProvisionService( 2469): mOutstandingReq set to false
I/global frequency( 2469): BcsDSCheckin.events found events 0
,D/Checkin ( 2469): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/GHttpClientFactory( 5841): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5841): Using platform SSLCertificateSocketFactory
,I/BSUtils ( 2469): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 2469): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,V/Mms     ( 5907): mnc/mcc: 
V/Mms     ( 5907): tag: int value: recipientLimit - 20
V/Mms     ( 5907): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 5907): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 5907): tag: int value: maxSubjectLength - 80
V/Mms     ( 5907): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 5907): tag: bool value: enableGroupMms - false
,V/Mms     ( 5907):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/MMApiWSBase( 2469): doRequest(): v1/gns/list/messages resp length: 1363
,D/CCE     ( 2469): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 2469): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 3421(142KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 517us total 43.656ms
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1939): CM callback handler got msg 524295
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/Checkin ( 2469): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 2469): handleGetNotificationsResponse(): got 0; more=false
,D/MMApiProvisionService( 2469):  pTime 1452467391223 sExp 172742 cTime 1452596576333 tTime 1452640133223
D/MMApiProvisionService( 2469):  No login Required 
,W/ResourcesManager( 5907): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5933 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  881): Explicit concurrent mark sweep GC freed 19890(839KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.968ms total 135.632ms
,I/art     ( 1537): Explicit concurrent mark sweep GC freed 29959(1920KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 833us total 87.378ms
,D/PhoneMonitor( 5933): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 5933): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5933): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 5453:com.android.vending/u0a32 (adj 15): empty #7
,W/DataUsage( 2469): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2469): publish the event [tag = MOT_CCE event name = LOG]
,W/DataUsage( 2469): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2469): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_5453/cgroup.procs: No such file or directory
,I/CheckinService( 1939): Checkin interval check for package: unspecified last checkin: 1452528668873 min interval config: 0 actual interval: 67907960
,I/CheckinService( 1939): Checking schedule, now: 1452596576845 next: 1452528698844
I/CheckinService( 1939): active receiver: enabled
,W/PhenotypeConfigurator( 1714): Server returned 404
,I/iu.SyncManager( 1939): SYNC; picasa accounts
,I/CheckinService( 1939): Preparing to send checkin request
,I/EventLogService( 1939): Accumulating logs since 1452596238147
,D/NetworkLogImpl( 1939): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1939): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1939): num queued entries: 0
I/iu.UploadsManager( 1939): num updated entries: 0
,I/iu.SyncManager( 1939): NEXT; no task
,I/art     ( 1714): Explicit concurrent mark sweep GC freed 42966(2MB) AllocSpace objects, 14(247KB) LOS objects, 39% free, 13MB/22MB, paused 1.281ms total 101.621ms
,E/DataBuffer( 1714): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2f2214c1)
E/DataBuffer( 1714): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@21bd466)
E/DataBuffer( 1714): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d74b3a7)
E/DataBuffer( 1714): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@23979054)
E/DataBuffer( 1714): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@a7a3bfd)
,I/GoogleURLConnFactory( 1939): Using platform SSLCertificateSocketFactory
,I/CheckinRequestBuilder( 1939): Checkin reason type: 8 attempt count: 1
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiService(  881): New client listening to asynchronous messages
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=5972 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 1939): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 4227): Explicit concurrent mark sweep GC freed 1685(64KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 733us total 24.090ms
,I/art     ( 1939): Explicit concurrent mark sweep GC freed 22843(1669KB) AllocSpace objects, 36(576KB) LOS objects, 39% free, 14MB/24MB, paused 1.905ms total 157.545ms
,I/GCM     ( 1714): GCM config loaded
,I/ActivityManager(  881): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6004 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6021 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6021): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6004): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6004): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6004): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel_SMS( 6021): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6021): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6021): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6021): MmsConfig.loadFromDatabase
,W/System  ( 6004): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6004): Installed default security provider GmsCore_OpenSSL
,E/Babel_SMS( 6021): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6021): MmsConfig.loadFromResources
,E/Babel_SMS( 6021): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6021): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6021): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6021): startup - clean
,I/Babel   ( 6021): deleted: false for 0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6059 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.130ms
,I/MDMCTBK (  306): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  306): NetlinkHandler, interfaceAdded
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
E/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
,I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  306): , Wifi = 1
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  306): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  306): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  306): get_property_value, Exit
I/MDMCTBK (  306): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1207407336
I/MDMCTBK (  306): return from set_get_from_wpa_supplicant
I/MDMCTBK (  306): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,D/MDMCTBK (  306): wifi_set_tx_pwr: SETTXPOWER = 18
,I/MDMCTBK (  306): send SAR ctrl over QMI
E/MDMCTBK (  306): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  306): , reply_len: 3, ret: 0
E/MDMCTBK (  306): MdmCutbackHndler, resp=OK
E/MDMCTBK (  306): 
D/MDMCTBK (  306): wifi_set_tx_pwr: Exit
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 26.193ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.994ms
,E/YouTube MDX( 6004): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
W/VideoCapabilities( 6021): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6021): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6021): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6021): Unsupported profile 4 for video/mp4v-es
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6004): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
W/VideoCapabilities( 6021): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6021): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6021): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6021): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6021): onServiceConnected
W/Babel   ( 6021): Attempted to change video mute state without an active call.
,W/ResourcesManager( 6004): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6004): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel   ( 6021): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 5652:com.android.settings/1000 (adj 15): empty #7
,I/dex2oat ( 6101): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-745661997.jar --oat-fd=38 --oat-location=/data/data/com.google.android.youtube/cache/ads-745661997.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
W/libprocessgroup(  881): failed to open /acct/uid_1000/pid_5652/cgroup.procs: No such file or directory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6004): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6004): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,I/PeopleSync( 1939): onPerformSync() [5005f081]
,W/ContextImpl( 6004): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,I/dex2oat ( 6101): dex2oat took 195.093ms (threads: 4)
,I/art     (  881): Explicit concurrent mark sweep GC freed 25192(1087KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.319ms total 144.011ms
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/InstanceID/Rpc( 6004): Found 10016
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6059): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6059): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6004): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/GAv4    ( 6059): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6059):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6059):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6059): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6059): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager(  881): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6123 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/art     ( 5428): Attempt to remove local handle scope entry from IRT, ignoring
,W/GAv4    ( 6059): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  881): Killing 5705:com.motorola.context/u0a8 (adj 15): empty #7
,W/GAv4    ( 6059): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6059): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_5705/cgroup.procs: No such file or directory
,W/ResourcesManager( 6123): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6123): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6123): VM with version 2.1.0 has multidex support
I/MultiDex( 6123): install
I/MultiDex( 6123): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6123): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6123): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6123): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b088376: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6123): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6123): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6123): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309638, SEQNUM=4416, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-351, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5611): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5611): Disconnected process message: 10, size: 0
,D/NativeLibraryUtils( 6123): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  308): Instantiating CDM.
,I/WVCdm   (  308): CdmEngine::OpenSession
I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  308): Service_Initialize: starts!
,D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  308): App is not loaded in QSEE
,E/QSEECOMAPI: (  308): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa1000
E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa1000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb546f960
D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb7ee6c60, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7f2d7a8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb7ffcda8, idLength=0xb0368730
,D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  308): PrepareKeyRequest: nonce=1177170587
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7eff408
D/DrmWidevineDash(  308): message_length=1591, signature=0xb7f04500, signature_length=2956363540
,I/GoogleURLConnFactory( 6123): Using platform SSLCertificateSocketFactory
,I/WebViewFactory( 6059): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6059): Time to load native libraries: 2 ms (timestamps 3686-3688)
,I/LibraryLoader( 6059): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6059): Binding Chromium to main looper Looper (main, tid 1) {2076b626}
I/LibraryLoader( 6059): Expected native library version number "",actual native library version number ""
I/chromium( 6059): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6059): Initializing chromium process, singleProcess=true
W/art     ( 6059): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6059): ApplicationContext is null in ApplicationStatus
,W/chromium( 6059): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6059): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6059): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6059): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6059): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6059): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6059): Local Branch: 
I/Adreno-EGL( 6059): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6059): Local Patches: NONE
I/Adreno-EGL( 6059): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  308): CdmEngine::CloseSession
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  308): L3 Terminate.
D/DrmWidevineDash(  308): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  308): Service_Uninitialize: starts!
D/QSEECOMAPI: (  308): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  308): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  308): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,W/AudioManagerAndroid( 6059): Requires BLUETOOTH permission
,I/NSApplication( 6059): Starting up...
,I/ActivityManager(  881): Killing 5841:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_5841/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6220 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 5907:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_5907/cgroup.procs: No such file or directory
,D/WVCdm   (  308): Instantiating CDM.
,I/WVCdm   (  308): CdmEngine::OpenSession
I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  308): Service_Initialize: starts!
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa0000
E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa0000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb556f960
D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb7eea998, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7f2d7a8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb7ffcde8, idLength=0xbee3e2b0
,D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  308): PrepareKeyRequest: nonce=3880086848
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7ec9648
D/DrmWidevineDash(  308): message_length=1626, signature=0xb7f2a1b0, signature_length=3202605716
,I/ActivityManager(  881): Killing 5933:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  308): CdmEngine::CloseSession
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  308): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  308): L3 Terminate.
D/DrmWidevineDash(  308): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  308): Service_Uninitialize: starts!
D/QSEECOMAPI: (  308): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  308): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  308): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_5933/cgroup.procs: No such file or directory
,I/PeopleSync( 1939): Setting subscription: result=true [5005f081]
,I/PeopleSync( 1939): Starting sync, feed=null [5005f081]
,I/jxcore-log( 5559): Test app app.js loaded
I/jxcore-log( 5559): 
,I/chromium( 5559): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/dex2oat ( 6246): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,I/PeopleSync( 1939): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=6260 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 6260): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/dex2oat ( 6246): dex2oat took 310.694ms (threads: 4)
,I/Adreno-EGL( 6123): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6123): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6123): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6123): Local Branch: 
I/Adreno-EGL( 6123): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6123): Local Patches: NONE
I/Adreno-EGL( 6123): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  881): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=6283 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 5972:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/Adreno-EGL( 6123): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6123): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6123): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6123): Local Branch: 
I/Adreno-EGL( 6123): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6123): Local Patches: NONE
I/Adreno-EGL( 6123): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_5972/cgroup.procs: No such file or directory
,E/SQLiteLog( 6283): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  881): Killing 6021:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6021/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6123): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6123): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6123): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6123): Local Branch: 
I/Adreno-EGL( 6123): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6123): Local Patches: NONE
I/Adreno-EGL( 6123): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  881): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6303 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6321 uid=10096 gids={50096, 9997} abi=armeabi-v7a
,I/Adreno-EGL( 6123): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6123): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6123): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6123): Local Branch: 
I/Adreno-EGL( 6123): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6123): Local Patches: NONE
I/Adreno-EGL( 6123): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ResourcesManager( 6303): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/AbstractGoogleClient( 6283): Application name is not set. Call Builder#setApplicationName.
,I/CalendarProvider2( 6303): Created com.android.providers.calendar.CalendarAlarmManager@2b5f26a7(com.android.providers.calendar.CalendarProvider2@1748754)
,I/System.out( 6321): TimeService: Loaded Library 
D/TimeService( 6321): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452596583017
D/        ( 6321): TimeServiceNative: User Time to be set is 1452596583017
D/QC-time-services( 6321): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6321): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6321): Lib:time_genoff_operation: pargs->ts_val = 1452596583017
D/QC-time-services( 6321): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  339): Daemon: Connection accepted:time_genoff
D/QC-time-services(  339): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452596583017
D/QC-time-services(  339): Daemon:genoff_opr: Base = 2, val = 1452596583017, operation = 0
D/QC-time-services(  339): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/12/116 11:1:33
,D/QC-time-services(  339): Daemon:Value read from RTC seconds = 1452596493000
D/QC-time-services(  339): Daemon:new time 1452596583017 
D/QC-time-services(  339): Daemon: delta 90017 genoff 90017 
D/QC-time-services(  339): Daemon:genoff_persistent_update: Writing genoff = 90017 to memory
D/QC-time-services(  339): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  339): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  339): Updating the TOD offset
D/QC-time-services(  339): Daemon:genoff_persistent_update: Writing genoff = 90017 to memory
D/QC-time-services(  339): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  339): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  339): Daemon:Update to modem bit set
D/QC-time-services(  339): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 6321): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  339): Daemon: Base = 2, Value being sent to MODEM = 18446743757744841633
,I/ActivityManager(  881): Killing 6059:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,E/QC-time-services(  339): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  339): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinRequestBuilder( 1939): Classify the device as Phone.
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_6059/cgroup.procs: No such file or directory
,I/CheckinService( 1939): Checkin interval check for package: unspecified last checkin: 1452528668873 min interval config: 0 actual interval: 67914454
,I/VacuumService( 1714): Vacuum at: now=1452596583342 tag=VacuumService
,I/AnalyticsLogBase( 6283): PlayLogger.onLoggerConnected
,I/AnalyticsLogBase( 6283): PlayLogger.onLoggerConnected
,I/CheckinTask( 1939): Sending checkin request (9941 bytes)
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  881): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=6355 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/PhenotypeConfigurator( 1714): Scheduling Phenotype for one-off execution 11281 seconds from now (1452596583826)
,D/GetConfigurationSnapshotOperation( 1714): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/GAv4    ( 6355): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6355):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6355):   adb logcat -s GAv4
,I/CheckinResponseProcessor( 1939): From server: 4 gservices updates and 0 deletes
,W/GAv4    ( 6355): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6355): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6355): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 4227): Explicit concurrent mark sweep GC freed 2853(109KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 460us total 35.761ms
,I/PhenotypeFlagCommitter( 1714): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1714): Using platform SSLCertificateSocketFactory
,I/art     (  881): Explicit concurrent mark sweep GC freed 24785(1194KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.821ms total 124.287ms
,V/AlarmManager(  881): done {c004476, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [9283ms]
,D/EmailService.MarketingOptInSetter( 2469): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 2469): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/PushService( 2469): started with background data enabled, making sure notification mechanism is enabled
E/SQLiteLog( 2469): (284) automatic index on registration(APP_ID)
,D/OtaApp  ( 2469): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/WaitableIntentService( 2469): ServiceHandler.handleMessage: mWaitCount=1
,D/OtaApp  ( 2469): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2469): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  881): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2469): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2469): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2469): publish the event [tag = MOT_OTA event name = LOG]
I/CalendarProvider2( 6303): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6303): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/OtaApp  ( 2469): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2469): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2469): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2469): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2469): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2469): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2469): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2469): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2469): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1409): onFinishInput()
,W/IInputConnectionWrapper( 5559): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  881): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,169
,I/CertBlacklister(  881): Certificate blacklist changed, updating...
,I/GservicesProvider( 4227): main difference update completed
,I/CheckinRequestBuilder( 1939): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1939): Failed to find provider info for com.google.android.wearable.settings
,I/SundryService( 2469): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
,D/WaitableIntentService( 2469): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 2469): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 2469): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2469): unbindWebServices(): un-registering our AIDL callback...
,I/CertBlacklister(  881): Certificate blacklist updated
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6396 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6396): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Killing 6004:com.google.android.youtube/u0a101 (adj 15): empty #7
,I/PeopleSync( 1939): Sync finished, successful=true, took 2636ms
,W/libprocessgroup(  881): failed to open /acct/uid_10101/pid_6004/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 1939): Classify the device as Phone.
,I/art     ( 4227): Explicit concurrent mark sweep GC freed 8785(433KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 530us total 48.543ms
,I/Babel_SMS( 6396): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6396): MmsConfig.loadMmsSettings
I/Babel_SMS( 6396): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6396): MmsConfig.loadFromDatabase
,I/CalendarSyncAdapter( 6283): Found no pending settings
,I/ActivityManager(  881): Killing 6220:com.android.chrome/u0a52 (adj 15): empty #7
,E/Babel_SMS( 6396): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6396): MmsConfig.loadFromResources
I/CheckinTask( 1939): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,E/Babel_SMS( 6396): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6396): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     ( 1939): Explicit concurrent mark sweep GC freed 32164(2MB) AllocSpace objects, 14(247KB) LOS objects, 24% free, 15MB/20MB, paused 1.329ms total 113.848ms
,W/SQLiteConnectionPool( 1939): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_6220/cgroup.procs: No such file or directory
,I/CheckinService( 1939): Checking schedule, now: 1452596585099 next: 1453197721981
I/CheckinService( 1939): active receiver: disabled
,I/PeopleContactsSync( 1939): CP2 sync start [5005f081]
,I/PeopleContactsSync( 1939): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 1939): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,D/CheckinService( 1939): Recording last checkin time for package unspecified as 1452596585131
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6425 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/Settings( 6396): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6396): startup - clean
,I/Babel   ( 6396): deleted: false for 0
,I/GCoreUlr( 1714): Uploading GCM registration ID for account#2#
,W/art     ( 6396): Suspending all threads took: 6.212ms
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6449 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ContactLocale( 6425): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  881): Killing 6260:com.motorola.context/u0a8 (adj 15): empty #7
,W/VideoCapabilities( 6396): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6396): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6396): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6396): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6396): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6396): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6396): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6396): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_6260/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 5428:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/vclib   ( 6396): onServiceConnected
W/Babel   ( 6396): Attempted to change video mute state without an active call.
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_5428/cgroup.procs: No such file or directory
,W/BaseAppContext( 1714): Using Auth Proxy for data requests.
,W/ProcessCpuTracker(  881): Skipping unknown process pid 6384
,W/ProcessCpuTracker(  881): Skipping unknown process pid 6467
,W/ProcessCpuTracker(  881): Skipping unknown process pid 6468
,I/PeopleContactsSync( 1939): CP2 cleanup done, kept= duration=847 ms
,I/PeopleContactsSync( 1939): ===CP2 sync finished, success=true, time=864,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/PeopleSync( 1939): ***Sync finished***, duration: 6585 [5005f081]
,I/art     ( 1714): Explicit concurrent mark sweep GC freed 103544(5MB) AllocSpace objects, 31(496KB) LOS objects, 40% free, 14MB/24MB, paused 3.934ms total 133.678ms
,D/GCM     ( 1714): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,I/ActivityManager(  881): Killing 6355:com.google.android.deskclock/u0a55 (adj 13): empty #7
,I/ActivityManager(  881): Killing 6321:com.qualcomm.timeservice/u0a96 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10055/pid_6355/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10096/pid_6321/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 6303:com.android.providers.calendar/u0a5 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10005/pid_6303/cgroup.procs: No such file or directory
,D/LocationInitializer( 1939): Restart initialization of location
,D/WearableService( 1714): callingUid 10016, callindPid: 1714
,D/AuthorizationBluetoothService( 1714): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/BaseAppContext( 1714): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,E/MDM     ( 1714): [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6493 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 22.499ms
,W/GCoreFlp( 1714): No location to return for getLastLocation()
W/FusedLocationProvider( 1714): location=null
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.049ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 22.601ms
,D/ActivityThread( 6493): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/Gmail   ( 6493): getAccountsCursor
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=6519 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=6536 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1537): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  881): Explicit concurrent mark sweep GC freed 24831(1149KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 2.842ms total 166.310ms
,W/ActivityManager(  881): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 6536): EasService.onCreate
,I/Gmail   ( 6493): Observing account changes for notifications
,I/MusicStore( 6519): Database version: 120
,I/Exchange( 6536): RestartPingTask
W/GAV2    ( 6493): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task.xml
,I/Exchange( 6536): RestartPingsTask did not start any pings.
I/Exchange( 6536): PSS stopIfIdle
I/Exchange( 6536): PSS has no active accounts; stopping service.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6519): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/Exchange( 6536): onDestroy
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  881): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  881): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Gmail   ( 6493): getAccountsCursor
,V/BackupManagerService(  881): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@11362707
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6519): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6519): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/Gmail   ( 6493): Sync started for account: account:61035162
,I/Launcher( 1555): Deferring update until onResume
,W/ResourcesManager( 6519): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6519): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/SQLiteLog( 6493): (283) recovered 159 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,V/JNIHelp ( 6519): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreNlp( 1714): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ActivityThread( 6519): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6519): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5078d29: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6519): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6519): GMSCore installation verified
,I/ConfigStore( 6519): Config Database version: 1
,I/Gmail   ( 6493): notifyAccountChanged
,I/Gmail   ( 6493): getAccountsCursor
I/art     ( 4227): Explicit concurrent mark sweep GC freed 3014(123KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 939us total 25.794ms
,I/Gmail   ( 6493): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/GCoreUlr( 1714): GCM ID uploaded for account#2#
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6493): notifyAccountChanged
,I/Gmail   ( 6493): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6493): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6493): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/ContextImpl( 6283): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/MediaRouter( 6519): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GCoreUlr( 1714): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GAV2    ( 6283): Thread[GAThread,5,main]: No campaign data found.
,I/NetworkMonitor( 6519): type=WIFI subType= reason=null isConnected=true
I/Gmail   ( 6493): getAccountsCursor
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6594 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/GCoreUlr( 1714): DispatchingService.onCreate()
,W/ResourcesManager( 6594): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Gmail   ( 6493): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 14380, normalSync: true
,I/MusicLeanback( 6519): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6519): Stop autocaching.
,I/NetworkMonitor( 6519): type=WIFI subType= reason=null isConnected=true
,I/MusicLeanback( 6519): Stop autocaching.
I/MusicLeanback( 6519): Stop autocaching.
,I/MusicLeanback( 6519): Stop autocaching.
,I/GHttpClientFactory( 6519): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6519): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/GmsUtils( 6519): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6519): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ResourcesManager( 6493): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6493): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6631 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/JNIHelp ( 6493): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6648 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6396:com.google.android.talk/u0a70 (adj 15): empty #7
,I/GCoreUlr( 1714): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/System  ( 6493): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6493): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6396/cgroup.procs: No such file or directory
,I/art     (  881): Explicit concurrent mark sweep GC freed 18851(939KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.612ms total 117.016ms
,I/ActivityManager(  881): Killing 6449:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/ResourcesManager( 6631): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_6449/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 6536:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,I/CalendarProvider2( 6631): Created com.android.providers.calendar.CalendarAlarmManager@2b5f26a7(com.android.providers.calendar.CalendarProvider2@1748754)
,W/ResourcesManager( 6648): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/GCoreUlr( 1714): Unbound from all location providers
,W/libprocessgroup(  881): failed to open /acct/uid_10060/pid_6536/cgroup.procs: No such file or directory
I/GCoreUlr( 1714): Place inference reporting - stopped
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6673 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/GCoreUlr( 1714): DispatchingService.onDestroy()
I/GCoreUlr( 1714): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1714): Unbound from all location providers
I/GCoreUlr( 1714): Place inference reporting - stopped
,I/ActivityManager(  881): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6700 uid=10054 gids={50054, 9997, 3003} abi=armeabi-v7a
,I/GoogleHttpClient( 4227): GMS http client unavailable, use old client
,E/UpdateRequestReceiver( 6700): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6700): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6700): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6700): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/CheckinService( 1939): Checkin interval check for package: unspecified last checkin: 1452596585131 min interval config: 0 actual interval: 3941
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 1939): Checking schedule, now: 1452596589101 next: 1453197721981
I/CheckinService( 1939): active receiver: disabled
,I/SystemUpdateService( 1939): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1939): onCreate
,D/SystemUpdateService( 1939): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/art     ( 4227): Explicit concurrent mark sweep GC freed 6444(320KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.202ms total 40.503ms
,I/SystemUpdateService( 1939): cancelUpdate (empty URL)
I/SystemUpdateService( 1939): active receiver: disabled
,D/ContactsSyncAdapter( 4227): ForbiddenException, ignoring rest of feed
D/ContactsSyncAdapter( 4227): com.google.wireless.gdata2.client.ForbiddenException: Could not fetch feed https://www.google.com/m8/feeds/groups/thalitester@gmail.com/base2_property-android?sortorder=ascending&showdeleted=true&max-results=500&requirealldeleted=true&updated-min=2016-01-11T07%3A55%3A15.652Z&orderby=lastmodified com.google.wireless.gdata2.client.HttpException: Received 403 status code: <?xml version="1.0" encoding="UTF-8"?>
D/ContactsSyncAdapter( 4227): <errors xmlns="http://schemas.google.com/g/2005">
D/ContactsSyncAdapter( 4227):  <error>
D/ContactsSyncAdapter( 4227):   <domain>usageLimits</domain>
D/ContactsSyncAdapter( 4227):   <code>rateLimitExceededUnreg</code>
D/ContactsSyncAdapter( 4227):   <internalReason>Rate Limit Exceeded. Please sign up</internalReason>
D/ContactsSyncAdapter( 4227):   <extendedHelp>https://code.google.com/apis/console</extendedHelp>
D/ContactsSyncAdapter( 4227):  </error>
D/ContactsSyncAdapter( 4227): </errors>
D/ContactsSyncAdapter( 4227): 
D/ContactsSyncAdapter( 4227): 	at com.google.wireless.gdata2.client.GDataServiceClient.convertHttpExceptionForFeedReads(GDataServiceClient.java:433)
D/ContactsSyncAdapter( 4227): 	at com.google.wireless.gdata2.client.GDataServiceClient.getParserForFeed(GDataServiceClient.java:111)
D/ContactsSyncAdapter( 4227): 	at com.google.android.syncadapters.contacts.GDataFeedFetcher.fetchFeed(GDataFeedFetcher.java:185)
D/ContactsSyncAdapter( 4227): 	at com.google.android.syncadapters.contacts.GDataFeedFetcher.run(GDataFeedFetcher.java:100)
D/ContactsSyncAdapter( 4227): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter$ContactsGDataFeedFetcher.run(ContactsSyncAdapter.java:1413)
D/ContactsSyncAdapter( 4227): 	at java.lang.Thread.run(Thread.java:818)
D/ContactsSyncAdapter( 4227): Caused by: com.google.wireless.gdata2.client.HttpException: Received 403 status code: <?xml version="1.0" encoding="UTF-8"?>
D/ContactsSyncAdapter( 4227): <errors xmlns="http://schemas.google.com/g/2005">
D/ContactsSyncAdapter( 4227):  <error>
D/ContactsSyncAdapter( 4227):   <domain>usageLimits</domain>
D/ContactsSyncAdapter( 4227):   <code>rateLimitExceededUnreg</code>
D/ContactsSyncAdapter( 4227):   <internalReason>Rate Limit Exceeded. Please sign up</internalReason>
D/ContactsSyncAdapter( 4227):   <extendedHelp>https://code.google.com/apis/console</extendedHelp>
D/ContactsSyncAdapter( 4227):  </error>
D/ContactsSyncAdapter( 4227): </errors>
D/ContactsSyncAdapter( 4227): 
D/ContactsSyncAdapter( 4227): 	at com.google.android.common.gdata2.AndroidGDataClient.createAndExecuteMethod(AndroidGDataClient.java:397)
D/ContactsSyncAdapter( 4227): 	at com.google.android.syncadapters.HttpsOnlyAndroidGDataClient.createAndExecuteMethod(HttpsOnlyAndroidGDataClient.java:32)
D/ContactsSyncAdapter( 4227): 	at com.google.android.common.gdata2.AndroidGDataClient.getFeedAsStream(AndroidGDataClient.java:415)
D/ContactsSyncAdapter( 4227): 	at com.google.wireless.gdata2.client.GDataServiceClient.getParserForFeed(GDataServiceClient.java:108)
D/ContactsSyncAdapter( 4227): 	... 4 more
,D/ContactsSyncAdapter( 4227): getServerDiffs failed
D/ContactsSyncAdapter( 4227): com.google.wireless.gdata2.parser.ParseException: unparsable feed https://www.google.com/m8/feeds/groups/thalitester@gmail.com/base2_property-android
D/ContactsSyncAdapter( 4227): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.getServerDiffs(ContactsSyncAdapter.java:1218)
D/ContactsSyncAdapter( 4227): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:290)
D/ContactsSyncAdapter( 4227): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 4227): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 4227): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 4227): FAILURE: processed 0 records in 295 ms from feed https://www.google.com/m8/feeds/groups/thalitester@gmail.com/base2_property-android, updated time is 2016-01-11T07:55:15.652Z
I/ActivityManager(  881): Killing 6519:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/art     ( 1939): Explicit concurrent mark sweep GC freed 9669(500KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 15MB/25MB, paused 1.186ms total 82.914ms
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6519/cgroup.procs: No such file or directory
,D/SyncManager(  881): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 245313, reason: Periodic
,I/art     ( 4227): Explicit concurrent mark sweep GC freed 10782(579KB) AllocSpace objects, 1(39KB) LOS objects, 40% free, 7MB/12MB, paused 786us total 35.874ms
,D/SystemUpdateService( 1939): onDestroy
,I/ActivityManager(  881): Killing 6123:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/CalendarProvider2( 6631): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6631): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_6123/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 6648:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_6648/cgroup.procs: No such file or directory
,E/DynamiteModule( 1939): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1939): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 1939): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1939): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 1939): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 1939): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1939): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1939): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1939): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1939): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1939): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1939): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2611)
E/DynamiteModule( 1939): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/DynamiteModule( 1939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1369)
E/DynamiteModule( 1939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1939): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 1939): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/DynamiteModule( 1939): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 1939): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 1939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/DynamiteModule( 1939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/DynamiteModule( 1939): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 1939): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 1939): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 1939): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 1939): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 1939): 		... 17 more
E/DynamiteModule( 1939): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 1939): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 1939): Selected local version of com.google.android.gms.flags
,D/SystemEventReceiver( 1939): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1939): Updating ocr activity enabled=false
,W/ActivityManager(  881): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1939): Updating downloaded model state (gservices changed)
,I/art     ( 1714): Explicit concurrent mark sweep GC freed 84336(4MB) AllocSpace objects, 27(478KB) LOS objects, 39% free, 14MB/24MB, paused 1.351ms total 122.658ms
,W/Gmail   ( 6493): MailSyncAdapterService#onSyncCanceled Thread[SyncAdapterThread-1,5,main]
W/Gmail   ( 6493): MailEngine != null account: account:61035162
,I/art     ( 4227): Explicit concurrent mark sweep GC freed 3865(147KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 759us total 27.786ms
,I/art     ( 6493): Explicit concurrent mark sweep GC freed 5968(300KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 10MB/14MB, paused 580us total 55.428ms
,I/Gmail   ( 6493): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 14380, normalSync: true
,D/GCM     ( 1714): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,E/Gmail   ( 6493): Connection to search failed: 15
,I/Gmail   ( 6493): notifyAccountChanged
,I/Gmail   ( 6493): getAccountsCursor
,I/Gmail   ( 6493): notifyAccountChanged
,W/Gmail   ( 6493): Sync complete for account: account:61035162
,D/SyncManager(  881): handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 209468, mTimeoutStartTime 209468, mHistoryRowId 14, syncOperation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 52144, reason: Periodic
,I/Gmail   ( 6493): getAccountsCursor
,W/Gmail   ( 6493): Sync started for account: account:61035162
,I/Gmail   ( 6493): notifyAccountChanged
,I/art     (  881): Explicit concurrent mark sweep GC freed 24224(1061KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.677ms total 122.283ms
,I/Gmail   ( 6493): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 14380, normalSync: true
,I/Gmail   ( 6493): getAccountsCursor
,W/ResourcesManager( 6493): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6493): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1714): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=6779 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/GCoreUlr( 1714): DispatchingService.onCreate()
,I/GCoreUlr( 1714): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GeofencerStateMachine( 1714): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1714): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/art     ( 4227): Explicit concurrent mark sweep GC freed 2843(114KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 539us total 28.500ms
,W/ctxmgr  ( 1714): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10016, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1714): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/GCoreUlr( 1714): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1714): Unbound from all location providers
I/GCoreUlr( 1714): Place inference reporting - stopped
,I/GCoreUlr( 1714): DispatchingService.onDestroy()
,I/GCoreUlr( 1714): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1714): Unbound from all location providers
I/GCoreUlr( 1714): Place inference reporting - stopped
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver: pid=6813 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6631:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10005/pid_6631/cgroup.procs: No such file or directory
,I/GservicesUpdateTask( 6779): Updating Gservices keys
,I/ActivityManager(  881): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6846 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/art     ( 1714): Explicit concurrent mark sweep GC freed 36355(1891KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 14MB/23MB, paused 1.572ms total 106.918ms
,W/Herrevad( 1714): mobile connection type with no cell id
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6874 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6594:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/art     (  323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 23.559ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 19.082ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 20.433ms
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6594/cgroup.procs: No such file or directory
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PhoneMonitor( 6874): Register our PhoneStateListener
,I/Gmail   ( 6493): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 14598, normalSync: true
,I/Gmail   ( 6493): lowestBackward conversation id 0
,V/SetupWizard( 6874): Connected to Gservices successfully
I/ActivityManager(  881): Killing 6700:com.google.android.configupdater/u0a54 (adj 15): empty #7
,I/GAv4    ( 6846): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6846):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6846):   adb logcat -s GAv4
,W/libprocessgroup(  881): failed to open /acct/uid_10054/pid_6700/cgroup.procs: No such file or directory
,W/GAv4    ( 6846): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6846): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6846): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Gmail   ( 6493): notifyAccountChanged
,W/Gmail   ( 6493): Sync complete for account: account:61035162
,D/GCM     ( 1714): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Gmail   ( 6493): getAccountsCursor
,W/AnalyticsTrackerProxyImpl( 6846): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6901 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=6919 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6425:android.process.acore/u0a7 (adj 15): empty #7
,W/ResourcesManager( 6901): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GAV2    ( 6493): Thread[GAThread,5,main]: No campaign data found.
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_6425/cgroup.procs: No such file or directory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6846): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 6846): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6846): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6846): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6846): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6846): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel_SMS( 6901): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6901): MmsConfig.loadMmsSettings
I/Babel_SMS( 6901): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6901): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6901): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6901): MmsConfig.loadFromResources
,E/Babel_SMS( 6901): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6901): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/System  ( 6846): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6846): Installed default security provider GmsCore_OpenSSL
,D/WifiService(  881): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@32c9c104}
,W/Settings( 6901): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6901): startup - clean
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 6901): deleted: false for 0
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6919): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6919): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6919): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6919): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6919): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6919):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6919):   adb logcat -s GAv4
,I/art     (  881): Explicit concurrent mark sweep GC freed 15535(782KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.796ms total 136.682ms
,I/ActivityManager(  881): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6965 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/GAv4    ( 6919): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6919): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6919): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/VideoCapabilities( 6901): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6901): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6901): Unsupported mime video/mpeg2
,W/Flag    ( 6846): Duration spec must be at least 2 characters long
,I/VideoCapabilities( 6901): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6901): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6901): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6901): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6901): Unrecognized profile 2130706433 for video/avc
,I/Icing   ( 1939): Indexing 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A from com.google.android.gm
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6989 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6673:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/ContactLocale( 6965): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  881): failed to open /acct/uid_10019/pid_6673/cgroup.procs: No such file or directory
,I/Gmail   ( 6493): Backfilling search sequence table
,W/asset   ( 6989): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6989): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6989): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6989): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/vclib   ( 6901): onServiceConnected
,W/Babel   ( 6901): Attempted to change video mute state without an active call.
,W/ResourcesManager( 6901): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6901): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6901): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 6901): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6901): Installed default security provider GmsCore_OpenSSL
,I/WebViewFactory( 6919): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6919): Time to load native libraries: 3 ms (timestamps 6530-6533)
I/LibraryLoader( 6919): Expected native library version number "",actual native library version number ""
,D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1939): Null package name or gms related package.  Ignoreing.
,V/WebViewChromiumFactoryProvider( 6919): Binding Chromium to main looper Looper (main, tid 1) {2076b626}
,I/LibraryLoader( 6919): Expected native library version number "",actual native library version number ""
,I/chromium( 6919): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/UpdateIcingCorporaServi( 6779): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/BrowserStartupController( 6919): Initializing chromium process, singleProcess=true
W/Launcher( 1555): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2e38439f new=com.google.android.velvet.VelvetApplication@2e38439f
W/art     ( 6919): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6919): ApplicationContext is null in ApplicationStatus
,W/Icing   ( 1939): Content incarnation mismatch: Expected [12a769a562485c59] found [e39f71a46c7591d9]
I/Icing   ( 1939): Indexing done 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A
E/Icing   ( 1939): Aborting indexing of corpus messages/com.google/thalitester%40gmail.com
W/chromium( 6919): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:33000 mC
I/Icing   ( 1939): updateResources: need to parse f{com.google.android.gms}
,E/libEGL  ( 6919): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6919): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6919): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6919): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6919): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6919): Local Branch: 
I/Adreno-EGL( 6919): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6919): Local Patches: NONE
I/Adreno-EGL( 6919): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7043 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7043): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/AudioManagerAndroid( 6919): Requires BLUETOOTH permission
,I/ActivityManager(  881): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7068 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 6779): UpdateCorporaTask done [took 225 ms] updated apps [took 225 ms] 
,I/NSApplication( 6919): Starting up...
,W/ResourcesManager( 7068): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 7068): Created com.android.providers.calendar.CalendarAlarmManager@2b5f26a7(com.android.providers.calendar.CalendarProvider2@1748754)
,I/ActivityManager(  881): Killing 6283:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10049/pid_6283/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 6813:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/SyncAdapterService( 6919): Ignoring sync request for non-current account
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_6813/cgroup.procs: No such file or directory
,I/Icing   ( 1939): Removing corpus key 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A for package com.google.android.gm
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7099 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6874:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_6874/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 6989:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10027/pid_6989/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=7119 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7119): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7119): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7119): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7119): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7119): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7119): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/CalendarProvider2( 7068): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 7068): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,V/JNIHelp ( 7119): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Finsky  ( 7099): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ActivityThread( 7119): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7119): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5078d29: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7119): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7119): GMSCore installation verified
,I/ConfigStore( 7119): Config Database version: 1
,I/Icing   ( 1939): Indexing 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A from com.google.android.gm
,I/art     ( 1939): Explicit concurrent mark sweep GC freed 30243(1954KB) AllocSpace objects, 20(320KB) LOS objects, 24% free, 15MB/21MB, paused 1.315ms total 101.248ms
,D/Finsky  ( 7099): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/Icing   ( 1939): Indexing done 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A
,I/MediaRouter( 7119): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,W/Settings( 7099): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7099): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7099): Skipping gmscore version check
,D/Finsky  ( 7099): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7099): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7099): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/GHttpClientFactory( 7119): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7119): Using platform SSLCertificateSocketFactory
,D/Finsky  ( 7099): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  881): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.WidgetDataReceiver: pid=7190 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NetworkMonitor( 7119): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Killing 6779:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/MusicLifecycle( 7119): Sync started
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_6779/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7119): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 7119): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7119): Using platform SSLCertificateSocketFactory
,E/SQLiteLog( 7190): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
I/ActivityManager(  881): Killing 7068:com.android.providers.calendar/u0a5 (adj 15): empty #7
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=296, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310058, SEQNUM=4440, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-378, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/libprocessgroup(  881): failed to open /acct/uid_10005/pid_7068/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 5611): Disconnected process message: 10, size: 0
,I/ActivityManager(  881): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7218 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/HeadsetStateMachine( 5611): Disconnected process message: 10, size: 0
,I/art     (  881): Explicit concurrent mark sweep GC freed 14829(729KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.644ms total 129.994ms
,W/ResourcesManager( 7218): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 7218): Created com.android.providers.calendar.CalendarAlarmManager@2b5f26a7(com.android.providers.calendar.CalendarProvider2@1748754)
,I/AnalyticsLogBase( 7190): PlayLogger.onLoggerConnected
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7241 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6965:android.process.acore/u0a7 (adj 15): empty #7
,I/art     (  323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 20.567ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.165ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 19.862ms
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_6965/cgroup.procs: No such file or directory
,D/WifiService(  881): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@32c9c104}
,I/ActivityManager(  881): Killing 7043:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 7241): Register our PhoneStateListener
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7043/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 6919:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/Icing   ( 1939): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 1939): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1939): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_6919/cgroup.procs: No such file or directory
,I/MusicSyncAdapter( 7119): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
,I/MusicSyncAdapter( 7119): Periodic update
,I/art     ( 4227): Explicit concurrent mark sweep GC freed 3134(128KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 439us total 28.884ms
,W/MusicApiClient( 7119): Activity events list is null or empty. Skip reporting.
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,I/MusicLifecycle( 7119): Sync ended
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,W/BaseAppContext( 1939): Using Auth Proxy for data requests.
,I/ActivityManager(  881): Killing 7099:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_7099/cgroup.procs: No such file or directory
,I/CheckinService( 1939): Checkin interval check for package: unspecified last checkin: 1452596585131 min interval config: 0 actual interval: 11402
,I/ActivityManager(  881): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=7272 uid=10053 gids={50053, 9997, 3003, 1028} abi=armeabi-v7a
,D/GCM     ( 1714): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 1939): Checking schedule, now: 1452596596594 next: 1452596614981
I/CheckinService( 1939): active receiver: disabled
,I/CalendarProvider2( 7218): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 7218): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=7294 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6493:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10063/pid_6493/cgroup.procs: No such file or directory
,W/ResourcesManager( 7294): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.apps.cloudprint for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService: pid=7312 uid=10053 gids={50053, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7335 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 7272): Sync request not initiated by GCP app. Dropping
,I/ActivityManager(  881): Killing 7218:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10005/pid_7218/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 7241:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/Gmail   ( 7335): getAccountsCursor
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7241/cgroup.procs: No such file or directory
,D/ActivityThread( 7335): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=7361 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.apps.docs.editors.sheets for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService: pid=7380 uid=10105 gids={50105, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  881): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/GAV2    ( 7335): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 7335): Observing account changes for notifications
,I/Exchange( 7361): EasService.onCreate
,I/Exchange( 7361): RestartPingTask
,I/Exchange( 7361): RestartPingsTask did not start any pings.
,I/Exchange( 7361): PSS stopIfIdle
I/Exchange( 7361): PSS has no active accounts; stopping service.
,I/Gmail   ( 7335): getAccountsCursor
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=7416 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7119:com.google.android.music:main/u0a80 (adj 13): empty #7
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1939): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager(  881): Killing 6846:com.google.android.apps.docs/u0a57 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_7119/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10057/pid_6846/cgroup.procs: No such file or directory
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Killing 7312:com.google.android.apps.cloudprint/u0a53 (adj 13): empty #7
,I/Exchange( 7361): onDestroy
,W/libprocessgroup(  881): failed to open /acct/uid_10053/pid_7312/cgroup.procs: No such file or directory
,E/SQLiteLog( 7335): (283) recovered 21 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/AbstractGoogleClient( 7190): Application name is not set. Call Builder#setApplicationName.
,I/Gmail   ( 7335): notifyAccountChanged
,I/Gmail   ( 7335): getAccountsCursor
,I/Gmail   ( 7335): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7335): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7335): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7335): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/art     (  881): Explicit concurrent mark sweep GC freed 18545(839KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.704ms total 117.335ms
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AnalyticsLogBase( 7190): PlayLogger.onLoggerConnected
,D/Finsky  ( 7416): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager(  881): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7450 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7450): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Gmail   ( 7335): getAccountsCursor
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 7450): Created com.android.providers.calendar.CalendarAlarmManager@2b5f26a7(com.android.providers.calendar.CalendarProvider2@1748754)
,D/Finsky  ( 7416): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7416): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7416): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/GAv4    ( 7380): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7380):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7380):   adb logcat -s GAv4
,D/Ads     ( 7416): Skipping gmscore version check
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.download.MusicCommunicator: pid=7490 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 7272:com.google.android.apps.cloudprint:sync/u0a53 (adj 15): empty #7
,D/Finsky  ( 7416): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7416): [1] Libraries$2.run: Finished loading 1 libraries.
,W/libprocessgroup(  881): failed to open /acct/uid_10053/pid_7272/cgroup.procs: No such file or directory
,W/GAv4    ( 7380): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/Finsky  ( 7416): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7416): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/GAv4    ( 7380): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7380): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7380): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.312.11.30
,I/MusicStore( 7490): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7490): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7490): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7490): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityThread( 7490): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7490): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5078d29: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7490): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7490): GMSCore installation verified
,I/ConfigStore( 7490): Config Database version: 1
,I/CalendarSyncAdapter( 7190): Found no pending settings
,V/AlarmManager(  881): send {2e83a395, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {26e5e4f3, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED}
,V/AlarmManager(  881): done {2e83a395, *alarm*:android.intent.action.TIME_TICK} [46ms]
,W/PackageSettings(  881): Skipping PackageSetting{2a00d6a com.example.hello/10440} due to missing metadata
,I/ActivityManager(  881): Killing 6901:com.google.android.talk/u0a70 (adj 15): empty #7
,W/ResourcesManager( 7380): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7380): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6901/cgroup.procs: No such file or directory
,I/MediaRouter( 7490): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 7490): type=WIFI subType= reason=null isConnected=true
,V/JNIHelp ( 7380): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CalendarProvider2( 7450): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 7450): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  881): Killing 7294:com.motorola.context/u0a8 (adj 15): empty #7
,I/ProviderInstaller( 7380): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_7294/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 7361:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10060/pid_7361/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7490): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7558 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/GHttpClientFactory( 7490): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7490): Using platform SSLCertificateSocketFactory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/cache
,D/PhoneMonitor( 7558): Register our PhoneStateListener
,I/CheckinService( 1939): Checkin interval check for package: unspecified last checkin: 1452596585131 min interval config: 0 actual interval: 14304
,D/GCM     ( 1714): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=7586 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
I/CheckinService( 1939): Checking schedule, now: 1452596599494 next: 1452596614981
,I/CheckinService( 1939): active receiver: disabled
,I/art     (  323): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 20.763ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 19.868ms
,I/MusicLeanback( 7490): Stop autocaching.
,I/ActivityManager(  881): Killing 7335:com.google.android.gm/u0a63 (adj 15): empty #7
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.259ms
,W/ResourcesManager( 7586): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/libprocessgroup(  881): failed to open /acct/uid_10063/pid_7335/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7605 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  881): Explicit concurrent mark sweep GC freed 16635(1036KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.880ms total 139.964ms
,I/MusicLeanback( 7490): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 7490): Stop autocaching.
,I/ActivityManager(  881): Killing 7450:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/Gmail   ( 7605): getAccountsCursor
,I/ActivityManager(  881): Killing 7416:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10005/pid_7450/cgroup.procs: No such file or directory
,D/ActivityThread( 7605): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=7632 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_7416/cgroup.procs: No such file or directory
,W/ActivityManager(  881): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 7632): EasService.onCreate
,I/Gmail   ( 7605): Observing account changes for notifications
,I/Exchange( 7632): RestartPingTask
,W/GAV2    ( 7605): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Exchange( 7632): RestartPingsTask did not start any pings.
I/Exchange( 7632): PSS stopIfIdle
I/Exchange( 7632): PSS has no active accounts; stopping service.
,I/Gmail   ( 7605): getAccountsCursor
,I/Exchange( 7632): onDestroy
,I/ActivityManager(  881): Killing 7380:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=298, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310327, SEQNUM=4450, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-391, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/libprocessgroup(  881): failed to open /acct/uid_10105/pid_7380/cgroup.procs: No such file or directory
,V/AlarmManager(  881): done {26e5e4f3, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED} [1394ms]
,I/ActivityManager(  881): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7666 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/HeadsetStateMachine( 5611): Disconnected process message: 10, size: 0
V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/HeadsetStateMachine( 5611): Disconnected process message: 10, size: 0
,I/ActivityManager(  881): Killing 7558:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,E/SQLiteLog( 7605): (283) recovered 22 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 7605): notifyAccountChanged
,I/Gmail   ( 7605): getAccountsCursor
,I/Gmail   ( 7605): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7605): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7558/cgroup.procs: No such file or directory
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7605): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7605): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ResourcesManager( 7666): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/WearableService( 1714): callingUid 10016, callindPid: 1714
,I/CalendarProvider2( 7666): Created com.android.providers.calendar.CalendarAlarmManager@2b5f26a7(com.android.providers.calendar.CalendarProvider2@1748754)
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7190): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,W/ContextImpl( 7490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/cache
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7693 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/GAV2    ( 7190): Thread[GAThread,5,main]: No campaign data found.
,E/GmsUtils( 7490): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7490): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PhoneMonitor( 7693): Register our PhoneStateListener
,I/Gmail   ( 7605): getAccountsCursor
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 1939): Checkin interval check for package: unspecified last checkin: 1452596585131 min interval config: 0 actual interval: 15507
,D/GCM     ( 1714): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 1939): Checking schedule, now: 1452596600650 next: 1452596614981
I/CheckinService( 1939): active receiver: disabled
,D/GCM     ( 1714): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
,I/MDMCTBK (  306): checkDefaultInst, pid match
,I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/CalendarProvider2( 7666): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 7666): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  881): Killing 7632:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10060/pid_7632/cgroup.procs: No such file or directory
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:33000 mC
,E/GmsUtils( 7490): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7490): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 7490): Stop autocaching.
,E/GmsUtils( 7490): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/AlarmManager(  881): send {12426e11, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  881): done {12426e11, *walarm*:android.content.syncmanager.SYNC_ALARM} [6ms]
,I/GAV2    ( 7605): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  881): Waited long enough for: ServiceRecord{1b012681 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=281, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309580, SEQNUM=4459, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-423, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5611): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5611): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1714): disconnect managed GoogleApiClient
,I/ActivityManager(  881): Killing 7693:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ActivityManager(  881): Killing 4227:com.google.process.gapps/u0a16 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7693/cgroup.procs: No such file or directory
W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_4227/cgroup.procs: No such file or directory
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310078, SEQNUM=4463, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-437, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5611): Disconnected process message: 10, size: 0
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  881): send {12426e11, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  881): done {12426e11, *walarm*:android.content.syncmanager.SYNC_ALARM} [6ms]
,I/art     (  881): Explicit concurrent mark sweep GC freed 14988(746KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 6.092ms total 144.826ms
,I/ActivityManager(  881): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7768 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,E/ActivityThread( 1939): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  881): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 322651, reason: UserStart
,I/GAv4    ( 7768): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7768):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7768):   adb logcat -s GAv4
,W/GAv4    ( 7768): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7768): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7768): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7768): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteLog( 7768): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7768): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 7768): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7768): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7768): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7768): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7768): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7768): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7768): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  881): Killing 7605:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10063/pid_7605/cgroup.procs: No such file or directory
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1409): run()
,I/Keyboard.Facilitator( 1409): flushDynamicLanguageModels()
,I/ConfigService( 1714): onCreate
,I/ConfigService( 1714): onDestroy
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=267, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311122, SEQNUM=4471, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-438, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5611): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5611): Disconnected process message: 10, size: 0
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {2e83a395, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {12426e11, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  881): done {12426e11, *walarm*:android.content.syncmanager.SYNC_ALARM} [12ms]
,V/AlarmManager(  881): done {2e83a395, *alarm*:android.intent.action.TIME_TICK} [43ms]
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 5559): --= Surplus to requirements =--
I/jxcore-log( 5559): 
I/jxcore-log( 5559): ****TEST TOOK:  ms ****
I/jxcore-log( 5559): 
I/jxcore-log( 5559): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5559): 
,D/AndroidRuntime( 7825): 
D/AndroidRuntime( 7825): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7825): CheckJNI is OFF
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309970, SEQNUM=4473, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1613, POWER_SUPPLY_CHARGE_COUNTER=-444, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5611): Disconnected process message: 10, size: 0
,D/AndroidRuntime( 7825): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  881): Force stopping com.test.thalitest appid=10441 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 5559:com.test.thalitest/u0a441 (adj 9): stop com.test.thalitest
,W/PackageSettings(  881): Skipping PackageSetting{2a00d6a com.example.hello/10440} due to missing metadata
,D/WifiService(  881): Client connection lost with reason: 4
,I/WindowState(  881): WIN DEATH: Window{2facd962 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  881):   Force finishing activity ActivityRecord{149d116f u0 com.test.thalitest/.MainActivity t3}
,W/ActivityManager(  881): Spurious death for ProcessRecord{214b832d 5559:com.test.thalitest/u0a441}, curProc for 5559: null
,I/ActivityManager(  881): Force stopping com.test.thalitest appid=10441 user=0: pkg removed
,I/art     ( 3106): Explicit concurrent mark sweep GC freed 11985(2MB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 7MB/12MB, paused 606us total 56.204ms
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1714): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1409): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1409): run()
,I/Decoder ( 1409): createOrResetDecoder
,I/ActivityManager(  881): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7860 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     ( 1555): Explicit concurrent mark sweep GC freed 7717(551KB) AllocSpace objects, 4(184KB) LOS objects, 25% free, 13MB/17MB, paused 507us total 134.777ms
,I/art     (  881): Explicit concurrent mark sweep GC freed 14009(917KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 11.436ms total 183.515ms
,I/art     (  881): WaitForGcToComplete blocked for 57.235ms for cause Explicit
,I/art     ( 1939): Explicit concurrent mark sweep GC freed 6761(415KB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 15MB/21MB, paused 1.122ms total 184.137ms
,I/ConfigService( 1714): onCreate
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): run()
,D/VoicemailCleanupService( 7860): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7884 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ContactLocale( 7860): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = contacts
,D/TaskPersister(  881): removeObsoleteFile: deleting file=3_task.xml
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1409): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1409): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1409): run()
I/StatsUtilsManager( 1409): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1409): shouldRecordStats() = Too Soon
,I/ActivityManager(  881): Killing 7586:com.motorola.context/u0a8 (adj 15): empty #7
,W/asset   ( 7884): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 7884): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7884): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7884): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/art     (  881): Explicit concurrent mark sweep GC freed 4293(227KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 3.483ms total 204.247ms
,D/AndroidRuntime( 7825): Shutting down VM
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_7586/cgroup.procs: No such file or directory
,I/Launcher( 1555): Deferring update until onResume
,I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7906 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7666:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10005/pid_7666/cgroup.procs: No such file or directory
,W/ContextImpl( 7906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,I/ActivityManager(  881): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7928 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1714): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1714): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7948 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/GservicesProvider( 7928): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7928): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7928): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7928): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 7928): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 7928): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 7928): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 7928): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7928): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7928): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 7928): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7928): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1686)
E/SQLiteDatabase( 7928): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1655)
E/SQLiteDatabase( 7928): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5051)
E/SQLiteDatabase( 7928): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4646)
E/SQLiteDatabase( 7928): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4586)
E/SQLiteDatabase( 7928): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7928): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1353)
E/SQLiteDatabase( 7928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7928): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7928): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/SQLiteDatabase( 7928): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7928): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7928): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/SQLiteDatabase( 7928): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,D/AndroidRuntime( 7928): Shutting down VM
,--------- beginning of crash
E/AndroidRuntime( 7928): FATAL EXCEPTION: main
E/AndroidRuntime( 7928): Process: com.google.process.gapps, PID: 7928
E/AndroidRuntime( 7928): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7928): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5054)
E/AndroidRuntime( 7928): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4646)
E/AndroidRuntime( 7928): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4586)
E/AndroidRuntime( 7928): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 7928): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1353)
E/AndroidRuntime( 7928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7928): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7928): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 7928): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7928): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7928): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 7928): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 7928): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 7928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 7928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7928): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 7928): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 7928): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 7928): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 7928): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7928): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7928): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 7928): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7928): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1686)
E/AndroidRuntime( 7928): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1655)
E/AndroidRuntime( 7928): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5051)
E/AndroidRuntime( 7928): 	... 11 more
,I/Process ( 7928): Sending signal. PID: 7928 SIG: 9
E/DropBoxManagerService(  881): Can't write: system_app_crash
E/DropBoxManagerService(  881): java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  881): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  881): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  881): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  881): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  881): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  881): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  881): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  881): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  881): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  881): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  881): 	... 5 more
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,I/ActivityManager(  881): Process com.google.process.gapps (pid 7928) has died

```
