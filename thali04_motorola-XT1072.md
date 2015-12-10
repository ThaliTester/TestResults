#### Test 50650278c0f6ec2_thali04_motorola-XT1072 Logs


```
--------- beginning of main,
I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
D/AndroidRuntime( 5196): 
D/AndroidRuntime( 5196): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5196): CheckJNI is OFF
D/AndroidRuntime( 5196): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5215 uid=10375 gids={50375, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5196): Shutting down VM
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5215): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5215): Time to load native libraries: 4 ms (timestamps 7436-7440)
I/LibraryLoader( 5215): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5215): Binding Chromium to main looper Looper (main, tid 1) {22675df4}
I/LibraryLoader( 5215): Expected native library version number "",actual native library version number ""
I/chromium( 5215): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5215): Initializing chromium process, singleProcess=true
W/art     ( 5215): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5215): ApplicationContext is null in ApplicationStatus
W/chromium( 5215): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5215): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5215): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5215): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5215): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5215): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5215): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5215): Local Branch: 
I/Adreno-EGL( 5215): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5215): Local Patches: NONE
I/Adreno-EGL( 5215): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bdbc86:true
W/ActivityManager(  880): Activity pause timeout for ActivityRecord{2b4ba6f3 u0 com.test.thalitest/.MainActivity t3}
D/BluetoothAdapter( 5215): 497833151: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5215): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5215): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5215): CordovaWebView is running on device made by: motorola
W/art     ( 5215): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5215): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5215): Render dirty regions requested: true
D/Atlas   ( 5215): Validating map...
W/chromium( 5215): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 5215): Initialized EGL, version 1.4
D/OpenGLRenderer( 5215): Enabling debug mode 0
I/Keyboard.Facilitator( 1406): onFinishInput()
I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,1058
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +985ms (total +1s58ms)
W/IInputConnectionWrapper( 5215): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5215): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 5215): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5215): Cannot call determinedVisibility() - never saw a connection for the pid: 5215
,D/JsMessageQueue( 5215): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5215): JniHelper::setJavaVM(0xb84a9310), pthread_self() = -1199344448
,D/JX-Cordova( 5215): jxcore cordova android initializing
,I/art     ( 5215): Background partial concurrent mark sweep GC freed 13870(813KB) AllocSpace objects, 3(3MB) LOS objects, 39% free, 15MB/25MB, paused 5.941ms total 52.216ms
,W/jxcore-log( 5215): Initializing JXcore engine
W/jxcore-log( 5215): JXcore engine is ready
,W/jxcore-log( 5215): Starting JXcore engine
,W/.test.thalitest( 5215): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10375 path="socket:[8382]" dev="sockfs" ino=8382 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5215): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10375 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5215): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10375 path="socket:[6844]" dev="sockfs" ino=6844 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5215): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10375 path="socket:[23206]" dev="sockfs" ino=23206 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5215): Platform android
W/jxcore-log( 5215): 
W/jxcore-log( 5215): Process ARCH arm
W/jxcore-log( 5215): 
,I/jxcore-log( 5215): JXcore Cordova bridge is ready!
I/jxcore-log( 5215): 
,W/jxcore-log( 5215): JXcore engine is started
,I/chromium( 5215): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5215): Toggling radios to true
I/jxcore-log( 5215): 
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  880): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  880): Message: 1
D/BluetoothManagerService(  880): MESSAGE_ENABLE: mBluetooth = null
,W/Settings( 1465): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: true pid=5215, uid=10375
,E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine(  880): setting operational mode to 1
,I/jxcore-log( 5215): Radios toggled
I/jxcore-log( 5215): 
,I/ActivityManager(  880): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5266 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1465): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/ResourcesManager( 5266): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 5266): Adding HeadsetService
D/AdapterServiceConfig( 5266): Adding A2dpService
D/AdapterServiceConfig( 5266): Adding HidService
D/AdapterServiceConfig( 5266): Adding HealthService
D/AdapterServiceConfig( 5266): Adding PanService
D/AdapterServiceConfig( 5266): Adding GattService
D/AdapterServiceConfig( 5266): Adding BluetoothMapService
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13d0d33c:true
,D/BluetoothAdapterState( 5266): make
,I/bluedroid( 5266): init
I/BluetoothAdapterState( 5266): Entering OffState
,I/bte_conf( 5266): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5266): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5266): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5266): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 5266): get_profile_interface socket
I/bluedroid( 5266): get_profile_interface map_client
,I/GKI_LINUX( 5266): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothManagerService(  880): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  880): Message: 40
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 5266): Address is:44:80:EB:7B:5A:05
D/BluetoothAdapterProperties( 5266): Name is: XT1072
D/BluetoothManagerService(  880): Bluetooth Adapter name changed to XT1072
D/BluetoothManagerService(  880): Stored Bluetooth name: XT1072
I/bluedroid( 5266): config_hci_snoop_log
,D/BluetoothManagerService(  880): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  880): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 5266): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 5266): Setting state to 11
I/BluetoothAdapterState( 5266): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  880): Message: 60
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  880): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 5266): make
,I/BluetoothBondStateMachine( 5266): StableState(): Entering Off State
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/ActivityManager(  880): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5307 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  880): ApnList is empty for checkDunConfigured()
,D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
,D/Tethering(  880):  7
D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
,D/TCMD    (  478): NL - Read 1008 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 1008 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
,D/Tethering(  880): InitialState.processMessage what=4
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/QsoftapCmd(  291): Got softap fwreload command we are passing on
E/Tethering(  880): ApnList is empty for checkDunConfigured()
,D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
,D/Tethering(  880):  7
,D/SoftapController(  291): Softap fwReload - Ok
,D/BluetoothHeadset(  880): Proxy object connected
D/BluetoothHeadset( 1505): Proxy object connected
,D/HeadsetService( 5266): Received start request. Starting profile...
D/BluetoothHeadset( 1540): Proxy object connected
,I/BluetoothHeadsetServiceJni( 5266): classInitNative: succeeds
,D/HeadsetStateMachine( 5266): make
,I/BluetoothAdapterState( 5266): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothHeadset( 1505): Proxy object connected
D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
,D/HeadsetStateMachine( 5266): max_hf_connections = 1
I/bluedroid( 5266): get_profile_interface handsfree
,D/HeadsetStateMachine( 5266): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
,D/BluetoothA2dp(  880): Proxy object connected
,D/A2dpService( 5266): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 5266): classInitNative: succeeds
I/bluedroid( 5266): get_profile_interface avrcp
,D/CommandListener(  291): Setting iface cfg
,D/CommandListener(  291): Trying to bring down wlan0
,D/CommandListener(  291): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  880): setWifiState: enabling
,E/RemoteController( 5266): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 5266): classInitNative: succeeds
D/A2dpStateMachine( 5266): make
,I/bluedroid( 5266): get_profile_interface a2dp
I/GKI_LINUX( 5266): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
D/A2dpStateMachine( 5266): Enter Disconnected: -2
I/BluetoothHidServiceJni( 5266): classInitNative: succeeds
,E/WifiStateMachine(  880): Supplicant start successful
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,D/WifiMonitor(  880): startMonitoring(wlan0) with mConnected = false
,D/HidService( 5266): Received start request. Starting profile...
I/bluedroid( 5266): get_profile_interface hidhost
D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
,I/BluetoothHealthServiceJni( 5266): classInitNative: succeeds
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/ResourcesManager( 5307): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
D/HealthService( 5266): Received start request. Starting profile...
,I/bluedroid( 5266): get_profile_interface health
D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
,I/BluetoothPanServiceJni( 5266): classInitNative(L105): succeeds
,D/PanService( 5266): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 5266): initializeNative(L110): pan
I/bluedroid( 5266): get_profile_interface pan
,D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
,I/BtGatt.JNI( 5266): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 5266): handleDebugAction() action=null
D/BtGatt.GattService( 5266): Received start request. Starting profile...
D/BtGatt.GattService( 5266): start()
I/bluedroid( 5266): get_profile_interface gatt
D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
D/BtGatt.AdvertiseManager( 5266): advertise manager created
,I/wpa_supplicant( 5328): Successfully initialized wpa_supplicant
E/wpa_supplicant( 5328): Line 13: unknown global field 'a'.
E/wpa_supplicant( 5328): Line 13: Invalid configuration line 'a'.
D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
I/wpa_supplicant( 5328): rfkill: Cannot open RFKILL control device
,D/TCMD    (  478): NL - Read 1004 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
,D/TCMD    (  478): NL - Read 1004 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
,D/BluetoothMapService( 5266): Received start request. Starting profile...
D/BluetoothMapService( 5266): start()
,D/BluetoothMapEmailSettingsLoader( 5266): Found 0 applications
,D/BluetoothMapEmailAppObserver( 5266): createReceiver()
,D/BluetoothMapEmailAppObserver( 5266): initObservers()
,D/BluetoothMapEmailAppObserver( 5266): getEnabledAccountItems()
,D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
D/HeadsetStateMachine( 5266): Proxy object connected
,D/HeadsetStateMachine( 5266): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 5266): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5266): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 5266): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5266): enable
,I/GKI_LINUX( 5266): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 5266): init
,I/bt-btu  ( 5266): btu_task pending for preload complete event
,I/bt_vendor( 5266): bt-vendor : init
,D/bt_userial_mct( 5266): userial_init
I/bt_hwcfg( 5266): Starting hciattach daemon
I/bt_hwcfg( 5266): try to set false
,I/bt_hwcfg( 5266): Starting hciattach daemon
I/bt_hwcfg( 5266): try to set true
,I/qcom-bluetooth( 5342): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/libmdmdetect( 5328): ESOC framework not supported
E/Diag_Lib( 5328):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 5328): baseband property is set to [msm]
I/libmdmdetect( 5328): ESOC framework not supported
,I/ActivityManager(  880): Killing 4920:android.process.acore/u0a7 (adj 15): empty #7
,E/wpa_supplicant( 5328):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5328): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5328): card_info[i].card_state: 0x0
E/wpa_supplicant( 5328): card_info[i].error_code: 0x0
E/wpa_supplicant( 5328): SIM/USIM not ready
E/wpa_supplicant( 5328): Error while reading SIM card status
,E/wpa_supplicant( 5328): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5328): card_info[i].card_state: 0x0
E/wpa_supplicant( 5328): card_info[i].error_code: 0x0
E/wpa_supplicant( 5328): SIM/USIM not ready
I/wpa_supplicant( 5328): eap_proxy: Card not ready
,I/qcom-bluetooth( 5350): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 5351): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 5353): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5354): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 5355): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_4920/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 1738): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/wpa_supplicant( 5328): Line 31: unknown global field 'a'.
E/wpa_supplicant( 5328): Line 31: Invalid configuration line 'a'.
I/wpa_supplicant( 5328): rfkill: Cannot open RFKILL control device
,D/TCMD    (  478): NL - Read 1004 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
,E/wpa_supplicant( 5328): baseband property is set to [msm]
I/libmdmdetect( 5328): ESOC framework not supported
,E/wpa_supplicant( 5328):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5328): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5328): card_info[i].card_state: 0x0
E/wpa_supplicant( 5328): card_info[i].error_code: 0x0
E/wpa_supplicant( 5328): SIM/USIM not ready
E/wpa_supplicant( 5328): Error while reading SIM card status
,E/wpa_supplicant( 5328): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5328): card_info[i].card_state: 0x0
E/wpa_supplicant( 5328): card_info[i].error_code: 0x0
E/wpa_supplicant( 5328): SIM/USIM not ready
I/wpa_supplicant( 5328): eap_proxy: Card not ready
I/wpa_supplicant( 5328): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,E/WifiStateMachine(  880): setSuspendOptimizations: 2 true
E/WifiStateMachine(  880): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  880): Supplicant connection established
,E/WifiStateMachine(  880): setWifiState: enabled
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiConfigStore(  880): Loading config and enabling all networks 
,E/WifiConfigStore(  880):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  880):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  880): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  880): Setting external_sim to 1
,D/WifiStateMachine(  880): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2d9889c
D/wifi    (  880): halHandle = 0x0, mVM = 0xb84a9310, mCls = 0x201472
I/WifiNative-HAL(  880): Could not start hal
,E/WifiStateMachine(  880): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 5328): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/wpa_supplicant( 5328): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5328): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=5361 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,E/native  (  880): do suspend true
,D/WifiP2pService(  880): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  880): SCAN_AVAILABLE : 3
D/RttService(  880): SCAN_AVAILABLE : 3
,D/RttService(  880): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  291): Setting iface cfg
D/CommandListener(  291): Trying to bring up p2p0
D/WifiScanningService(  880): DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa48b09cc
D/wifi    (  880): halHandle = 0x0, mVM = 0xb84a9310, mCls = 0x146e
,I/WifiNative-HAL(  880): Could not start hal
E/WifiScanningService(  880): could not start HAL
D/WifiMonitor(  880): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  880): P2pEnablingState
D/WifiP2pService(  880): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2p socket connection successful
D/WifiP2pService(  880): P2pEnabledState
D/WifiP2pService(  880): sending p2p connection changed broadcast
,D/WifiNative-HAL(  880): p2pGetDeviceAddress
,D/WifiNative-HAL(  880): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
E/WifiStateMachine(  880): set country code US
D/WifiP2pService(  880): DeviceAddress: 44:80:eb:7b:5a:07
,E/WifiStateMachine(  880): set frequency band 2
,D/WifiP2pService(  880): MCC mode enabled 0
,I/wpa_supplicant( 5328): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 5328): wlan0: Failed to initiate AP scan
,D/WifiP2pService(  880): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  880): sending p2p persistent groups changed broadcast
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/WifiP2pService(  880): InactiveState
D/WifiP2pService(  880): InactiveState{ when=-8ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-8ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiP2pService(  880): InactiveState{ when=-13ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-13ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info0x
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/SharedPreferencesImpl(  880): Couldn't create directory for SharedPreferences file shared_prefs/android_preferences.xml
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/ResourcesManager( 5361): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/ActivityManager(  880): Killing 5062:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/MDMCTBK (  293): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  293): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): wifi_connect_to_supplicant, current pid is = 293
,D/MDMCTBK (  293): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  293): wifi_close_sockets: Exit
,E/MDMCTBK (  293): Attach monitor thread
I/MDMCTBK (  293): createWifiMonitorThread: Started the wifi monitor thread -1195487432
D/MDMCTBK (  293): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_5062/cgroup.procs: No such file or directory
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  478): NL - Read 1004 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
,D/MDMCTBK (  293): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
,D/TCMD    (  478): NL - Read 56 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  293): Event received = WPS-AP-AVAILABLE 
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2d988fc
,D/wifi    (  880): halHandle = 0x0, mVM = 0xb84a9310, mCls = 0x201906
I/WifiNative-HAL(  880): Could not start hal
E/WifiStateMachine(  880): [1,449,748,713,042 ms] noteScanEnd no scan source
E/WifiStateMachine(  880): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@fef8168 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  880): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  880):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  880): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  880): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,I/qcom-bluetooth( 5389): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 44:80:eb:7b:5a:05 
,E/WifiConfigStore(  880): will read network variables netId=0
,E/WifiStateMachine(  880): CMD_AUTO_CONNECT did save config ->  nid=0
E/WifiConfigStore(  880): will read network variables netId=0
,I/qcom-bluetooth( 5390): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/wpa_supplicant( 5328): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  293): Event received = Trying to associate with
D/WifiMonitor(  880): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
E/wpa_supplicant( 5328): DSDS: eapol_sm_notify_config config->sim_num = 1
E/WifiConfigStore(  880): setLastSelectedConfiguration -1
E/wpa_supplicant( 5328): PNO: In assoc process
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/bt_hwcfg( 5266): bluetooth satus is on
,D/bt_userial_mct( 5266): userial_open(port:0)
I/bt_userial_vendor( 5266): Done intiailizing UART
,I/bt_userial_vendor( 5266): Done intiailizing UART
I/bt_userial_mct( 5266): CMD=53, EVT=53, ACL_Out=54, ACL_In=54
,I/bt_vendor( 5266): Bluetooth Firmware and smd is initialized
I/bt-btu  ( 5266): btu_task received preload complete event
D/bt_userial_mct( 5266): Entering userial_read_thread()
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledStateupdate channel list
I/        ( 5266): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 5266): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5266): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5266): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5266): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5266): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5266): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5266): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5266): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5266): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5266): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5266): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5266): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5266): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5266): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 5266): BTM_SecRegister:p_cb_info->p_le_callback == 0xa6d58d85 
E/bt-btm  ( 5266): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa6d58d85 
,E/bt-btif ( 5266): Calling BTA_HhEnable
,E/bt-btif ( 5266): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 5266): Address is:44:80:EB:7B:5A:05
D/BluetoothManagerService(  880): Bluetooth Adapter name changed to XT1072
,D/BluetoothAdapterProperties( 5266): Name is: XT1072
D/BluetoothManagerService(  880): Stored Bluetooth name: XT1072
D/BluetoothAdapterProperties( 5266): Scan Mode:20
D/BluetoothAdapterProperties( 5266): Discoverable Timeout:120
D/BluetoothAdapterProperties( 5266): Adding bonded device:7C:F9:0E:37:96:AB
D/BluetoothAdapterProperties( 5266): Adding bonded device:58:2A:F7:ED:96:BE
E/BluetoothRemoteDevices( 5266): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:37:96:AB, value is empty for type: 10
,E/BluetoothRemoteDevices( 5266): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/bte_conf( 5266): Device ID record 1 : primary
D/bte_conf( 5266):   vendorId            = 000f
,D/bte_conf( 5266):   vendorIdSource      = 0001
D/bte_conf( 5266):   product             = 1200
E/bt_mct  ( 5266): hci lib postload completed
D/bte_conf( 5266):   version             = 1436
D/bte_conf( 5266):   clientExecutableURL = 
D/bte_conf( 5266):   serviceDescription  = 
D/bte_conf( 5266):   documentationURL    = 
D/bte_conf( 5266): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 5266): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5266): ScanMode =  20
D/BluetoothPanServiceJni( 5266): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 5266): State =  11
D/BluetoothAdapterProperties( 5266): Setting state to 12
I/BluetoothAdapterState( 5266): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  880): Message: 60
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  880): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothA2dp(  880): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 5266): Scan Mode:21
D/BluetoothAdapterProperties( 5266): Discoverable Timeout:120
,I/BluetoothAdapterState( 5266): Entering On State
D/BluetoothHeadset( 1505): onBluetoothStateChange: up=true
D/BluetoothHeadset(  880): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1540): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1505): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  880): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothMapService( 5266): onReceive
D/BluetoothMapService( 5266): STATE_ON
D/BluetoothMapMasInstance( 5266): Map Service startRfcommSocketListener
,D/BluetoothManagerService(  880): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  880): Message: 40
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapMasInstance( 5266): MAS initSocket()
,I/Telecom ( 1505): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5266): getBluetoothService() called with no BluetoothManagerCallback
D/TCMD    (  478): NL - Read 312 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 192 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 1004 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/BluetoothMapMasInstance( 5266): Accepting socket connection...
D/HeadsetStateMachine( 5266): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 5266): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 5266): mNumber:  mType: 128
D/HeadsetStateMachine( 5266): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 5266): terminateScoUsingVirtualVoiceCall:No present call to terminate
D/TCMD    (  478): NL - Read 80 bytes from update socket.
,D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 80 bytes from update socket.
,D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
I/wpa_supplicant( 5328): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  293): Event received = Associated with c0:ff:d4
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
,D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ContextImpl( 5307): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  880): Message: 20
,D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b7c7291:true
,D/LocalBluetoothProfileManager( 5307): Adding local A2DP profile
,D/BluetoothManagerService(  880): Message: 30
,D/LocalBluetoothProfileManager( 5307): Adding local HEADSET profile
D/BluetoothManagerService(  880): Message: 30
D/AuthorizationBluetoothService( 1738): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5266): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  880): Message: 30
,D/BluetoothManagerService(  880): Message: 30
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5266): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 5266): Accept thread started.
,D/LocalBluetoothProfileManager( 5307): Adding local MAP profile
,I/MDMCTBK (  293): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  293): NetlinkHandler, interfaceAdded
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
E/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  293): , Wifi = 0
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
,I/MDMCTBK (  293): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
D/BluetoothMap( 5307): Create BluetoothMap proxy object
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
,D/BluetoothManagerService(  880): Message: 30
,I/MDMCTBK (  293): send SAR ctrl over QMI
,D/BluetoothManagerService(  880): Message: 30
,D/LocalBluetoothProfileManager( 5307): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 5307): finishStartingService: stopping service
,D/BluetoothA2dp( 5307): Proxy object connected
,D/A2dpProfile( 5307): Bluetooth service connected
,D/BluetoothHeadset( 5307): Proxy object connected
,D/HeadsetProfile( 5307): Bluetooth service connected
,D/BluetoothInputDevice( 5307): Proxy object connected
,D/HidProfile( 5307): Bluetooth service connected
,D/BluetoothPan( 5307): BluetoothPAN Proxy object connected
,D/PanProfile( 5307): Bluetooth service connected
,D/BluetoothMap( 5307): Proxy object connected
D/MapProfile( 5307): Bluetooth service connected
,D/BluetoothMap( 5307): getConnectedDevices()
,D/BluetoothPbap( 5307): Proxy object connected
,D/PbapServerProfile( 5307): Bluetooth service connected
,E/global frequency( 2536): no tags to log
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/art     ( 2536): Explicit concurrent mark sweep GC freed 20407(1241KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 10MB/18MB, paused 1.200ms total 58.207ms
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  880): Explicit concurrent mark sweep GC freed 33236(1765KB) AllocSpace objects, 3(205KB) LOS objects, 33% free, 20MB/30MB, paused 1.521ms total 127.670ms
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 53574(2MB) AllocSpace objects, 32(1019KB) LOS objects, 39% free, 7MB/12MB, paused 946us total 46.073ms
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 4222(175KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 749us total 27.161ms
,D/BSUtils ( 2536): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2536): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2536): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2536): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2536): BcsDSCheckin.events found events 162
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2536): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2536): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2536): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2536): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2536): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2536): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 2536): unknown error code mapping for: 0
I/global frequency( 2536): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2536): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2536): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager(  880): send {7e28d71, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  880): done {7e28d71, *walarm*:com.google.android.intent.action.SEND_IDLE} [3ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 5328): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5328): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  293): Event received = WPA: Key negotiation com
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293):  STA Connected !!
D/TCMD    (  478): NL - Read 1004 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
,E/MDMCTBK (  293): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  293): get_freq !!, resp=2412
I/MDMCTBK (  293): get_freq !!, Strip data
I/MDMCTBK (  293): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=0,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, Wifi Band changed, call setWifiCutback.
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 1, data=0
I/MDMCTBK (  293): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  293): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1195471560
I/MDMCTBK (  293): return from set_get_from_wpa_supplicant
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  293): wifi_set_tx_pwr: SETTXPOWER = 18
,E/MDMCTBK (  293): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  293): , reply_len: 3, ret: 0
E/MDMCTBK (  293): MdmCutbackHndler, resp=OK
E/MDMCTBK (  293): 
D/MDMCTBK (  293): wifi_set_tx_pwr: Exit
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  880): Network connection established
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  880): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  880): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  880): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine(  880): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  291): Setting iface cfg
,E/WifiStateMachine(  880): Start Dhcp Watchdog 1
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend false
,E/wpa_supplicant( 5328): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
E/wpa_supplicant( 5328): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d0ade60 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1d0ade60 target=com.android.internal.util.StateMachine$SmHandler }
,E/DHCPCD  ( 5446): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5446): version 5.5.6 starting
,E/DHCPCD  ( 5446): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 5446): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 5446): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 5446): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 5446): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 5446): wlan0: sending REQUEST (xid 0xd91b7ab2), next in 3.18 seconds
,I/DHCPCD  ( 5446): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 5446): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 5446): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 5446): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 5446): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5446): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5446): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/TCMD    (  478): NL - Read 60 bytes from update socket.
D/TCMD    (  478): NL - ignore NL message, type = 20
D/TCMD    (  478): Listening for incoming client connection request
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  880): WifiStateMachine DHCP successful
E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  880): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  880): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  880): Adding iface wlan0 to network 100
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  880): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  880): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService(  880): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  880): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  880): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  880): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  880):    accepting network in place of null
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  880): Setting tx/rx TCP buffers to 131072,262144,3145728,4096,221184,3145728
,D/CSLegacyTypeTracker(  880): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  880): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
I/ModemStatsDSDetect( 1523): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
I/ModemStatsDSDetect( 1523): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine(  880): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/ModemStatsDSDetect( 1523): onReceive() - done, currentInetCondition=0
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityManager.CallbackHandler( 1931): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 11:58:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449748718653], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449748718636]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Validated
,D/ConnectivityService(  880): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  880): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1523): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1523): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1523): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1523): onReceive() - done, currentInetCondition=100
D/ConnectivityManager.CallbackHandler( 1931): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/MDMCTBK (  293): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  293): NetlinkHandler, interfaceAdded
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
E/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  293): , Wifi = 1
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  293): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  293): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1195471560
I/MDMCTBK (  293): return from set_get_from_wpa_supplicant
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,D/MDMCTBK (  293): wifi_set_tx_pwr: SETTXPOWER = 18,
,E/MDMCTBK (  293): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK,
E/MDMCTBK (  293): , reply_len: 3, ret: 0
E/MDMCTBK (  293): MdmCutbackHndler, resp=OK
E/MDMCTBK (  293): 
D/MDMCTBK (  293): wifi_set_tx_pwr: Exit
I/MDMCTBK (  293): send SAR ctrl over QMI
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2536): now: 201804 ,futureTime: 9223372036854775807
D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2536): now: 201805 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5512 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PollingManager( 2536): now: 201860 ,futureTime: 9223372036854775807
,D/AlarmManagerService(  880): Setting time of day to sec=1449748721
,W/AlarmManagerService(  880): Unable to set rtc to 1449748721: Invalid argument
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
V/AlarmManager(  880): send {18a0005f, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,D/OtaApp  ( 2536): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1465): now: 201908 ,futureTime: 86473999
D/Central_PollingManager( 1465): Polling alarm set to expire at: 86473999 Current Time: 201908
,D/OtaApp  ( 2536): [debug] > PollingManagerService, now: 201914 ,futureTime: 9225281
D/OtaApp  ( 2536): [debug] > Polling alarm set to expire at: 9225281 Current Time: 201914
,D/MMApiProvisionService( 2536): isDeviceProvisioned: deviceId = 2072049230914535424
,I/art     (  880): Explicit concurrent mark sweep GC freed 23265(1227KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.752ms total 142.967ms
,D/CCE     ( 2536): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2536): createDeviceIdOrLogin update_device
D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2536): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2536): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2536): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,E/GpsLocationProvider(  880): No APN found to select.
,D/GpsLocationProvider(  880): NTP server returned: 1449748718476 (Thu Dec 10 12:58:38 GMT+01:00 2015) reference: 198858 certainty: 10 system time offset: -3287
,E/LocSvc_ApiV02(  880): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,E/ActivityThread( 1931): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  880): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 234321, reason: UserStart
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=298, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311766, SEQNUM=4429, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10316, POWER_SUPPLY_CHARGE_COUNTER=-675, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/art     ( 2536): Explicit concurrent mark sweep GC freed 14769(961KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 11MB/18MB, paused 1.312ms total 84.873ms
,D/MMApiProvisionService( 2536): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2536): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2536): createDeviceIdOrLogin update_device
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,D/HeadsetStateMachine( 5266): Disconnected process message: 10, size: 0
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1931): CM callback handler got msg 524295
,D/MMApiWebService( 2536): generating token using payload instead of using session token
,I/MusicStore( 5512): Database version: 120
,D/MMApiProvisionService( 2536): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2536): isRequestAllowed(): already have outstanding request ... ignoring request
,D/ Nonce  ( 2536):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/MMApiWebService( 2536): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2536): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 3494(145KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 933us total 28.857ms
,I/MMApiWSBase( 2536): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2536): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2536): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2536): createDeviceIdOrLogin update_device
D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2536): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2536): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2536): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2536): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
D/OtaApp  ( 2536): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2536): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
W/ContextImpl( 5512): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/Checkin ( 2536): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2536): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2536): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2536): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2536): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 2536): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,E/Auth.Api.Credentials( 1931): [CredentialSyncAdapter] Unknown sync event.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5512): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5512): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/VacuumService( 1738): Vacuum at: now=1449748722234 tag=VacuumService
,W/ResourcesManager( 5512): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5512): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5512): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5512): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5512): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@904a350: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5512): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 5512): GMSCore installation verified
,I/ConfigStore( 5512): Config Database version: 1
,I/MediaRouter( 5512): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5512): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5512): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5512): type=WIFI subType= reason=null isConnected=true
,I/MMApiBackOffService( 2536): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5576 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/MMApiWebService( 2536): MMApiBackOffService told us it's okay to retry the waiting requests: 0
,I/GHttpClientFactory( 5512): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5512): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=5595 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5595): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 5215): Test app app.js loaded
I/jxcore-log( 5215): 
I/ActivityManager(  880): Killing 5003:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/chromium( 5215): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/art     (  880): Explicit concurrent mark sweep GC freed 23739(1023KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.512ms total 134.353ms
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_5003/cgroup.procs: No such file or directory
,D/MMApiWSBase( 2536): doRequest(): v1/gns/list/messages resp length: 1363
V/Mms     ( 5576): mnc/mcc: 
V/Mms     ( 5576): tag: int value: recipientLimit - 20
V/Mms     ( 5576): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 5576): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 5576): tag: int value: maxSubjectLength - 80
V/Mms     ( 5576): tag: bool value: smsForceShowEncodingMenu - true
D/CCE     ( 2536): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
V/Mms     ( 5576): tag: bool value: enableGroupMms - false
V/Mms     ( 5576):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/CCE     ( 2536): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ Nonce  ( 2536):  Nonce Reponse 
D/        ( 2536): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"847f817e-8f5f-4669-be13-1306264ae7d0"}
D/MMApiWSBase( 2536): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2536):  Nonce Handle Reponse 
,D/MMApiProvisionService( 2536): mOutstandingReq set to false
,D/Checkin ( 2536): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 2536): handleGetNotificationsResponse(): got 0; more=false
,W/ResourcesManager( 5576): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5625 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.604ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 19.589ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 20.735ms
,D/MMApiProvisionService( 2536):  pTime 1449671329422 sExp 172742 cTime 1449748723324 tTime 1449844071422
D/MMApiProvisionService( 2536):  No login Required 
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5644 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/PhenotypeConfigurator( 1738): Scheduling Phenotype for one-off execution 11015 seconds from now (1449748723416)
,D/GetConfigurationSnapshotOperation( 1738): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/art     ( 1540): Explicit concurrent mark sweep GC freed 29993(1925KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.048ms total 71.717ms
,I/ActivityManager(  880): Killing 5087:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 5625): Register our PhoneStateListener
,I/ContactLocale( 5644): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_5087/cgroup.procs: No such file or directory
,W/DataUsage( 2536): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,D/MobileConnectivityChangeReceiver( 5625): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5625): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 5307:com.android.settings/1000 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_1000/pid_5307/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 5361:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_5361/cgroup.procs: No such file or directory
,I/CheckinService( 1931): Checkin interval check for package: unspecified last checkin: 1449746339566 min interval config: 0 actual interval: 2384213
,I/CheckinService( 1931): Checking schedule, now: 1449748723798 next: 1449746369536
I/CheckinService( 1931): active receiver: enabled
,I/iu.SyncManager( 1931): SYNC; picasa accounts
,D/NetworkLogImpl( 1931): Loaded NetworkSpeedPredictor
,I/PhenotypeFlagCommitter( 1738): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1738): Using platform SSLCertificateSocketFactory
,I/iu.Environment( 1931): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/CheckinService( 1931): Preparing to send checkin request
,I/EventLogService( 1931): Accumulating logs since 1449748194673
,I/iu.UploadsManager( 1931): num queued entries: 0
,I/iu.UploadsManager( 1931): num updated entries: 0
I/iu.SyncManager( 1931): NEXT; no task
,W/DataUsage( 2536): invalid counter update blocked: 'err' by 0
D/Checkin ( 2536): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=5682 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCM     ( 1738): GCM config loaded
,I/CheckinRequestBuilder( 1931): Checkin reason type: 8 attempt count: 1
,D/WifiService(  880): New client listening to asynchronous messages
,E/ActivityThread( 1931): Failed to find provider info for com.google.android.wearable.settings
,W/art     ( 5595): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 5104): Explicit concurrent mark sweep GC freed 1634(74KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 368us total 25.989ms
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5724 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 5724): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5724): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5724): VM with version 2.1.0 has multidex support
I/MultiDex( 5724): install
I/MultiDex( 5724): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5742 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/JNIHelp ( 5724): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 5742): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ActivityThread( 5724): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5724): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a3ee31: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5724): Installed default security provider GmsCore_OpenSSL
,I/art     ( 5724): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5724): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel_SMS( 5742): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5742): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5742): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5742): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5742): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5742): MmsConfig.loadFromResources
,E/Babel_SMS( 5742): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5742): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/art     (  880): Explicit concurrent mark sweep GC freed 12023(538KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.766ms total 123.054ms
,D/NativeLibraryUtils( 5724): Install completed successfully. count=14 extracted=0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f60000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f60000
,W/Settings( 5742): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,I/Babel_Crash( 5742): startup - clean
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb542e960
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb75fc420, dataLength=8
,D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7600c68, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb7730798, idLength=0xbea2a2b0
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=3840472915
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7600c68
D/DrmWidevineDash(  295): message_length=1591, signature=0xb7663e00, signature_length=3198329492
,I/Babel   ( 5742): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5773 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,W/VideoCapabilities( 5742): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5742): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5742): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5742): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5742): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5742): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5742): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5742): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5742): onServiceConnected
W/Babel   ( 5742): Attempted to change video mute state without an active call.
,I/Babel   ( 5742): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 5512:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_5512/cgroup.procs: No such file or directory
,I/dex2oat ( 5797): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5773): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5773): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5773): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5773): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 5773): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5773):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5773):   adb logcat -s GAv4
,W/GAv4    ( 5773): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5773): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5773): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,I/dex2oat ( 5797): dex2oat took 355.516ms (threads: 4)
,I/Adreno-EGL( 5724): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5724): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5724): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5724): Local Branch: 
I/Adreno-EGL( 5724): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5724): Local Patches: NONE
I/Adreno-EGL( 5724): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 5773): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5773): Time to load native libraries: 2 ms (timestamps 6823-6825)
,I/LibraryLoader( 5773): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5773): Binding Chromium to main looper Looper (main, tid 1) {2adbc5a1}
I/LibraryLoader( 5773): Expected native library version number "",actual native library version number ""
I/chromium( 5773): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/Adreno-EGL( 5724): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5724): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5724): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5724): Local Branch: 
I/Adreno-EGL( 5724): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5724): Local Patches: NONE
I/Adreno-EGL( 5724): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/BrowserStartupController( 5773): Initializing chromium process, singleProcess=true
,W/art     ( 5773): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5773): ApplicationContext is null in ApplicationStatus
,W/chromium( 5773): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5773): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5773): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5773): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5773): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5773): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5773): Local Branch: 
I/Adreno-EGL( 5773): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5773): Local Patches: NONE
I/Adreno-EGL( 5773): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 5773): Requires BLUETOOTH permission
,I/NSApplication( 5773): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5846 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 5625:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ActivityManager(  880): Killing 5576:com.android.mms/u0a23 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_5625/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_5576/cgroup.procs: No such file or directory
,I/Adreno-EGL( 5724): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5724): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5724): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5724): Local Branch: 
I/Adreno-EGL( 5724): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5724): Local Patches: NONE
I/Adreno-EGL( 5724): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 5724): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5724): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5724): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5724): Local Branch: 
I/Adreno-EGL( 5724): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5724): Local Patches: NONE
I/Adreno-EGL( 5724): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f60000
,E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f60000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xbea2a4e0
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb7664070, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76e4e70, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb77307d8, idLength=0xb552e730
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=3671444444
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7600c68
D/DrmWidevineDash(  295): message_length=1626, signature=0xb7617940, signature_length=3042109204
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=5877 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
I/ActivityManager(  880): Killing 5644:android.process.acore/u0a7 (adj 15): empty #7
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_5644/cgroup.procs: No such file or directory
,W/ResourcesManager( 5877): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 1931): Classify the device as Phone.
,I/ActivityManager(  880): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=5905 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 5682:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_5682/cgroup.procs: No such file or directory
,E/SQLiteLog( 5905): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/art     ( 1931): Explicit concurrent mark sweep GC freed 24069(1706KB) AllocSpace objects, 31(496KB) LOS objects, 24% free, 14MB/19MB, paused 1.037ms total 112.561ms
,I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5926 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5926): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AnalyticsLogBase( 5905): PlayLogger.onLoggerConnected
,I/ActivityManager(  880): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5946 uid=10096 gids={50096, 9997} abi=armeabi-v7a
I/ActivityManager(  880): Killing 5773:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/CheckinTask( 1931): Sending checkin request (9608 bytes)
,I/ActivityManager(  880): Killing 5742:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_5773/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5926): Created com.android.providers.calendar.CalendarAlarmManager@326f4106(com.android.providers.calendar.CalendarProvider2@2fd2b3c7)
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_5742/cgroup.procs: No such file or directory
,I/System.out( 5946): TimeService: Loaded Library 
D/TimeService( 5946): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449748727959
D/        ( 5946): TimeServiceNative: User Time to be set is 1449748727959
D/QC-time-services( 5946): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5946): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5946): Lib:time_genoff_operation: pargs->ts_val = 1449748727959
D/QC-time-services( 5946): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  318): Daemon: Connection accepted:time_genoff
D/QC-time-services(  318): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449748727959
,D/QC-time-services(  318): Daemon:genoff_opr: Base = 2, val = 1449748727959, operation = 0
D/QC-time-services(  318): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/10/115 11:57:33
D/QC-time-services(  318): Daemon:Value read from RTC seconds = 1449748653000
D/QC-time-services(  318): Daemon:new time 1449748727959 
D/QC-time-services(  318): Daemon: delta 74959 genoff 74959 
D/QC-time-services(  318): Daemon:genoff_persistent_update: Writing genoff = 74959 to memory
D/QC-time-services(  318): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  318): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  318): Updating the TOD offset
D/QC-time-services(  318): Daemon:genoff_persistent_update: Writing genoff = 74959 to memory
,D/QC-time-services(  318): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  318): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  318): Daemon:Update to modem bit set
D/QC-time-services(  318): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 5946): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  318): Daemon: Base = 2, Value being sent to MODEM = 18446743757744826575
,E/QC-time-services(  318): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  318): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1931): Checkin interval check for package: unspecified last checkin: 1449746339566 min interval config: 0 actual interval: 2388416
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=5969 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 23.688ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 20.636ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.812ms
,I/CheckinRequestBuilder( 1931): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1931): Failed to find provider info for com.google.android.wearable.settings
,I/GAv4    ( 5969): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5969):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5969):   adb logcat -s GAv4
,W/GAv4    ( 5969): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5969): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5969): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/CheckinRequestBuilder( 1931): Classify the device as Phone.
,I/CheckinTask( 1931): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1931): Checking schedule, now: 1449748728320 next: 1450349865315
I/CheckinService( 1931): active receiver: disabled
,D/CheckinService( 1931): Recording last checkin time for package unspecified as 1449748728355
,I/ActivityManager(  880): Killing 5595:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  880): Killing 5846:com.android.chrome/u0a52 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_5595/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_5846/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 5877:com.motorola.context/u0a8 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_5877/cgroup.procs: No such file or directory
,V/AlarmManager(  880): done {18a0005f, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [7038ms]
,D/EmailService.MarketingOptInSetter( 2536): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 2536): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,E/SQLiteLog( 2536): (284) automatic index on registration(APP_ID)
,D/WaitableIntentService( 2536): ServiceHandler.handleMessage: mWaitCount=1
,I/PushService( 2536): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2536): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2536): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2536): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2536): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2536): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2536): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2536): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2536): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2536): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2536): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2536): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2536): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2536): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2536): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2536): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1406): onFinishInput()
,W/IInputConnectionWrapper( 5215): showStatusIcon on inactive InputConnection
,I/SundryService( 2536): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 2536): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 2536): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 2536): ServiceHandler.handleMessage: mWaitCount=0
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6001 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/GetNotificationsWS( 2536): unbindWebServices(): un-registering our AIDL callback...
,I/LaunchCheckinHandler(  880): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,273
,W/ResourcesManager( 6001): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5926): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5926): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  880): Killing 5905:com.google.android.calendar/u0a49 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10049/pid_5905/cgroup.procs: No such file or directory
,I/Babel_SMS( 6001): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6001): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6001): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6001): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6001): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6001): MmsConfig.loadFromResources
,E/Babel_SMS( 6001): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6001): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6001): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6001): startup - clean
,I/Babel   ( 6001): deleted: false for 0
,W/art     ( 6001): Suspending all threads took: 14.493ms
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6032 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6001): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6001): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6001): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6001): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6001): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6001): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6001): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6001): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Killing 5946:com.qualcomm.timeservice/u0a96 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10096/pid_5946/cgroup.procs: No such file or directory
,I/vclib   ( 6001): onServiceConnected
W/Babel   ( 6001): Attempted to change video mute state without an active call.
,D/WearableService( 1738): callingUid 10016, callindPid: 1738
,D/LocationInitializer( 1931): Restart initialization of location
,D/AuthorizationBluetoothService( 1738): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1738): [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  880): Explicit concurrent mark sweep GC freed 17886(874KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.371ms total 121.813ms
,I/ActivityManager(  880): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.WidgetDataReceiver: pid=6058 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1738): No location to return for getLastLocation()
,W/FusedLocationProvider( 1738): location=null
,E/SQLiteLog( 6058): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/AnalyticsLogBase( 6058): PlayLogger.onLoggerConnected
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6083 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6083): Register our PhoneStateListener
,V/SetupWizard( 6083): Connected to Gservices successfully
,I/ActivityManager(  880): Killing 5969:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10055/pid_5969/cgroup.procs: No such file or directory
,D/GCM     ( 1738): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6105 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 6105): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
,I/ActivityManager(  880): Killing 6001:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6001/cgroup.procs: No such file or directory
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6130 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,W/ResourcesManager( 1540): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@b0f15a
,I/GCoreNlp( 1738): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1558): Deferring update until onResume
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6182 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6199 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6032:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ActivityManager(  880): Killing 5926:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_6032/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_5926/cgroup.procs: No such file or directory
,W/ResourcesManager( 6199): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Killing 6083:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_6083/cgroup.procs: No such file or directory
,W/ContextImpl( 6058): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 6058): Thread[GAThread,5,main]: No campaign data found.
,I/Babel_SMS( 6199): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6199): MmsConfig.loadMmsSettings
I/Babel_SMS( 6199): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6199): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6199): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6199): MmsConfig.loadFromResources
,E/Babel_SMS( 6199): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6199): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6199): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6199): startup - clean
,I/Babel   ( 6199): deleted: false for 0
,I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6234 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 6199): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6199): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6199): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6199): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6199): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6199): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6257 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6199): Unrecognized profile 2130706433 for video/avc
,I/ContactLocale( 6234): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
W/VideoCapabilities( 6199): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6275 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 20.361ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 18.998ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 22.988ms
,W/ResourcesManager( 6257): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/asset   ( 6275): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6275): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6275): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6275): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6257): Created com.android.providers.calendar.CalendarAlarmManager@326f4106(com.android.providers.calendar.CalendarProvider2@2fd2b3c7)
,D/PackageBroadcastService( 1931): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1931): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 6130): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1558): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@33476ade new=com.google.android.velvet.VelvetApplication@33476ade
,I/vclib   ( 6199): onServiceConnected
,W/Babel   ( 6199): Attempted to change video mute state without an active call.
,W/ResourcesManager( 6199): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6199): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6305 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 1931): updateResources: need to parse f{com.google.android.gms}
,V/JNIHelp ( 6199): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 6305): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Killing 6105:com.motorola.context/u0a8 (adj 15): empty #7
,I/UpdateIcingCorporaServi( 6130): UpdateCorporaTask done [took 197 ms] updated apps [took 196 ms] 
,W/System  ( 6199): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6199): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_6105/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 6058:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10049/pid_6058/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6335 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  880): Explicit concurrent mark sweep GC freed 18075(956KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.347ms total 119.319ms
,I/ActivityManager(  880): Killing 5724:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_5724/cgroup.procs: No such file or directory
,D/Finsky  ( 6335): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6335): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6335): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6335): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 6335): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Ads     ( 6335): Skipping gmscore version check
,D/Finsky  ( 6335): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  880): Killing 6182:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/CalendarProvider2( 6257): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6257): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Finsky  ( 6335): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6383 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_6182/cgroup.procs: No such file or directory
,D/Finsky  ( 6335): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Killing 6275:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/ResourcesManager( 6383): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_6275/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=6402 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6257:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_6257/cgroup.procs: No such file or directory
,E/SQLiteLog( 6402): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6422 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6422): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AnalyticsLogBase( 6402): PlayLogger.onLoggerConnected
,I/CalendarProvider2( 6422): Created com.android.providers.calendar.CalendarAlarmManager@326f4106(com.android.providers.calendar.CalendarProvider2@2fd2b3c7)
,I/Icing   ( 1931): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1931): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 6130:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_6130/cgroup.procs: No such file or directory
,I/CalendarProvider2( 6422): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6422): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  880): Killing 6234:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_6234/cgroup.procs: No such file or directory
,W/SQLiteConnectionPool( 1931): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ActivityManager(  880): Killing 6199:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6199/cgroup.procs: No such file or directory
,W/ContextImpl( 6402): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 6402): Thread[GAThread,5,main]: No campaign data found.
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,I/ActivityManager(  880): Killing 6305:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6305/cgroup.procs: No such file or directory
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  880): send {23c76a01, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {5b729e9, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {5b729e9, *walarm*:android.content.syncmanager.SYNC_ALARM} [8ms]
,V/AlarmManager(  880): done {23c76a01, *alarm*:android.intent.action.TIME_TICK} [47ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=294, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311754, SEQNUM=4464, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-748, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5266): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1738): disconnect managed GoogleApiClient
,V/AlarmManager(  880): send {10f8066e, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  880): done {10f8066e, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [7ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  880): send {5b729e9, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {5b729e9, *walarm*:android.content.syncmanager.SYNC_ALARM} [3ms]
,E/ActivityThread( 1931): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  880): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 326393, reason: UserStart
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311685, SEQNUM=4469, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-768, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5266): Disconnected process message: 10, size: 0
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1406): run()
,I/Keyboard.Facilitator( 1406): flushDynamicLanguageModels()
,I/ConfigService( 1738): onCreate
,E/DataBuffer( 1738): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@25714b9f)
,E/DataBuffer( 1738): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1241d4ec)
E/DataBuffer( 1738): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2f6fc0b5)
E/DataBuffer( 1738): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4a634a)
,I/art     ( 1738): Explicit concurrent mark sweep GC freed 84722(4MB) AllocSpace objects, 32(512KB) LOS objects, 39% free, 14MB/24MB, paused 1.073ms total 112.620ms
,I/ConfigService( 1738): onDestroy
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  880): send {23c76a01, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {9a67546, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6517 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  880): done {23c76a01, *alarm*:android.intent.action.TIME_TICK} [82ms]
,I/GAv4    ( 6517): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6517):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6517):   adb logcat -s GAv4
,W/GAv4    ( 6517): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6517): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6517): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  880): done {9a67546, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [186ms]
,I/ActivityManager(  880): Killing 5104:com.google.process.gapps/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_5104/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  880): send {5b729e9, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {5b729e9, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312127, SEQNUM=4478, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-971, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5266): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5266): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 5215): Toggling radios to false
I/jxcore-log( 5215): 
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  880): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@dbf7307 mBinding = false
,D/BluetoothManagerService(  880): Message: 2
,W/Settings( 1465): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  880): Sending off request.
,D/BluetoothAdapterState( 5266): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 5266): Setting state to 13
I/BluetoothAdapterState( 5266): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 5266): onBluetoothDisable()
I/BluetoothAdapterState( 5266): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 5266): Scan Mode:20
,D/BluetoothAdapterState( 5266): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/BtOppRfcommListener( 5266): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/BluetoothManagerService(  880): Message: 60
,D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  880): Bluetooth State Change Intent: 12 -> 13
,V/BluetoothMapMasInstance( 5266): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 5266): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 5266): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
V/BluetoothMapMasInstance( 5266): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
V/BluetoothMapMasInstance( 5266): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
V/BluetoothMapMasInstance( 5266): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 5266): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 5266): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,W/bt-btif ( 5266): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/btif_config_util( 5266): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 5266): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5266): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothMapService( 5266): onReceive
,D/BluetoothMapService( 5266): STATE_TURNING_OFF
D/BluetoothMapService( 5266): MAP Service closeService in
D/BluetoothMapMasInstance( 5266): MAP Service shutdown
,I/BtOppRfcommListener( 5266): stopping Accept Thread
,I/BtOppRfcommListener( 5266): BluetoothSocket listen thread finished
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiService(  880): setWifiEnabled: false pid=5215, uid=10375
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine(  880): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  880): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
I/jxcore-log( 5215): Radios toggled
I/jxcore-log( 5215): 
,I/ActivityManager(  880): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6579 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
W/Settings( 1465): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  291): Clearing all IP addresses on wlan0
,D/TCMD    (  478): NL - Read 60 bytes from update socket.
D/TCMD    (  478): NL - ignore NL message, type = 21
D/TCMD    (  478): Listening for incoming client connection request
,V/NativeCrypto( 1738): Read error: ssl=0xb88b1978: I/O error during system call, Connection timed out
,V/NativeCrypto( 1738): SSL shutdown failed: ssl=0xb88b1978: I/O error during system call, Broken pipe
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/ConnectivityService(  880): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): ValidatedState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,W/Settings( 1465): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info<unknown ssid>
,D/WifiMetrics(  880): connected time updated 199537
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/wpa_supplicant( 5328): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
E/wpa_supplicant( 5328): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  880): [1,449,748,917,870 ms] noteScanEnd no scan source
D/WifiP2pService(  880): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  880): SCAN_AVAILABLE : 1
D/RttService(  880): SCAN_AVAILABLE : 1
,D/WifiScanningService(  880): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pDisablingState
D/WifiP2pService(  880): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): p2p socket connection lost
D/WifiP2pService(  880): P2pDisabledState
E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/RttService(  880): EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  880): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - enter - invokeEnterMethods
E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  880): do suspend true
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/bt-btif ( 5266): ag scb idx 1 not allocated
E/bt-btif ( 5266): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 5266): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5266): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5266): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5266): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5266): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5266): L2CAP - PSM: 0x0017 not found for deregistration
,I/bt_userial_mct( 5266): exiting userial_read_thread
D/bt_userial_mct( 5266): Leaving userial_evt_read_thread()
D/bt_userial_mct( 5266): userial_close_reader Joined userial reader thread: 0
,I/bt_hwcfg( 5266): hw_epilog_process
D/bt_userial_mct( 5266): userial_close
,W/ResourcesManager( 6579): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/WifiP2pService(  880): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl( 6579): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/AuthorizationBluetoothService( 1738): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3109f7a0:true
,D/BluetoothManagerService(  880): Message: 30
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6607 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/BluetoothManagerService(  880): Message: 30
I/bt_hwcfg( 5266): Starting hciattach daemon
,I/bt_hwcfg( 5266): try to set false
I/bt_vendor( 5266): cleanup
I/GKI_LINUX( 5266): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 5266): GKI_exit_task 0 done
I/GKI_LINUX( 5266): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 5266): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/LocalBluetoothProfileManager( 6579): Adding local MAP profile
D/BluetoothAdapterService( 5266): mProfilesStarted : true supportedProfileServices.length : 7
D/BluetoothMap( 6579): Create BluetoothMap proxy object
,D/BluetoothManagerService(  880): Message: 30
,D/HeadsetService( 5266): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 5266): quit
,D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
D/HeadsetStateMachine( 5266): Exit Disconnected: -1
,D/BluetoothAdapterState( 5266): Stopping profile services that were post enabled
D/BluetoothHeadset(  880): Proxy object disconnected
D/AudioService(  880): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1540): Proxy object disconnected
D/BluetoothHeadset( 1505): Proxy object disconnected
,D/BluetoothHeadset( 1505): Proxy object disconnected
D/A2dpService( 5266): Received stop request...Stopping profile...
D/A2dpStateMachine( 5266): Exit Disconnected: -1
,D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
,D/BluetoothA2dp(  880): Proxy object disconnected
D/AudioService(  880): onServiceDisconnected: Bluetooth profile: 2
,D/CommandListener(  291): Clearing all IP addresses on wlan0
D/HidService( 5266): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
,E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  880): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  880): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Disconnected - quitting
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  880): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  880): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/BluetoothManagerService(  880): Message: 30
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524292
D/HealthService( 5266): Received stop request...Stopping profile...
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityManager.CallbackHandler( 1931): CM callback handler got msg 524292
,D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
I/ModemStatsDSDetect( 1523): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/PanService( 5266): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
E/WifiStateMachine(  880): stopping supplicant
I/ModemStatsDSDetect( 1523): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1523): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1523): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/BtGatt.DebugUtils( 5266): handleDebugAction() action=null
E/WifiStateMachine(  880): setWifiState: disabling
,D/BtGatt.GattService( 5266): Received stop request...Stopping profile...
D/BtGatt.GattService( 5266): stop()
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BtGatt.AdvertiseManager( 5266): advertise clients cleared
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1523): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1523): onReceive() - done, currentInetCondition=0
,D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
,D/BluetoothMapService( 5266): Received stop request...Stopping profile...
D/BluetoothMapService( 5266): stop()
D/BluetoothMapEmailAppObserver( 5266): deinitObservers()
,D/BluetoothMapEmailAppObserver( 5266): removeReceiver()
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BluetoothAdapterService( 5266): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22675df4
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/HeadsetStateMachine( 5266): Unbinding service...
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/BluetoothHeadsetServiceJni( 5266): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 5266): Cleaning up Bluetooth Handsfree callback object
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/GKI_LINUX( 5266): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 5266): GKI_exit_task 2 done
,I/GKI_LINUX( 5266): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 5266): Cleaning up Bluetooth HID Interface...
D/LocalBluetoothProfileManager( 6579): LocalBluetoothProfileManager construction complete
,W/bt-btif ( 5266): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5266): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 5266): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 5266): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 5266): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5266): Cleaning up Bluetooth PAN callback object
,D/BluetoothMapService( 5266): MAP Service closeService in
D/BluetoothMapService( 5266): cleanup()
D/BluetoothAdapterState( 5266): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 5266): MAP Service closeService in
D/BluetoothAdapterProperties( 5266): Setting state to 10
I/BluetoothAdapterState( 5266): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  880): Message: 60
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService(  880): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothA2dp(  880): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 5266): Entering OffState
D/BluetoothHeadset( 1505): onBluetoothStateChange: up=false
,D/BluetoothPbap( 6579): onBluetoothStateChange: up=false
D/BluetoothMap( 6579): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 6579): onBluetoothStateChange: up=false
D/BluetoothHeadset(  880): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1540): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1505): onBluetoothStateChange: up=false
,D/BluetoothPan( 6579): onBluetoothStateChange on: false
,D/BluetoothManagerService(  880): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  880): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/DockEventReceiver( 6579): finishStartingService: stopping service
,I/wpa_supplicant( 5328): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/BluetoothManagerService(  880): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@dbf7307 mBinding = false
,I/ActivityManager(  880): Killing 6335:com.android.vending/u0a32 (adj 15): empty #7
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293):  STA Disconnected !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
D/BluetoothManagerService(  880): Sending unbind request.
D/TCMD    (  478): NL - Read 1004 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
D/TCMD    (  478): NL - Read 68 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
,I/MDMCTBK (  293): send SAR ctrl over QMI
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 5328): eap_proxy Deinitialzed
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 0
D/BluetoothManagerService(  880): Bluetooth State Change Intent: 13 -> 10
W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_6335/cgroup.procs: No such file or directory
,D/Tethering(  880): InitialState.processMessage what=4
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/GKI_LINUX( 5266): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 5266): GKI_exit_task 1 done
I/GKI_LINUX( 5266): GKI_shutdown(): task [BTIF] terminated
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
,I/BluetoothServiceJni( 5266): cleanupNative: return from cleanup
D/BluetoothAdapter( 1291): 1068786939: getState() :  mService = null. Returning STATE_OFF
D/TCMD    (  478): NL - Read 1004 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
I/wpa_supplicant( 5328): wlan0: CTRL-EVENT-TERMINATING 
,D/BluetoothAdapter( 1291): 1068786939: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1291): 1068786939: getState() :  mService = null. Returning STATE_OFF
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
,D/MDMCTBK (  293): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  293):  Wpa Supplicant Exiting !!
D/MDMCTBK (  293): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  293): wifi_close_sockets: Close Wifi socket
E/WifiStateMachine(  880): Supplicant connection lost
D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
D/MDMCTBK (  293): wifi_close_sockets: Exit
,I/art     ( 5266): System.exit called, status: 0
I/AndroidRuntime( 5266): VM exiting with result code 0, cleanup skipped.
,W/ResourcesManager( 6607): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BluetoothAdapter( 1738): 887531039: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1738): 887531039: getState() :  mService = null. Returning STATE_OFF
,E/QC-QMI  (  433): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  433): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  433): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
,E/QC-QMI  (  433): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
E/QC-QMI  (  433): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,I/ActivityManager(  880): Process com.android.bluetooth (pid 5266) has died
,E/WifiStateMachine(  880): setWifiState: disabled
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 1738): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  880): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6634 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/GservicesProvider( 6634): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 6634): GMS http client unavailable, use old client
,I/GoogleHttpClient( 6634): GMS http client unavailable, use old client
,I/Babel_SMS( 6607): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6607): MmsConfig.loadMmsSettings
I/Babel_SMS( 6607): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6607): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6607): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6607): MmsConfig.loadFromResources
,E/Babel_SMS( 6607): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6607): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6607): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6607): startup - clean
,D/TCMD    (  478): NL - Read 444 bytes from update socket.
D/TCMD    (  478): NL - ignore NL message, type = 17
D/TCMD    (  478): Listening for incoming client connection request
,I/Babel   ( 6607): deleted: false for 0
,D/TCMD    (  478): NL - Read 1004 bytes from update socket.
D/TCMD    (  478): NL - message type is RTM_NEWLINK
D/TCMD    (  478): Listening for incoming client connection request
,I/ActivityManager(  880): Killing 6422:com.android.providers.calendar/u0a5 (adj 15): empty #7
,D/TCMD    (  478): NL - Read 444 bytes from update socket.
D/TCMD    (  478): NL - ignore NL message, type = 17
D/TCMD    (  478): Listening for incoming client connection request
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_6422/cgroup.procs: No such file or directory
,W/ContextImpl( 6579): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/VideoCapabilities( 6607): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6607): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6607): Unsupported mime video/mpeg2
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/ActivityManager(  880): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6665 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/DockEventReceiver( 6579): finishStartingService: stopping service
,I/VideoCapabilities( 6607): Unsupported profile 4 for video/mp4v-es
,W/ResourcesManager( 6665): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/VideoCapabilities( 6607): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6607): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6607): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6607): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Killing 6402:com.google.android.calendar/u0a49 (adj 15): empty #7
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,W/libprocessgroup(  880): failed to open /acct/uid_10049/pid_6402/cgroup.procs: No such file or directory
,I/vclib   ( 6607): onServiceConnected
,W/Babel   ( 6607): Attempted to change video mute state without an active call.
,D/AdapterServiceConfig( 6665): Adding HeadsetService
D/AdapterServiceConfig( 6665): Adding A2dpService
,D/AdapterServiceConfig( 6665): Adding HidService
,D/AdapterServiceConfig( 6665): Adding HealthService
,D/AdapterServiceConfig( 6665): Adding PanService
,D/AdapterServiceConfig( 6665): Adding GattService
D/AdapterServiceConfig( 6665): Adding BluetoothMapService
,I/ActivityManager(  880): Killing 1931:com.google.android.gms/u0a16 (adj 15): empty #7
,D/ConnectivityService(  880): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@369525df)
D/WifiService(  880): Client connection lost with reason: 4
,D/ConnectivityService(  880): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  880): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_1931/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 1738): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  293): NetlinkHandler, wifiStateChanged 0
,I/MDMCTBK (  293): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2536): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6692 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  880): MasterInitialState.processMessage what=3
,I/art     (  308): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 32.586ms
,D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2536): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2536): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2536): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2536): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2536): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2536): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/art     (  308): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 24.108ms
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/CCE     ( 2536): Registering with Alarm Manager to restart CCE
,D/Central_PollingManager( 1465): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2536): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2536): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2536): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2536): [debug] > CusSM.onRadioDown
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 20.377ms
,I/MusicStore( 6692): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6692): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6692): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6692): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6692): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6692): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6692): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6692): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6692): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@904a350: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6692): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6692): GMSCore installation verified
,I/ConfigStore( 6692): Config Database version: 1
,I/art     (  880): Explicit concurrent mark sweep GC freed 34939(1744KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.402ms total 127.646ms
,I/MediaRouter( 6692): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6692): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6741 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=6759 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/GHttpClientFactory( 6692): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6692): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6759): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6759): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Killing 6517:com.google.android.deskclock/u0a55 (adj 15): empty #7
,V/Mms     ( 6741): mnc/mcc: 
V/Mms     ( 6741): tag: int value: recipientLimit - 20
V/Mms     ( 6741): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6741): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6741): tag: int value: maxSubjectLength - 80
V/Mms     ( 6741): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6741): tag: bool value: enableGroupMms - false
V/Mms     ( 6741):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/MultiDex( 6759): VM with version 2.1.0 has multidex support
I/MultiDex( 6759): install
I/MultiDex( 6759): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  880): failed to open /acct/uid_10055/pid_6517/cgroup.procs: No such file or directory
,W/ResourcesManager( 6741): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6793 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6607:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6607/cgroup.procs: No such file or directory
,V/JNIHelp ( 6759): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PhoneMonitor( 6793): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6793): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6793): onReceive CONNECTIVITY_CHANGE networkType=1
,W/ActivityThread( 6759): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6759): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2fa4587f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6759): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  880): Killing 6383:com.motorola.context/u0a8 (adj 15): empty #7
,D/NativeLibraryUtils( 6759): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_6383/cgroup.procs: No such file or directory
,D/WifiP2pService(  880): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.SyncManager( 6759): SYNC; picasa accounts
,D/NetworkLogImpl( 6759): Loaded NetworkSpeedPredictor
,I/ActivityManager(  880): Killing 6579:com.android.settings/1000 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_1000/pid_6579/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6828 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6848 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6665:com.android.bluetooth/1002 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_1002/pid_6665/cgroup.procs: No such file or directory
,W/ResourcesManager( 6848): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6848): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6848): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6848): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6848): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6848): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6848): MmsConfig.loadFromResources
,E/Babel_SMS( 6848): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6848): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6848): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6848): startup - clean
,I/Babel   ( 6848): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6880 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6848): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6848): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6848): Unsupported mime video/mpeg2
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6880): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6880): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6880):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6880):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6880): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/VideoCapabilities( 6848): Unsupported profile 4 for video/mp4v-es
,W/GAv4    ( 6880): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/VideoCapabilities( 6848): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6848): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6848): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6848): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/GAv4    ( 6880): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/ContextImpl( 6880): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/vclib   ( 6848): onServiceConnected
W/Babel   ( 6848): Attempted to change video mute state without an active call.
,V/AlarmManager(  880): send {23c76a01, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {32370db4, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/Babel   ( 6848): connection state changed from UNKNOWN to DISCONNECTED
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6880): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager(  880): Killing 6692:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/GAv4    ( 6880): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_6692/cgroup.procs: No such file or directory
,V/AlarmManager(  880): done {23c76a01, *alarm*:android.intent.action.TIME_TICK} [125ms]
,I/WebViewFactory( 6880): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6880): Time to load native libraries: 2 ms (timestamps 4665-4667)
I/LibraryLoader( 6880): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6880): Binding Chromium to main looper Looper (main, tid 1) {66ed3ab}
,I/LibraryLoader( 6880): Expected native library version number "",actual native library version number ""
I/chromium( 6880): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6880): Initializing chromium process, singleProcess=true
,W/art     ( 6880): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6880): ApplicationContext is null in ApplicationStatus
,W/chromium( 6880): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6880): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6880): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6880): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6880): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6880): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6880): Local Branch: 
I/Adreno-EGL( 6880): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6880): Local Patches: NONE
I/Adreno-EGL( 6880): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6880): Requires BLUETOOTH permission
,I/NSApplication( 6880): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6947 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6741:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_6741/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6969 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6793:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_6793/cgroup.procs: No such file or directory
,W/ResourcesManager( 6969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6989 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7015 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6848:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 6989): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 6828:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6848/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_6828/cgroup.procs: No such file or directory
,I/MusicStore( 7015): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7015): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7015): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7015): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7015): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7015): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7015): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7015): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7015): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@904a350: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7015): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7015): GMSCore installation verified
,I/ConfigStore( 7015): Config Database version: 1
,I/art     (  880): Explicit concurrent mark sweep GC freed 15071(818KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.414ms total 111.506ms
,I/MediaRouter( 7015): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7015): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7048 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 20.984ms
,I/GHttpClientFactory( 7015): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.052ms
,I/GoogleURLConnFactory( 7015): Using platform SSLCertificateSocketFactory
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 21.087ms
,I/ActivityManager(  880): Killing 6880:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_6880/cgroup.procs: No such file or directory
,V/Mms     ( 7048): mnc/mcc: 
,V/Mms     ( 7048): tag: int value: recipientLimit - 20
V/Mms     ( 7048): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7048): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7048): tag: int value: maxSubjectLength - 80
V/Mms     ( 7048): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7048): tag: bool value: enableGroupMms - false
V/Mms     ( 7048):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7048): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7083 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6947:com.android.chrome/u0a52 (adj 15): empty #7
,D/PhoneMonitor( 7083): Register our PhoneStateListener
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_6947/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7083): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7083): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 6969:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6969/cgroup.procs: No such file or directory
I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7105 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7125 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6989:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_6989/cgroup.procs: No such file or directory
,W/ResourcesManager( 7125): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7125): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7125): MmsConfig.loadMmsSettings
I/Babel_SMS( 7125): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7125): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7125): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7125): MmsConfig.loadFromResources
,E/Babel_SMS( 7125): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7125): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7125): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7125): startup - clean
,I/Babel   ( 7125): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7156 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7125): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7125): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7125): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7125): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7125): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7125): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7125): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7125): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7125): onServiceConnected
W/Babel   ( 7125): Attempted to change video mute state without an active call.
I/Babel   ( 7125): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  880): Killing 7015:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/lowmemorykiller(  277): Error writing /proc/7015/oom_score_adj; errno=22
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7015/cgroup.procs: No such file or directory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7156): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7156): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7156): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7156): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7156):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7156):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7156): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7156): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7156): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7156): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7156): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7156): Time to load native libraries: 1 ms (timestamps 8020-8021)
I/LibraryLoader( 7156): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7156): Binding Chromium to main looper Looper (main, tid 1) {66ed3ab}
,I/LibraryLoader( 7156): Expected native library version number "",actual native library version number ""
,I/chromium( 7156): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7156): Initializing chromium process, singleProcess=true
,W/art     ( 7156): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7156): ApplicationContext is null in ApplicationStatus
,W/chromium( 7156): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7156): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7156): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7156): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7156): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7156): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7156): Local Branch: 
I/Adreno-EGL( 7156): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7156): Local Patches: NONE
I/Adreno-EGL( 7156): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7156): Requires BLUETOOTH permission
,I/NSApplication( 7156): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7225 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7048:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7048/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7244 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7083:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7083/cgroup.procs: No such file or directory
,W/ResourcesManager( 7244): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7264 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7125:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 7264): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7105:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7125/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2536): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7105/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2536): bindWebServices(): registering our AIDL callback...
I/SundryService( 2536): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2536): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2536): onServiceConnected()
D/GetNotificationsWS( 2536): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2536): unbindWebServices(): un-registering our AIDL callback...
,D/WearableService( 1738): callingUid 10016, callindPid: 1738
,E/MDM     ( 1738): [177] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6759): Restart initialization of location
,D/AuthorizationBluetoothService( 1738): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7292 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6759): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6759): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     (  880): Explicit concurrent mark sweep GC freed 10089(472KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.565ms total 124.911ms
,W/GCoreFlp( 1738): No location to return for getLastLocation()
W/FusedLocationProvider( 1738): location=null
,I/MDMCTBK (  293): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  293): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
,I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
,W/IcingInternalCorpora( 6759): getNumBytesRead when not calculated.
,V/AlarmManager(  880): done {32370db4, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [4969ms]
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7333 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7333): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7333): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7333): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7333): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7333): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7333): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7333): MmsConfig.loadFromResources
E/Babel_SMS( 7333): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7333): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7333): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7333): startup - clean
,I/Babel   ( 7333): deleted: false for 0
,W/VideoCapabilities( 7333): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7333): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7333): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7333): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7333): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7333): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7333): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7333): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Killing 7156:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7156/cgroup.procs: No such file or directory
,I/vclib   ( 7333): onServiceConnected
,W/Babel   ( 7333): Attempted to change video mute state without an active call.
,I/ActivityManager(  880): Killing 7225:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7225/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  293): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  293): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  293): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  293): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
,W/SQLiteConnectionPool( 6759): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311612, SEQNUM=4536, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-1142, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312139, SEQNUM=4538, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-1182, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,D/ConnectivityService(  880): Failed to find a new network - expiring NetTransition Wakelock
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=269, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311989, SEQNUM=4540, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-1678, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {23c76a01, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {3964c334, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {3964c334, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [10ms]
,V/AlarmManager(  880): done {23c76a01, *alarm*:android.intent.action.TIME_TICK} [47ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {23c76a01, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {2562adc7, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7383 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  880): done {23c76a01, *alarm*:android.intent.action.TIME_TICK} [107ms]
,I/GAv4    ( 7383): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7383):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7383):   adb logcat -s GAv4
,W/GAv4    ( 7383): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7383): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7383): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  880): done {2562adc7, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [190ms]
I/ActivityManager(  880): Killing 7244:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7244/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311344, SEQNUM=4547, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-108, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312214, SEQNUM=4548, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-11, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {23c76a01, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {3964c334, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {3964c334, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [11ms]
,V/AlarmManager(  880): done {23c76a01, *alarm*:android.intent.action.TIME_TICK} [50ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311327, SEQNUM=4550, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1008, POWER_SUPPLY_CHARGE_COUNTER=1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311595, SEQNUM=4551, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=44, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311894, SEQNUM=4553, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=-4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310718, SEQNUM=4554, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=-3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311301, SEQNUM=4555, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-19, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7424): 
D/AndroidRuntime( 7424): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7424): CheckJNI is OFF
D/AndroidRuntime( 7424): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10375 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 5215:com.test.thalitest/u0a375 (adj 9): stop com.test.thalitest
W/PackageSettings(  880): Skipping PackageSetting{26e03575 com.example.hello/10359} due to missing metadata
I/WindowState(  880): WIN DEATH: Window{18b45336 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  880): Client connection lost with reason: 4
I/ActivityManager(  880):   Force finishing activity ActivityRecord{2b4ba6f3 u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  880): Spurious death for ProcessRecord{bcd131d 5215:com.test.thalitest/u0a375}, curProc for 5215: null
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10375 user=0: pkg removed
I/ActivityManager(  880):   Force finishing activity ActivityRecord{2b4ba6f3 u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  880): Duplicate finish request for ActivityRecord{2b4ba6f3 u0 com.test.thalitest/.MainActivity t3 f}
I/art     ( 2971): Explicit concurrent mark sweep GC freed 16205(2MB) AllocSpace objects, 32(512KB) LOS objects, 39% free, 7MB/12MB, paused 753us total 48.536ms
I/ProcessStatsService(  880): Prepared write state in 14ms
I/art     ( 1558): Explicit concurrent mark sweep GC freed 7667(548KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 586us total 83.330ms
I/ProcessStatsService(  880): Prepared write state in 9ms
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1738): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1406): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1406): run()
D/VoicemailCleanupService( 7264): Cleaning up data for package: com.test.thalitest
I/art     (  880): Explicit concurrent mark sweep GC freed 15737(1246KB) AllocSpace objects, 10(210KB) LOS objects, 33% free, 20MB/30MB, paused 1.666ms total 177.822ms
I/art     (  880): WaitForGcToComplete blocked for 107.040ms for cause Explicit
I/Decoder ( 1406): createOrResetDecoder
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7451 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  308): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 22.117ms
I/art     (  308): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.667ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 27.524ms
I/ConfigService( 1738): onCreate
W/asset   ( 7451): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7451): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7451): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): run()
I/ProcessStatsService(  880): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-11-09.bin
I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = history
I/art     (  880): Explicit concurrent mark sweep GC freed 4596(251KB) AllocSpace objects, 1(49KB) LOS objects, 33% free, 20MB/30MB, paused 1.959ms total 234.087ms
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7478 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1406): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1406): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1406): run()
I/StatsUtilsManager( 1406): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1406): shouldRecordStats() = Too Soon
I/ActivityManager(  880): Killing 7292:com.google.android.apps.photos/u0a88 (adj 15): empty #7
W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7292/cgroup.procs: No such file or directory
D/AndroidRuntime( 7424): Shutting down VM
W/ContextImpl( 7478): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 6759): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 6759): Reading stored module config
D/AccountUtils( 6759): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 6759): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6759): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 6759): Removing dialog suppression flag for package com.test.thalitest
I/Launcher( 1558): Deferring update until onResume
I/GMPM-SVC( 6759): App measurement is starting up, version: 8489
I/GMPM-SVC( 6759): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1738): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1738): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 6759): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6759): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6759): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6759): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6759): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6759): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 6759): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 6759): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6759): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6759): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6759): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6759): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6759): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7511 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
V/AlarmManager(  880): send {23c76a01, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {34aeaa92, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  880): send {f0dacfe, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
V/AlarmManager(  880): send {1dfc3c5f, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
V/AlarmManager(  880): send {2f44d6ac, *alarm*:com.google.android.gms/.common.download.DownloadAlarmReceiver}
I/ActivityManager(  880): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=7530 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  880): send {34682ce5, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
V/AlarmManager(  880): done {34682ce5, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [50ms]
V/AlarmManager(  880): done {23c76a01, *alarm*:android.intent.action.TIME_TICK} [89ms]
W/BaseAppContext( 6759): Using Auth Proxy for data requests.
D/ChimeraCfgMgr( 6759): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6759): Module APK com.google.android.play.games already loaded
W/Launcher( 1558): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@33476ade new=com.google.android.velvet.VelvetApplication@33476ade
D/Finsky  ( 7530): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/ActivityManager(  880): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7569 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
E/ConnectivityChangeReceiver( 6759): Ignoring connectivity change
E/BaseAppContext( 6759): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 6759): Using Auth Proxy for data requests.
W/BaseAppContext( 6759): Using Auth Proxy for data requests.
W/BaseAppContext( 6759): Using Auth Proxy for data requests.
I/Icing   ( 6759): Storage manager: low false usage 1.74MB avail 3.22GB capacity 4.85GB
D/ConnectivityService(  880): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/BaseAppContext( 6759): Using Auth Proxy for data requests.
W/BaseAppContext( 6759): Using Auth Proxy for data requests.
W/BaseAppContext( 6759): Using Auth Proxy for data requests.
W/BaseAppContext( 6759): Using Auth Proxy for data requests.
W/DriveInitializer( 6759): Awaiting to be initialized
W/DriveInitializer( 6759): Background init thread started
I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7613 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
D/Finsky  ( 7530): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/UpdateIcingCorporaServi( 7511): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Settings( 7530): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7530): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.gms/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6759): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
D/Finsky  ( 7530): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Ads     ( 7530): Skipping gmscore version check
V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7530): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7530): [1] Libraries$2.run: Finished loading 1 libraries.
I/art     ( 6634): Explicit concurrent mark sweep GC freed 2016(86KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 374us total 32.531ms
D/Finsky  ( 7530): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  880): Killing 7333:com.google.android.talk/u0a70 (adj 15): empty #7
D/Finsky  ( 7530): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/SQLiteLog( 6759): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 7511): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 6759): (3850) statement aborts at 151: [DELETE FROM FileContent163 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 6759): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6759): Process: com.google.android.gms, PID: 6759
E/AndroidRuntime( 6759): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 6759): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 6759): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3166)
E/AndroidRuntime( 6759): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6759): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6759): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6759): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DocListDatabase( 6759): Failed to delete from FileContent163 table
E/DocListDatabase( 6759): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 6759): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 6759): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 6759): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 6759): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 6759): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 6759): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 6759): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/DocListDatabase( 6759): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/DocListDatabase( 6759): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/DocListDatabase( 6759): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 6759): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 6759): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 6759): Sending signal. PID: 6759 SIG: 9
D/ConnectivityService(  880): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@37f85f99)
D/ConnectivityService(  880): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  880): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
