#### Test 50650278c17c777_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:31000 mC
D/AndroidRuntime( 5033): 
D/AndroidRuntime( 5033): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5033): CheckJNI is OFF
D/AndroidRuntime( 5033): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5052 uid=10374 gids={50374, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5033): Shutting down VM
I/art     (  880): Explicit concurrent mark sweep GC freed 19445(1037KB) AllocSpace objects, 2(195KB) LOS objects, 33% free, 19MB/29MB, paused 1.677ms total 113.573ms
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5052): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5052): Time to load native libraries: 2 ms (timestamps 7564-7566)
I/LibraryLoader( 5052): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5052): Binding Chromium to main looper Looper (main, tid 1) {1f91988e}
I/LibraryLoader( 5052): Expected native library version number "",actual native library version number ""
I/chromium( 5052): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5052): Initializing chromium process, singleProcess=true
W/art     ( 5052): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5052): ApplicationContext is null in ApplicationStatus
W/chromium( 5052): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5052): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5052): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5052): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5052): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5052): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5052): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5052): Local Branch: 
I/Adreno-EGL( 5052): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5052): Local Patches: NONE
I/Adreno-EGL( 5052): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@276b1e61:true
D/BluetoothAdapter( 5052): 543254465: getState() :  mService = null. Returning STATE_OFF
W/ActivityManager(  880): Activity pause timeout for ActivityRecord{15ce5662 u0 com.test.thalitest/.MainActivity t3}
W/art     ( 5052): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5052): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5052): CordovaWebView is running on device made by: motorola
W/art     ( 5052): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5052): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5052): Render dirty regions requested: true
D/Atlas   ( 5052): Validating map...
W/chromium( 5052): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 5052): Initialized EGL, version 1.4
D/OpenGLRenderer( 5052): Enabling debug mode 0
I/Keyboard.Facilitator( 1406): onFinishInput()
I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,1116
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +904ms (total +1s116ms)
W/IInputConnectionWrapper( 5052): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5052): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5052): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5052): Cannot call determinedVisibility() - never saw a connection for the pid: 5052
,D/JsMessageQueue( 5052): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5052): JniHelper::setJavaVM(0xb7f12310), pthread_self() = -1205200664
,D/JX-Cordova( 5052): jxcore cordova android initializing
,W/jxcore-log( 5052): Initializing JXcore engine
W/jxcore-log( 5052): JXcore engine is ready
,W/jxcore-log( 5052): Starting JXcore engine
,W/.test.thalitest( 5052): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10374 path="socket:[8588]" dev="sockfs" ino=8588 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5052): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10374 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5052): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10374 path="socket:[9723]" dev="sockfs" ino=9723 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5052): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10374 path="socket:[22285]" dev="sockfs" ino=22285 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5052): Platform android
W/jxcore-log( 5052): 
,W/jxcore-log( 5052): Process ARCH arm
W/jxcore-log( 5052): 
,I/jxcore-log( 5052): JXcore Cordova bridge is ready!
I/jxcore-log( 5052): 
,W/jxcore-log( 5052): JXcore engine is started
I/chromium( 5052): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5052): Toggling radios to true
I/jxcore-log( 5052): 
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  880): enable():  mBluetooth =null mBinding = false
,W/Settings( 1461): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  880): Message: 1
D/BluetoothManagerService(  880): MESSAGE_ENABLE: mBluetooth = null
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: true pid=5052, uid=10374
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine(  880): setting operational mode to 1
,I/jxcore-log( 5052): Radios toggled
I/jxcore-log( 5052): 
,I/ActivityManager(  880): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5103 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,W/Settings( 1461): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1461): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1461): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/ResourcesManager( 5103): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 5103): Adding HeadsetService
D/AdapterServiceConfig( 5103): Adding A2dpService
D/AdapterServiceConfig( 5103): Adding HidService
D/AdapterServiceConfig( 5103): Adding HealthService
D/AdapterServiceConfig( 5103): Adding PanService
D/AdapterServiceConfig( 5103): Adding GattService
D/AdapterServiceConfig( 5103): Adding BluetoothMapService
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
,D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ff36141:true
,D/Tethering(  880): InitialState.processMessage what=4
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
D/TCMD    (  465): NL - Read 1008 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/BluetoothAdapterState( 5103): make
,D/TCMD    (  465): NL - Read 1008 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
,D/TCMD    (  465): Listening for incoming client connection request
,I/bluedroid( 5103): init
I/BluetoothAdapterState( 5103): Entering OffState
,I/bte_conf( 5103): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,D/QsoftapCmd(  296): Got softap fwreload command we are passing on
,I/bte_conf( 5103): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,D/SoftapController(  296): Softap fwReload - Ok
,E/bt_osi_config( 5103): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5103): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 5103): get_profile_interface socket
I/bluedroid( 5103): get_profile_interface map_client
,I/GKI_LINUX( 5103): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 5103): Address is:44:80:EB:7B:5A:05
,D/BluetoothManagerService(  880): Bluetooth Adapter name changed to XT1072
,D/BluetoothManagerService(  880): Stored Bluetooth name: XT1072
D/BluetoothAdapterProperties( 5103): Name is: XT1072
D/BluetoothManagerService(  880): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  880): Message: 40
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/CommandListener(  296): Setting iface cfg
D/CommandListener(  296): Trying to bring down wlan0
D/CommandListener(  296): Clearing all IP addresses on wlan0
I/bluedroid( 5103): config_hci_snoop_log
D/BluetoothManagerService(  880): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  880): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 5103): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 5103): Setting state to 11
,I/BluetoothAdapterState( 5103): Bluetooth adapter state changed: 10-> 11
E/WifiStateMachine(  880): setWifiState: enabling
D/BluetoothBondStateMachine( 5103): make
D/BluetoothManagerService(  880): Message: 60
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  880): Bluetooth State Change Intent: 10 -> 11
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/BluetoothBondStateMachine( 5103): StableState(): Entering Off State
,E/WifiStateMachine(  880): Supplicant start successful
D/WifiMonitor(  880): startMonitoring(wlan0) with mConnected = false
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/BluetoothHeadset( 1538): Proxy object connected
D/BluetoothHeadset(  880): Proxy object connected
,D/HeadsetService( 5103): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 5103): classInitNative: succeeds
,D/BluetoothHeadset( 1502): Proxy object connected
,D/HeadsetStateMachine( 5103): make
,D/BluetoothHeadset( 1502): Proxy object connected
,I/ActivityManager(  880): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5149 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/HeadsetStateMachine( 5103): max_hf_connections = 1
,I/bluedroid( 5103): get_profile_interface handsfree
,I/wpa_supplicant( 5146): Successfully initialized wpa_supplicant
I/wpa_supplicant( 5146): Long line in configuration file truncated
,I/wpa_supplicant( 5146): rfkill: Cannot open RFKILL control device
D/TCMD    (  465): NL - Read 1004 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/HeadsetStateMachine( 5103): Enter Disconnected: -2, size: 0
,D/Checkin ( 2969): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
,I/BluetoothAdapterState( 5103): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothA2dp(  880): Proxy object connected
,D/Checkin ( 2969): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
D/A2dpService( 5103): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 5103): classInitNative: succeeds
I/bluedroid( 5103): get_profile_interface avrcp
,I/libmdmdetect( 5146): ESOC framework not supported
E/Diag_Lib( 5146):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 5146): baseband property is set to [msm]
I/libmdmdetect( 5146): ESOC framework not supported
,E/wpa_supplicant( 5146):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5146): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5146): card_info[i].card_state: 0x0
E/wpa_supplicant( 5146): card_info[i].error_code: 0x0
E/wpa_supplicant( 5146): SIM/USIM not ready
E/wpa_supplicant( 5146): Error while reading SIM card status
,E/wpa_supplicant( 5146): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5146): card_info[i].card_state: 0x0
,E/wpa_supplicant( 5146): card_info[i].error_code: 0x0
E/wpa_supplicant( 5146): SIM/USIM not ready
I/wpa_supplicant( 5146): eap_proxy: Card not ready
,E/RemoteController( 5103): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 5103): classInitNative: succeeds
D/A2dpStateMachine( 5103): make
,I/bluedroid( 5103): get_profile_interface a2dp
I/GKI_LINUX( 5103): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
I/BluetoothHidServiceJni( 5103): classInitNative: succeeds
D/A2dpStateMachine( 5103): Enter Disconnected: -2
,W/ResourcesManager( 5149): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/HidService( 5103): Received start request. Starting profile...
I/bluedroid( 5103): get_profile_interface hidhost
D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
I/BluetoothHealthServiceJni( 5103): classInitNative: succeeds
,D/HealthService( 5103): Received start request. Starting profile...
,I/bluedroid( 5103): get_profile_interface health
D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
I/BluetoothPanServiceJni( 5103): classInitNative(L105): succeeds
,D/PanService( 5103): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5103): initializeNative(L110): pan
I/bluedroid( 5103): get_profile_interface pan
,D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
D/HeadsetStateMachine( 5103): Proxy object connected
,I/BtGatt.JNI( 5103): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 5103): handleDebugAction() action=null
,D/BtGatt.GattService( 5103): Received start request. Starting profile...
D/BtGatt.GattService( 5103): start()
I/bluedroid( 5103): get_profile_interface gatt
D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
D/BtGatt.AdvertiseManager( 5103): advertise manager created
,D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
,D/HeadsetStateMachine( 5103): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 5103): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 5103): Disconnected process message: 11, size: 0
,D/BluetoothMapService( 5103): Received start request. Starting profile...
D/BluetoothMapService( 5103): start()
,D/BluetoothMapEmailSettingsLoader( 5103): Found 0 applications
D/BluetoothMapEmailAppObserver( 5103): createReceiver()
,D/BluetoothMapEmailAppObserver( 5103): initObservers()
D/BluetoothMapEmailAppObserver( 5103): getEnabledAccountItems()
,D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
,D/BluetoothAdapterState( 5103): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5103): enable
I/GKI_LINUX( 5103): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 5103): init
I/bt-btu  ( 5103): btu_task pending for preload complete event
,I/bt_vendor( 5103): bt-vendor : init
D/bt_userial_mct( 5103): userial_init
I/bt_hwcfg( 5103): Starting hciattach daemon
I/bt_hwcfg( 5103): try to set false
I/bt_hwcfg( 5103): Starting hciattach daemon
I/bt_hwcfg( 5103): try to set true
,I/qcom-bluetooth( 5180): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,E/wpa_supplicant( 5146): Line 31: unknown global field 's'.
E/wpa_supplicant( 5146): Line 31: Invalid configuration line 's'.
I/wpa_supplicant( 5146): rfkill: Cannot open RFKILL control device
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/ActivityManager(  880): Killing 4841:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,E/wpa_supplicant( 5146): baseband property is set to [msm]
I/libmdmdetect( 5146): ESOC framework not supported
,E/wpa_supplicant( 5146):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5146): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5146): card_info[i].card_state: 0x0
E/wpa_supplicant( 5146): card_info[i].error_code: 0x0
E/wpa_supplicant( 5146): SIM/USIM not ready
E/wpa_supplicant( 5146): Error while reading SIM card status
,E/wpa_supplicant( 5146): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5146): card_info[i].card_state: 0x0
E/wpa_supplicant( 5146): card_info[i].error_code: 0x0
E/wpa_supplicant( 5146): SIM/USIM not ready
,I/wpa_supplicant( 5146): eap_proxy: Card not ready
I/wpa_supplicant( 5146): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
I/qcom-bluetooth( 5187): /system/etc/init.qcom.bt.sh: Transport : smd 
E/WifiStateMachine(  880): setSuspendOptimizations: 2 true
E/WifiStateMachine(  880): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  880): Supplicant connection established
E/WifiStateMachine(  880): setWifiState: enabled
,I/qcom-bluetooth( 5189): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 5191): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_4841/cgroup.procs: No such file or directory
,I/qcom-bluetooth( 5192): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/AuthorizationBluetoothService( 1689): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiConfigStore(  880): Loading config and enabling all networks 
,I/qcom-bluetooth( 5193): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/WifiConfigStore(  880):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  880):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  880): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/wpa_supplicant( 5146): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5146): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,D/WifiNative-HAL(  880): Setting external_sim to 1
,D/WifiStateMachine(  880): Setting OUI to DA-A1-19
I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2e0d89c
D/wifi    (  880): halHandle = 0x0, mVM = 0xb7f12310, mCls = 0x17c2
I/WifiNative-HAL(  880): Could not start hal
,E/WifiStateMachine(  880): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 5146): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=5198 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
E/native  (  880): do suspend true
D/WifiP2pService(  880): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  296): Setting iface cfg
D/CommandListener(  296): Trying to bring up p2p0
D/WifiMonitor(  880): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  880): P2pEnablingState
D/WifiP2pService(  880): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2p socket connection successful
D/WifiP2pService(  880): P2pEnabledState
D/WifiP2pService(  880): sending p2p connection changed broadcast
,D/WifiScanningService(  880): SCAN_AVAILABLE : 3
D/WifiScanningService(  880): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa19399cc
D/wifi    (  880): halHandle = 0x0, mVM = 0xb7f12310, mCls = 0x101526
I/WifiNative-HAL(  880): Could not start hal
E/WifiScanningService(  880): could not start HAL
,D/RttService(  880): SCAN_AVAILABLE : 3
,D/RttService(  880): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/art     (  315): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 23.262ms
,D/WifiNative-HAL(  880): p2pGetDeviceAddress
D/WifiNative-HAL(  880): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/WifiP2pService(  880): DeviceAddress: 44:80:eb:7b:5a:07
,D/WifiP2pService(  880): MCC mode enabled 0
D/WifiP2pService(  880): mP2pAutoConnectSupport = 0
D/WifiP2pService(  880): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  880): InactiveState
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.009ms
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  880): set country code US
D/WifiP2pService(  880): InactiveState{ when=-1ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  880): set frequency band 2
D/WifiP2pService(  880): InactiveState{ when=-3ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-3ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5146): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 5146): wlan0: Failed to initiate AP scan
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info0x
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 20.813ms
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/SharedPreferencesImpl(  880): Couldn't create directory for SharedPreferences file shared_prefs/android_preferences.xml
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 5198): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/MDMCTBK (  298): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  298): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): wifi_connect_to_supplicant, current pid is = 298
,D/MDMCTBK (  298): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  298): wifi_close_sockets: Exit
E/MDMCTBK (  298): Attach monitor thread
I/MDMCTBK (  298): createWifiMonitorThread: Started the wifi monitor thread -1202512072
D/MDMCTBK (  298): wifi_wait_on_socket: Enter monitor thread
,I/MDMCTBK (  298): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  298): NetlinkHandler, interfaceAdded
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
E/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  298): , Wifi = 0
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  298): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
,I/MDMCTBK (  298): send SAR ctrl over QMI
,I/ActivityManager(  880): Killing 4865:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/Checkin ( 2969): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2969): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_4865/cgroup.procs: No such file or directory
,D/Checkin ( 2969): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/Checkin ( 2969): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/MDMCTBK (  298): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  298): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  298): Event received = WPS-AP-AVAILABLE 
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2e0d8fc
D/wifi    (  880): halHandle = 0x0, mVM = 0xb7f12310, mCls = 0x17e2
I/WifiNative-HAL(  880): Could not start hal
E/WifiStateMachine(  880): [1,449,746,324,232 ms] noteScanEnd no scan source
,E/WifiStateMachine(  880): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3b528d62 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  880): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  880):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  880): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  880): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  880): will read network variables netId=0
,E/WifiStateMachine(  880): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  880): will read network variables netId=0
,I/wpa_supplicant( 5146): wlan0: Trying to associate with SSID 'NG700'
,D/WifiMonitor(  880): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 5146): DSDS: eapol_sm_notify_config config->sim_num = 1
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  298): Event received = Trying to associate with
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiConfigStore(  880): setLastSelectedConfiguration -1
,E/wpa_supplicant( 5146): PNO: In assoc process
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/qcom-bluetooth( 5233): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 44:80:eb:7b:5a:05 
,I/qcom-bluetooth( 5234): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledStateupdate channel list
,I/bt_hwcfg( 5103): bluetooth satus is on
D/bt_userial_mct( 5103): userial_open(port:0)
,I/bt_userial_vendor( 5103): Done intiailizing UART
D/TCMD    (  465): NL - Read 312 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 192 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/TCMD    (  465): NL - Read 80 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 80 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
I/wpa_supplicant( 5146): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  298): Event received = Associated with c0:ff:d4
,I/bt_userial_vendor( 5103): Done intiailizing UART
I/bt_userial_mct( 5103): CMD=53, EVT=53, ACL_Out=54, ACL_In=54
,I/bt_vendor( 5103): Bluetooth Firmware and smd is initialized
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/bt-btu  ( 5103): btu_task received preload complete event
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,E/Tethering(  880): ApnList is empty for checkDunConfigured()
,D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
,D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 5146): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 5146): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  298): Event received = WPA: Key negotiation com
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  298): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  298):  STA Connected !!
D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
,D/TCMD    (  465): Listening for incoming client connection request
E/MDMCTBK (  298): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  298): get_freq !!, resp=2412
,I/MDMCTBK (  298): get_freq !!, Strip data
I/MDMCTBK (  298): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): get_property_value, Enter
I/MDMCTBK (  298): get_property_value, Values read from property=0,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  298): get_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler, Wifi Band changed, call setWifiCutback.
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 1, data=0
I/MDMCTBK (  298): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  298): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): get_property_value, Enter
I/MDMCTBK (  298): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  298): get_property_value, Exit
I/MDMCTBK (  298): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1202496240
I/MDMCTBK (  298): return from set_get_from_wpa_supplicant
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/MDMCTBK (  298): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  298): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  298): , reply_len: 3, ret: 0
E/MDMCTBK (  298): MdmCutbackHndler, resp=OK
E/MDMCTBK (  298): 
,D/MDMCTBK (  298): wifi_set_tx_pwr: Exit
,D/bt_userial_mct( 5103): Entering userial_read_thread()
,I/        ( 5103): BTE_InitTraceLevels -- TRC_HCI
I/        ( 5103): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5103): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5103): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5103): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5103): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5103): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5103): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5103): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5103): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5103): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5103): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5103): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5103): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5103): BTE_InitTraceLevels -- TRC_BTIF
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/global frequency( 2556): no tags to log
,D/Checkin ( 2556): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  880): Network connection established
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/bt-btm  ( 5103): BTM_SecRegister:p_cb_info->p_le_callback == 0xa6dd0d85 
E/bt-btm  ( 5103): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa6dd0d85 
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/WifiStateMachine(  880): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/bt-btif ( 5103): Calling BTA_HhEnable
E/bt-btif ( 5103): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 5103): Address is:44:80:EB:7B:5A:05
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BluetoothAdapterProperties( 5103): Name is: XT1072
,D/BluetoothAdapterProperties( 5103): Scan Mode:20
,D/BluetoothAdapterProperties( 5103): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5103): Adding bonded device:7C:F9:0E:37:96:AB
D/BluetoothManagerService(  880): Bluetooth Adapter name changed to XT1072
D/BluetoothAdapterProperties( 5103): Adding bonded device:58:2A:F7:ED:96:BE
D/BluetoothManagerService(  880): Stored Bluetooth name: XT1072
E/BluetoothRemoteDevices( 5103): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:37:96:AB, value is empty for type: 10
E/BluetoothRemoteDevices( 5103): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/bte_conf( 5103): Device ID record 1 : primary
,D/bte_conf( 5103):   vendorId            = 000f
D/bte_conf( 5103):   vendorIdSource      = 0001
D/bte_conf( 5103):   product             = 1200
D/bte_conf( 5103):   version             = 1436
D/bte_conf( 5103):   clientExecutableURL = 
D/bte_conf( 5103):   serviceDescription  = 
D/bte_conf( 5103):   documentationURL    = 
D/bte_conf( 5103): bte_load_did_conf no section named DID2.
E/bt_mct  ( 5103): hci lib postload completed
D/BluetoothAdapterState( 5103): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5103): ScanMode =  20
D/BluetoothAdapterProperties( 5103): State =  11
D/BluetoothAdapterProperties( 5103): Setting state to 12
I/BluetoothAdapterState( 5103): Bluetooth adapter state changed: 11-> 12
D/BluetoothPanServiceJni( 5103): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService(  880): Message: 60
I/BluetoothAdapterState( 5103): Entering On State
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  880): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset(  880): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 5103): Scan Mode:21
D/BluetoothAdapterProperties( 5103): Discoverable Timeout:120
D/BluetoothHeadset( 1502): onBluetoothStateChange: up=true
D/BluetoothA2dp(  880): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1538): onBluetoothStateChange: up=true
,D/BSUtils ( 2556): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/BluetoothHeadset( 1502): onBluetoothStateChange: up=true
D/BluetoothManagerService(  880): Bluetooth State Change Intent: 11 -> 12
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BluetoothManagerService(  880): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 5103): onReceive
,D/BluetoothMapService( 5103): STATE_ON
D/BluetoothManagerService(  880): Message: 40
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapMasInstance( 5103): Map Service startRfcommSocketListener
,D/ConnectivityService(  880): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  880): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  880): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BluetoothMapMasInstance( 5103): MAS initSocket()
,E/WifiStateMachine(  880): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine(  880): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5103): getBluetoothService() called with no BluetoothManagerCallback
D/CommandListener(  296): Setting iface cfg
,D/BluetoothMapMasInstance( 5103): Accepting socket connection...
,W/ContextImpl( 5149): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/Telecom ( 1502): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,E/WifiStateMachine(  880): Start Dhcp Watchdog 1
,D/HeadsetStateMachine( 5103): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 5103): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 5103): mNumber:  mType: 128
D/HeadsetStateMachine( 5103): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 5103): terminateScoUsingVirtualVoiceCall:No present call to terminate
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37f6c4df:true
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend false
,E/wpa_supplicant( 5146): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
E/wpa_supplicant( 5146): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2787f52c target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2787f52c target=com.android.internal.util.StateMachine$SmHandler }
,D/AuthorizationBluetoothService( 1689): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5103): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 5149): Adding local A2DP profile
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  880): Message: 30
,W/BluetoothAdapter( 5103): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 5103): Accept thread started.
,D/LocalBluetoothProfileManager( 5149): Adding local HEADSET profile
,D/BluetoothManagerService(  880): Message: 30
,D/BluetoothManagerService(  880): Message: 30
D/BluetoothManagerService(  880): Message: 30
,D/LocalBluetoothProfileManager( 5149): Adding local MAP profile
D/BluetoothMap( 5149): Create BluetoothMap proxy object
D/BluetoothManagerService(  880): Message: 30
D/BluetoothManagerService(  880): Message: 30
,D/LocalBluetoothProfileManager( 5149): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 5149): finishStartingService: stopping service
,D/BluetoothA2dp( 5149): Proxy object connected
,D/A2dpProfile( 5149): Bluetooth service connected
,D/BluetoothHeadset( 5149): Proxy object connected
D/HeadsetProfile( 5149): Bluetooth service connected
,D/BluetoothInputDevice( 5149): Proxy object connected
,D/HidProfile( 5149): Bluetooth service connected
,I/art     ( 2556): Explicit concurrent mark sweep GC freed 20295(1186KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 10MB/18MB, paused 1.204ms total 73.381ms
,D/BluetoothPan( 5149): BluetoothPAN Proxy object connected
D/PanProfile( 5149): Bluetooth service connected
,D/BluetoothMap( 5149): Proxy object connected
D/MapProfile( 5149): Bluetooth service connected
,D/BluetoothMap( 5149): getConnectedDevices()
,D/BluetoothPbap( 5149): Proxy object connected
D/PbapServerProfile( 5149): Bluetooth service connected
,E/DHCPCD  ( 5260): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5260): version 5.5.6 starting
E/DHCPCD  ( 5260): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 5260): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 5260): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/art     (  880): Explicit concurrent mark sweep GC freed 34061(1739KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.727ms total 144.403ms
,D/BSUtils ( 2556): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2556): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2556): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/DHCPCD  ( 5260): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/DHCPCD  ( 5260): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 5260): wlan0: sending REQUEST (xid 0x39a92b5), next in 3.12 seconds
,I/art     ( 1461): Explicit concurrent mark sweep GC freed 38207(2MB) AllocSpace objects, 16(570KB) LOS objects, 40% free, 7MB/12MB, paused 777us total 34.313ms
,D/BSUtils ( 2556): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2556): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2556): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2556): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2556): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2556): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2556): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2556): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2556): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2556): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2556): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2556): BcsDSCheckin.events found events 117
,D/Checkin ( 2556): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2556): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2556): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2556): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2556): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2556): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2556): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2556): unknown error code mapping for: 0
I/global frequency( 2556): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2556): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager(  880): send {15fb4760, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  880): done {15fb4760, *walarm*:com.google.android.intent.action.SEND_IDLE} [2ms]
,I/DHCPCD  ( 5260): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 5260): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 5260): wlan0: adding IP address 192.168.1.123/24
D/TCMD    (  465): NL - Read 60 bytes from update socket.
D/TCMD    (  465): NL - ignore NL message, type = 20
D/TCMD    (  465): Listening for incoming client connection request
D/DHCPCD  ( 5260): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 5260): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5260): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5260): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  880): WifiStateMachine DHCP successful
E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  880): Calling ARP set with IP = 192.168.1.123
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  880): Adding iface wlan0 to network 100
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/ConnectivityService(  880): Unexpected mtu value: 0, wlan0
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  880): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  880): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  880): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  880): Setting Dns servers for network 100 to [/192.168.1.1]
,E/WifiStateMachine(  880): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  880): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  880):    accepting network in place of null
,D/ConnectivityService(  880): Setting tx/rx TCP buffers to 131072,262144,3145728,4096,221184,3145728
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  880): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/CSLegacyTypeTracker(  880): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  880): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1926): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1520): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1520): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1520): onReceive() - done, currentInetCondition=0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 11:18:47 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449746326709], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449746326686]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Validated
,D/ConnectivityService(  880): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  880): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1926): CM callback handler got msg 524290
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/ModemStatsDSDetect( 1520): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1520): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1520): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1520): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1288): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:32000 mC
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/PollingManager( 2556): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1461): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AlarmManagerService(  880): Setting time of day to sec=1449746330
,W/AlarmManagerService(  880): Unable to set rtc to 1449746330: Invalid argument
,D/PollingManager( 2556): now: 199073 ,futureTime: 9223372036854775807
D/PollingManager( 2556): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/PollingManager( 2556): now: 199082 ,futureTime: 9223372036854775807
D/PollingManager( 2556): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2556): now: 199098 ,futureTime: 9223372036854775807
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5326 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  880): send {24cc91fe, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,D/Central_PollingManager( 1461): now: 199155 ,futureTime: 86473860
D/Central_PollingManager( 1461): Polling alarm set to expire at: 86473860 Current Time: 199155
,D/OtaApp  ( 2556): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2556): [debug] > PollingManagerService, now: 199177 ,futureTime: 11614528
D/OtaApp  ( 2556): [debug] > Polling alarm set to expire at: 11614528 Current Time: 199177
,D/MMApiProvisionService( 2556): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2556): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2556): createDeviceIdOrLogin update_device
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2556): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2556): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2556): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2556): isDeviceProvisioned: deviceId = 2072049230914535424
,I/art     ( 1461): Explicit concurrent mark sweep GC freed 3810(156KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 658us total 47.088ms
,D/CCE     ( 2556): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2556): createDeviceIdOrLogin update_device
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2556): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2556): isRequestAllowed(): already have outstanding request ... ignoring request
,D/MMApiWebService( 2556): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2556): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     (  880): Explicit concurrent mark sweep GC freed 18729(992KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.574ms total 184.041ms
,E/GpsLocationProvider(  880): No APN found to select.
,I/art     ( 2556): Explicit concurrent mark sweep GC freed 13247(865KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 982us total 83.711ms
,D/MMApiWebService( 2556): generating token using payload instead of using session token
,E/ActivityThread( 1926): Failed to find provider info for com.android.contacts.metadata
,I/MusicStore( 5326): Database version: 120
,D/GpsLocationProvider(  880): NTP server returned: 1449746327056 (Thu Dec 10 12:18:47 GMT+01:00 2015) reference: 196093 certainty: 10 system time offset: -3455
,E/LocSvc_ApiV02(  880): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,D/SyncManager(  880): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 231706, reason: UserStart
,D/MMApiProvisionService( 2556): isDeviceProvisioned: deviceId = 2072049230914535424
,D/ Nonce  ( 2556):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/CCE     ( 2556): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2556): createDeviceIdOrLogin update_device
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2556): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2556): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2556): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2556): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2556): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2556): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2556): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2556): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2556): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2556): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2556): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 2556): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
I/MMApiWSBase( 2556): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,D/ConnectivityManager.CallbackHandler( 1926): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524295
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5326): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/ActivityManager(  880): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=5379 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5326): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5326): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 5326): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5326): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5326): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5326): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5326): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@20053a0a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5326): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5326): GMSCore installation verified
,I/ConfigStore( 5326): Config Database version: 1
,W/ResourcesManager( 5379): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5379): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5379): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5379): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5379): Installed default security provider GmsCore_OpenSSL
,I/MediaRouter( 5326): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5326): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5326): type=WIFI subType= reason=null isConnected=true
,E/Auth.Api.Credentials( 1926): [CredentialSyncAdapter] Unknown sync event.
,I/NetworkMonitor( 5326): type=WIFI subType= reason=null isConnected=true
,E/YouTube MDX( 5379): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5421 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5379): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/MMApiWSBase( 2556): doRequest(): v1/gns/list/messages resp length: 1363
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ResourcesManager( 5379): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ContextImpl( 5379): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/ Nonce  ( 2556):  Nonce Reponse 
D/        ( 2556): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"071d3114-a78d-43dc-ad6c-c11e294119d1"}
,D/MMApiWSBase( 2556): doRequest(): /v1/gdi/nonce.json resp length: 61
,D/CCE     ( 2556): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,I/ Nonce  ( 2556):  Nonce Handle Reponse 
,D/MMApiProvisionService( 2556): mOutstandingReq set to false
,I/GHttpClientFactory( 5326): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/CCE     ( 2556): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/GoogleURLConnFactory( 5326): Using platform SSLCertificateSocketFactory
,D/Checkin ( 2556): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 2556): handleGetNotificationsResponse(): got 0; more=false
,V/Mms     ( 5421): mnc/mcc: 
,V/Mms     ( 5421): tag: int value: recipientLimit - 20
V/Mms     ( 5421): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 5421): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 5421): tag: int value: maxSubjectLength - 80
V/Mms     ( 5421): tag: bool value: smsForceShowEncodingMenu - true
D/MMApiProvisionService( 2556):  pTime 1449671329422 sExp 172742 cTime 1449746331850 tTime 1449844071422
D/MMApiProvisionService( 2556):  No login Required 
V/Mms     ( 5421): tag: bool value: enableGroupMms - false
V/Mms     ( 5421):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/dex2oat ( 5454): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1019644407.jar --oat-fd=38 --oat-location=/data/data/com.google.android.youtube/cache/ads-1019644407.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ResourcesManager( 5421): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5465 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5379): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5379): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5379): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 5379): Found 10016
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5379): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,D/PhoneMonitor( 5465): Register our PhoneStateListener
,I/art     ( 1538): Explicit concurrent mark sweep GC freed 30016(1929KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.275ms total 93.574ms
,I/dex2oat ( 5454): dex2oat took 239.913ms (threads: 4)
,W/DataUsage( 2556): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/art     (  880): Explicit concurrent mark sweep GC freed 19249(859KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.596ms total 141.506ms
,D/MobileConnectivityChangeReceiver( 5465): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5465): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 4906:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_4906/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 4935:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_4935/cgroup.procs: No such file or directory
,I/CheckinService( 1926): Checkin interval check for package: unspecified last checkin: 1449704369208 min interval config: 0 actual interval: 41963445
,I/CheckinService( 1926): Checking schedule, now: 1449746332675 next: 1449704399193
I/CheckinService( 1926): active receiver: enabled
,I/iu.SyncManager( 1926): SYNC; picasa accounts
,D/NetworkLogImpl( 1926): Loaded NetworkSpeedPredictor
,I/CheckinService( 1926): Preparing to send checkin request
I/EventLogService( 1926): Accumulating logs since 1449746189853
,W/DataUsage( 2556): invalid counter update blocked: 'err' by 0
D/Checkin ( 2556): publish the event [tag = MOT_CCE event name = LOG]
,I/iu.Environment( 1926): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1926): num queued entries: 0
,I/iu.UploadsManager( 1926): num updated entries: 0
,I/iu.SyncManager( 1926): NEXT; no task
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=5518 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=5543 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/MDMCTBK (  298): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  298): NetlinkHandler, interfaceAdded
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
E/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  298): , Wifi = 1
I/MDMCTBK (  298): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
,I/MDMCTBK (  298): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  298): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): get_property_value, Enter
I/MDMCTBK (  298): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  298): get_property_value, Exit
I/MDMCTBK (  298): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1202496240
I/MDMCTBK (  298): return from set_get_from_wpa_supplicant
I/MDMCTBK (  298): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  298): set_property_value, Enter
D/MDMCTBK (  298): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  298): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  298): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  298): , reply_len: 3, ret: 0
E/MDMCTBK (  298): MdmCutbackHndler, resp=OK
E/MDMCTBK (  298): 
D/MDMCTBK (  298): wifi_set_tx_pwr: Exit
I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,I/MDMCTBK (  298): send SAR ctrl over QMI
,W/ResourcesManager( 5518): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 1926): Checkin reason type: 8 attempt count: 1
,D/WifiService(  880): New client listening to asynchronous messages
,E/ActivityThread( 1926): Failed to find provider info for com.google.android.wearable.settings
,I/GCM     ( 1689): GCM config loaded
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=293, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309929, SEQNUM=4403, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-16927, POWER_SUPPLY_CHARGE_COUNTER=-632, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5103): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5103): Disconnected process message: 10, size: 0
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5590 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  880): Killing 5149:com.android.settings/1000 (adj 15): empty #7
,I/ActivityManager(  880): Killing 5198:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_1000/pid_5149/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_5198/cgroup.procs: No such file or directory
,W/ResourcesManager( 5590): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/art     ( 5518): Attempt to remove local handle scope entry from IRT, ignoring
,I/Babel_SMS( 5590): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5590): MmsConfig.loadMmsSettings
I/Babel_SMS( 5590): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5590): MmsConfig.loadFromDatabase
,I/VacuumService( 1689): Vacuum at: now=1449746334545 tag=VacuumService
,E/Babel_SMS( 5590): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5590): MmsConfig.loadFromResources
,E/Babel_SMS( 5590): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5590): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 5590): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5590): startup - clean
,I/Babel   ( 5590): deleted: false for 0
,I/art     ( 3910): Explicit concurrent mark sweep GC freed 1777(80KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 856us total 54.364ms
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5639 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PhenotypeConfigurator( 1689): Scheduling Phenotype for one-off execution 5719 seconds from now (1449746334966)
,D/GetConfigurationSnapshotOperation( 1689): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,W/VideoCapabilities( 5590): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5590): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5590): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5590): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5590): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5590): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5590): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5660 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/VideoCapabilities( 5590): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5590): onServiceConnected
W/Babel   ( 5590): Attempted to change video mute state without an active call.
,W/ResourcesManager( 5660): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5660): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel   ( 5590): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 5326:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/MultiDex( 5660): VM with version 2.1.0 has multidex support
I/MultiDex( 5660): install
I/MultiDex( 5660): VM has multidex support, MultiDex support library is disabled.
,I/jxcore-log( 5052): Test app app.js loaded
I/jxcore-log( 5052): 
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_5326/cgroup.procs: No such file or directory
,I/chromium( 5052): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/JNIHelp ( 5660): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5639): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5639): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5639): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5639): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
W/ActivityThread( 5660): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5660): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@335d7a23: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5660): Installed default security provider GmsCore_OpenSSL
,I/GAv4    ( 5639): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5639):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5639):   adb logcat -s GAv4
,W/GAv4    ( 5639): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 5660): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5660): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/GAv4    ( 5639): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5639): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  880): Explicit concurrent mark sweep GC freed 25065(1082KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.794ms total 128.743ms
,I/PhenotypeFlagCommitter( 1689): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
D/NativeLibraryUtils( 5660): Install completed successfully. count=14 extracted=0
,I/GoogleURLConnFactory( 1689): Using platform SSLCertificateSocketFactory
,D/WVCdm   (  300): Instantiating CDM.
,I/WVCdm   (  300): CdmEngine::OpenSession
I/WVCdm   (  300): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  300): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  300): Service_Initialize: starts!
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,E/QSEECOMAPI: (  300): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,E/QSEECOMAPI: (  300): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,D/QSEECOMAPI: (  300): Loaded image: APP id = 3
,D/DrmWidevineDash(  300): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fd3000
E/DrmWidevineDash(  300): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fd3000
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: starts!
,I/GoogleURLConnFactory( 5660): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  300): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: starts! SID=0xb54a1960
,D/DrmWidevineDash(  300): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: starts! randomData=0xb8cf97c8, dataLength=8
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8ba95a8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  300): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  300): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  300): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  300): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: starts! deviceID=0xb8cf5780, idLength=0xbedb12b0
,D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  300): PrepareKeyRequest: nonce=3341659243
D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8c9c670
D/DrmWidevineDash(  300): message_length=1591, signature=0xb8bac240, signature_length=3202028180
,I/WebViewFactory( 5639): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5639): Time to load native libraries: 2 ms (timestamps 5189-5191)
I/LibraryLoader( 5639): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5639): Binding Chromium to main looper Looper (main, tid 1) {3cb13213}
,I/LibraryLoader( 5639): Expected native library version number "",actual native library version number ""
,I/chromium( 5639): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5639): Initializing chromium process, singleProcess=true
W/art     ( 5639): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5639): ApplicationContext is null in ApplicationStatus
,W/chromium( 5639): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5639): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5639): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5639): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5639): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5639): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5639): Local Branch: 
I/Adreno-EGL( 5639): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5639): Local Patches: NONE
I/Adreno-EGL( 5639): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  300): CdmEngine::CloseSession
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  300): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  300): L3 Terminate.
D/DrmWidevineDash(  300): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  300): Service_Uninitialize: starts!
D/QSEECOMAPI: (  300): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  300): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  300): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  300): OEMCrypto_Terminate: ends! returns 0
,W/AudioManagerAndroid( 5639): Requires BLUETOOTH permission
,I/NSApplication( 5639): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5740 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 5379:com.google.android.youtube/u0a101 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10101/pid_5379/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 5421:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_5421/cgroup.procs: No such file or directory
,I/dex2oat ( 5766): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=33 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=5783 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/art     (  315): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 22.490ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 21.480ms
,I/dex2oat ( 5766): dex2oat took 106.768ms (threads: 4)
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.348ms
,I/Adreno-EGL( 5660): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5660): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5660): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5660): Local Branch: 
I/Adreno-EGL( 5660): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5660): Local Patches: NONE
I/Adreno-EGL( 5660): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ResourcesManager( 5783): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=5807 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Adreno-EGL( 5660): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5660): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5660): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5660): Local Branch: 
I/Adreno-EGL( 5660): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5660): Local Patches: NONE
I/Adreno-EGL( 5660): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  880): Killing 5465:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ActivityManager(  880): Killing 5543:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_5543/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_5465/cgroup.procs: No such file or directory
,E/SQLiteLog( 5807): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/Adreno-EGL( 5660): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5660): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5660): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5660): Local Branch: 
I/Adreno-EGL( 5660): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5660): Local Patches: NONE
I/Adreno-EGL( 5660): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:33000 mC
,I/Adreno-EGL( 5660): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5660): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5660): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5660): Local Branch: 
I/Adreno-EGL( 5660): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5660): Local Patches: NONE
I/Adreno-EGL( 5660): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5842 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WVCdm   (  300): Instantiating CDM.
,I/WVCdm   (  300): CdmEngine::OpenSession
I/WVCdm   (  300): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  300): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/ResourcesManager( 5842): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  300): Service_Initialize: starts!
,D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
E/QSEECOMAPI: (  300): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  300): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  300): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  300): App is not loaded in QSEE
,D/QSEECOMAPI: (  300): Loaded image: APP id = 3
,D/DrmWidevineDash(  300): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fc6000
E/DrmWidevineDash(  300): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fc6000
,D/DrmWidevineDash(  300): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: starts!
,I/AnalyticsLogBase( 5807): PlayLogger.onLoggerConnected
,D/DrmWidevineDash(  300): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  300): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  300): OEMCrypto_OpenSession: starts! SID=0xb13dc960
D/DrmWidevineDash(  300): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  300): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: starts! randomData=0xb8cf91c8, dataLength=8
D/DrmWidevineDash(  300): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8bc6aa0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  300): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  300): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  300): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  300): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  300): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: starts! deviceID=0xb8cf57c0, idLength=0xb54a1730
,D/DrmWidevineDash(  300): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  300): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  300): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  300): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  300): hlos api version =  9
D/DrmWidevineDash(  300): tz api version =  8
D/DrmWidevineDash(  300): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  300): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  300): PrepareKeyRequest: nonce=3231978856
D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8bab978
D/DrmWidevineDash(  300): message_length=1626, signature=0xb8c9cba0, signature_length=3041531668
,I/ActivityManager(  880): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5865 uid=10096 gids={50096, 9997} abi=armeabi-v7a
I/ActivityManager(  880): Killing 5639:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/DrmWidevineDash(  300): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  300): CdmEngine::CloseSession
D/DrmWidevineDash(  300): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  300): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  300): L3 Terminate.
D/DrmWidevineDash(  300): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  300): Service_Uninitialize: starts!
D/QSEECOMAPI: (  300): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  300): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  300): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  300): OEMCrypto_Terminate: ends! returns 0
,E/libprocessgroup(  880): failed to kill 1 processes for processgroup 5639
I/ActivityManager(  880): Killing 5590:com.google.android.talk/u0a70 (adj 15): empty #8
,I/CalendarProvider2( 5842): Created com.android.providers.calendar.CalendarAlarmManager@304e8f90(com.android.providers.calendar.CalendarProvider2@1a913089)
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_5590/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 1926): Classify the device as Phone.
,I/System.out( 5865): TimeService: Loaded Library 
D/TimeService( 5865): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449746338184
D/        ( 5865): TimeServiceNative: User Time to be set is 1449746338185
D/QC-time-services( 5865): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5865): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5865): Lib:time_genoff_operation: pargs->ts_val = 1449746338185
D/QC-time-services( 5865): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  322): Daemon: Connection accepted:time_genoff
D/QC-time-services(  322): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449746338185
,D/QC-time-services(  322): Daemon:genoff_opr: Base = 2, val = 1449746338185, operation = 0
D/QC-time-services(  322): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/10/115 11:17:43
D/QC-time-services(  322): Daemon:Value read from RTC seconds = 1449746263000
D/QC-time-services(  322): Daemon:new time 1449746338185 
D/QC-time-services(  322): Daemon: delta 75185 genoff 75185 
D/QC-time-services(  322): Daemon:genoff_persistent_update: Writing genoff = 75185 to memory
D/QC-time-services(  322): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  322): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  322): Updating the TOD offset
D/QC-time-services(  322): Daemon:genoff_persistent_update: Writing genoff = 75185 to memory
,D/QC-time-services(  322): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  322): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  322): Daemon:Update to modem bit set
D/QC-time-services(  322): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 5865): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  322): Daemon: Base = 2, Value being sent to MODEM = 18446743757744826801
,E/QC-time-services(  322): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  322): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1926): Checkin interval check for package: unspecified last checkin: 1449704369208 min interval config: 0 actual interval: 41969003
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=5897 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/CheckinTask( 1926): Sending checkin request (9760 bytes)
,I/GAv4    ( 5897): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5897):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5897):   adb logcat -s GAv4
,W/GAv4    ( 5897): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5897): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5897): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  880): Killing 5740:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_5740/cgroup.procs: No such file or directory
,V/AlarmManager(  880): done {24cc91fe, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [8533ms]
,D/EmailService.MarketingOptInSetter( 2556): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 2556): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,E/SQLiteLog( 2556): (284) automatic index on registration(APP_ID)
,D/WaitableIntentService( 2556): ServiceHandler.handleMessage: mWaitCount=1
,I/PushService( 2556): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2556): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2556): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2556): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2556): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2556): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2556): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2556): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2556): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2556): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2556): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2556): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2556): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2556): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2556): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2556): publish the event [tag = MOT_OTA event name = LOG]
,I/CheckinResponseProcessor( 1926): From server: 1 gservices updates and 1 deletes
,W/IInputConnectionWrapper( 5052): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1406): onFinishInput()
,I/SundryService( 2556): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 2556): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
,D/SundryService( 2556): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 2556): ServiceHandler.handleMessage: mWaitCount=0
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5929 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/GetNotificationsWS( 2556): unbindWebServices(): un-registering our AIDL callback...
,I/LaunchCheckinHandler(  880): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,212
,W/ResourcesManager( 5929): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CertBlacklister(  880): Certificate blacklist changed, updating...
,I/GservicesProvider( 3910): main difference update completed
,I/CheckinRequestBuilder( 1926): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1926): Failed to find provider info for com.google.android.wearable.settings
,I/CertBlacklister(  880): Certificate blacklist updated
,I/art     ( 1926): Explicit concurrent mark sweep GC freed 28146(2025KB) AllocSpace objects, 33(528KB) LOS objects, 24% free, 14MB/19MB, paused 1.170ms total 115.886ms
,I/Babel_SMS( 5929): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5929): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5929): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5929): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5929): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5929): MmsConfig.loadFromResources
,E/Babel_SMS( 5929): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5929): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/CalendarProvider2( 5842): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5842): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/art     ( 1689): Explicit concurrent mark sweep GC freed 102211(5MB) AllocSpace objects, 40(663KB) LOS objects, 40% free, 14MB/24MB, paused 1.430ms total 202.444ms
,W/Settings( 5929): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5929): startup - clean
,I/Babel   ( 5929): deleted: false for 0
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3a7766d)
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19b0d2a2)
,E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1bc33b33)
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@a9beef0)
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4d20c69)
,W/art     ( 5929): Suspending all threads took: 6.319ms
,I/art     ( 3910): Explicit concurrent mark sweep GC freed 8730(433KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 857us total 26.928ms
,I/ActivityManager(  880): Killing 5783:com.motorola.context/u0a8 (adj 15): empty #7
,I/CheckinRequestBuilder( 1926): Classify the device as Phone.
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_5783/cgroup.procs: No such file or directory
,W/VideoCapabilities( 5929): Unrecognized profile 2130706433 for video/avc
I/CheckinTask( 1926): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/AudioCapabilities( 5929): Unsupported mime audio/amr-wb-plus
,I/CheckinService( 1926): Checking schedule, now: 1449746339547 next: 1450347476536
I/CheckinService( 1926): active receiver: disabled
,W/VideoCapabilities( 5929): Unsupported mime video/mpeg2
,D/CheckinService( 1926): Recording last checkin time for package unspecified as 1449746339566
,I/VideoCapabilities( 5929): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5929): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5929): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5929): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5929): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Killing 5518:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/vclib   ( 5929): onServiceConnected
,W/Babel   ( 5929): Attempted to change video mute state without an active call.
,I/ActivityManager(  880): Killing 5865:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,I/ActivityManager(  880): Killing 5807:com.google.android.calendar/u0a49 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_5518/cgroup.procs: No such file or directory
,I/art     (  880): Explicit concurrent mark sweep GC freed 18771(878KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.554ms total 149.184ms
,W/libprocessgroup(  880): failed to open /acct/uid_10096/pid_5865/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10049/pid_5807/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=5968 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/LocationInitializer( 1926): Restart initialization of location
,D/WearableService( 1689): callingUid 10016, callindPid: 1689
,D/AuthorizationBluetoothService( 1689): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/MDM     ( 1689): [159] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ActivityManager(  880): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.WidgetDataReceiver: pid=6009 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1689): No location to return for getLastLocation()
,W/FusedLocationProvider( 1689): location=null
,E/SQLiteLog( 6009): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/AnalyticsLogBase( 6009): PlayLogger.onLoggerConnected
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6034 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6061 uid=10054 gids={50054, 9997, 3003} abi=armeabi-v7a
,E/UpdateRequestReceiver( 6061): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6061): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6061): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6061): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/CheckinService( 1926): Checkin interval check for package: unspecified last checkin: 1449746339566 min interval config: 0 actual interval: 1590
,I/SystemUpdateService( 1926): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
I/CheckinService( 1926): Checking schedule, now: 1449746341176 next: 1450347476536
I/CheckinService( 1926): active receiver: disabled
,D/SystemUpdateService( 1926): onCreate
,D/SystemUpdateService( 1926): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1926): cancelUpdate (empty URL)
I/SystemUpdateService( 1926): active receiver: disabled
,I/ActivityManager(  880): Killing 5897:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10055/pid_5897/cgroup.procs: No such file or directory
,I/art     ( 3910): Explicit concurrent mark sweep GC freed 4045(171KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 854us total 34.905ms
,I/art     ( 1926): Explicit concurrent mark sweep GC freed 10038(570KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 14MB/24MB, paused 1.172ms total 78.016ms
,W/SQLiteConnectionPool( 1926): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/art     ( 3910): Explicit concurrent mark sweep GC freed 2480(96KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 656us total 22.709ms
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
,I/ActivityManager(  880): Killing 5929:com.google.android.talk/u0a70 (adj 15): empty #7
,D/SystemUpdateService( 1926): onDestroy
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_5929/cgroup.procs: No such file or directory
,E/DynamiteModule( 1926): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1926): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 1926): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1926): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 1926): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 1926): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1926): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1926): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1926): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1926): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1926): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1926): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2611)
E/DynamiteModule( 1926): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/DynamiteModule( 1926): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1369)
E/DynamiteModule( 1926): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1926): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 1926): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/DynamiteModule( 1926): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 1926): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 1926): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/DynamiteModule( 1926): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/DynamiteModule( 1926): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 1926): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 1926): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 1926): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 1926): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 1926): 		... 17 more
E/DynamiteModule( 1926): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,I/DynamiteModule( 1926): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 1926): Selected local version of com.google.android.gms.flags
,D/SystemEventReceiver( 1926): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1926): Updating ocr activity enabled=false
,W/ActivityManager(  880): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1926): Updating downloaded model state (gservices changed)
,I/art     ( 1689): Explicit concurrent mark sweep GC freed 42671(2MB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 13MB/23MB, paused 1.116ms total 82.076ms
,I/art     ( 3910): Explicit concurrent mark sweep GC freed 2775(109KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 725us total 24.735ms
,D/GCM     ( 1689): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GCoreUlr( 1689): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1689): DispatchingService.onCreate()
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=6131 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/GCoreUlr( 1689): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GeofencerStateMachine( 1689): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1689): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,W/ctxmgr  ( 1689): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10016, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1689): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1538): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GCoreUlr( 1689): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1689): Unbound from all location providers
I/GCoreUlr( 1689): Place inference reporting - stopped
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/art     (  880): Explicit concurrent mark sweep GC freed 21243(1081KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 4.696ms total 150.973ms
,I/Launcher( 1555): Deferring update until onResume
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@388d2534
,I/GCoreNlp( 1689): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/GservicesUpdateTask( 6131): Updating Gservices keys
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6180 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6009:com.google.android.calendar/u0a49 (adj 15): empty #7
I/art     (  315): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 25.190ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 20.824ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.721ms
,W/libprocessgroup(  880): failed to open /acct/uid_10049/pid_6009/cgroup.procs: No such file or directory
,I/GCoreUlr( 1689): DispatchingService.onDestroy()
I/GCoreUlr( 1689): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1689): Unbound from all location providers
I/GCoreUlr( 1689): Place inference reporting - stopped
,W/ResourcesManager( 6180): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/art     ( 3910): Explicit concurrent mark sweep GC freed 2706(105KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 637us total 27.501ms
,I/ActivityManager(  880): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=6199 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 5842:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_5842/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 6061:com.google.android.configupdater/u0a54 (adj 15): empty #7
,E/SQLiteLog( 6199): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,W/libprocessgroup(  880): failed to open /acct/uid_10054/pid_6061/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6222 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6222): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AnalyticsLogBase( 6199): PlayLogger.onLoggerConnected
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6243 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/CalendarProvider2( 6222): Created com.android.providers.calendar.CalendarAlarmManager@304e8f90(com.android.providers.calendar.CalendarProvider2@1a913089)
,D/PhoneMonitor( 6243): Register our PhoneStateListener
,V/SetupWizard( 6243): Connected to Gservices successfully
,I/ActivityManager(  880): Killing 5660:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_5660/cgroup.procs: No such file or directory
,D/GCM     ( 1689): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1689): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6263 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6263): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6263): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6263): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6263): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6263): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6263): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6263): MmsConfig.loadFromResources
,E/Babel_SMS( 6263): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6263): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6263): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6263): startup - clean
,I/Babel   ( 6263): deleted: false for 0
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6295 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6263): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6263): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6263): Unsupported mime video/mpeg2
,W/asset   ( 6295): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 6295): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6295): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6295): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 6263): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6263): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6263): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6263): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6263): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 1926): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1926): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 6131): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/Icing   ( 1926): updateResources: need to parse f{com.google.android.gms}
,W/Launcher( 1555): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@159cc0a8 new=com.google.android.velvet.VelvetApplication@159cc0a8
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6326 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CalendarProvider2( 6222): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6222): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  880): Killing 6034:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/vclib   ( 6263): onServiceConnected
W/Babel   ( 6263): Attempted to change video mute state without an active call.
,W/ResourcesManager( 6263): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6263): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 6131): UpdateCorporaTask done [took 173 ms] updated apps [took 173 ms] 
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_6034/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 5968:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/ResourcesManager( 6326): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 6263): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 6263): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6263): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_5968/cgroup.procs: No such file or directory
,I/art     ( 1689): Explicit concurrent mark sweep GC freed 21710(1244KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 14MB/23MB, paused 1.086ms total 73.618ms
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6353 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6180:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_6180/cgroup.procs: No such file or directory
,D/Finsky  ( 6353): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6353): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6353): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6353): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 6353): Skipping gmscore version check
,D/Finsky  ( 6353): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6353): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6353): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/art     (  880): Explicit concurrent mark sweep GC freed 16027(825KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.482ms total 114.402ms
,I/ActivityManager(  880): Killing 6222:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_6222/cgroup.procs: No such file or directory
,D/Finsky  ( 6353): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6406 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6423 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6406): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/ResourcesManager( 6423): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Icing   ( 1926): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/CalendarProvider2( 6423): Created com.android.providers.calendar.CalendarAlarmManager@304e8f90(com.android.providers.calendar.CalendarProvider2@1a913089)
,I/ActivityManager(  880): Killing 6243:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,D/Icing   ( 1926): Loaded CLD2 Version V2.0 - 20141016
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_6243/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 6295:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,I/Icing   ( 1926): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_6295/cgroup.procs: No such file or directory
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:34000 mC
,I/CalendarProvider2( 6423): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6423): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  880): Killing 6131:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_6131/cgroup.procs: No such file or directory
,W/ContextImpl( 6199): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 6199): Thread[GAThread,5,main]: No campaign data found.
,W/PackageSettings(  880): Skipping PackageSetting{32b6a847 com.example.hello/10359} due to missing metadata
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=303, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310016, SEQNUM=4448, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-696, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5103): Disconnected process message: 10, size: 0
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:33000 mC
,I/ActivityManager(  880): Waited long enough for: ServiceRecord{c42f8ff u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/ActivityManager(  880): Killing 6326:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  880): Killing 6263:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6326/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6263/cgroup.procs: No such file or directory
,V/AlarmManager(  880): send {151f5ac8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {183b5eea, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {183b5eea, *walarm*:android.content.syncmanager.SYNC_ALARM} [7ms]
,V/AlarmManager(  880): done {151f5ac8, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=289, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310377, SEQNUM=4450, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12019, POWER_SUPPLY_CHARGE_COUNTER=-740, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5103): Disconnected process message: 10, size: 0
,V/AlarmManager(  880): send {3b2ee5db, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  880): done {3b2ee5db, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [72ms]
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  880): send {183b5eea, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {183b5eea, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,E/ActivityThread( 1926): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  880): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 323696, reason: UserStart
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=282, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309988, SEQNUM=4454, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-785, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5103): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5103): Disconnected process message: 10, size: 0
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/Keyboard.Facilitator.LanguageModelFlusher( 1406): run()
I/Keyboard.Facilitator( 1406): flushDynamicLanguageModels()
,I/ConfigService( 1689): onCreate
,I/CheckinRequestBuilder( 1689): Classify the device as Phone.
,I/ConfigService( 1689): onDestroy
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310533, SEQNUM=4456, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-829, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5103): Disconnected process message: 10, size: 0
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  880): send {151f5ac8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {183b5eea, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {183b5eea, *walarm*:android.content.syncmanager.SYNC_ALARM} [10ms]
,V/AlarmManager(  880): done {151f5ac8, *alarm*:android.intent.action.TIME_TICK} [50ms]
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1689): disconnect managed GoogleApiClient
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 5052): Toggling radios to false
I/jxcore-log( 5052): 
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  880): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2773cf8e mBinding = false
,D/BluetoothManagerService(  880): Message: 2
,W/Settings( 1461): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  880): Sending off request.
,D/WifiService(  880): setWifiEnabled: false pid=5052, uid=10374
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothAdapterState( 5103): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 5103): Setting state to 13
I/BluetoothAdapterState( 5103): Bluetooth adapter state changed: 12-> 13
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1461): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/BluetoothAdapterProperties( 5103): onBluetoothDisable()
I/BluetoothAdapterState( 5103): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 5103): Scan Mode:20
,D/BluetoothAdapterState( 5103): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/BtOppRfcommListener( 5103): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,V/BluetoothMapMasInstance( 5103): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 5103): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 5103): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
V/BluetoothMapMasInstance( 5103): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
V/BluetoothMapMasInstance( 5103): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
V/BluetoothMapMasInstance( 5103): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 5103): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 5103): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,W/bt-btif ( 5103): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/btif_config_util( 5103): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 5103): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5103): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  880): Message: 60
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  880): Bluetooth State Change Intent: 12 -> 13
,E/WifiStateMachine(  880): WifiStateMachine: Leaving Connected state
,D/BluetoothMapService( 5103): onReceive
D/BluetoothMapService( 5103): STATE_TURNING_OFF
D/BluetoothMapService( 5103): MAP Service closeService in
D/BluetoothMapMasInstance( 5103): MAP Service shutdown
,I/BtOppRfcommListener( 5103): stopping Accept Thread
,I/BtOppRfcommListener( 5103): BluetoothSocket listen thread finished
,I/jxcore-log( 5052): Radios toggled
I/jxcore-log( 5052): 
W/Settings( 1461): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  880): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
,I/ActivityManager(  880): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6517 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,W/Settings( 1461): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  296): Clearing all IP addresses on wlan0
D/TCMD    (  465): NL - Read 60 bytes from update socket.
D/TCMD    (  465): NL - ignore NL message, type = 21
D/TCMD    (  465): Listening for incoming client connection request
,V/NativeCrypto( 1689): Read error: ssl=0xb81a9f78: I/O error during system call, Connection timed out
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info<unknown ssid>
,V/NativeCrypto( 1689): SSL shutdown failed: ssl=0xb81a9f78: I/O error during system call, Broken pipe
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
D/WifiMetrics(  880): connected time updated 245522
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/ConnectivityService(  880): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 5146): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 5146): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  880): [1,449,746,572,426 ms] noteScanEnd no scan source
D/WifiP2pService(  880): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  880): SCAN_AVAILABLE : 1
,D/RttService(  880): SCAN_AVAILABLE : 1
D/WifiP2pService(  880): P2pDisablingState
D/WifiScanningService(  880): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): p2p socket connection lost
D/RttService(  880): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pDisabledState
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  880): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - enter - invokeEnterMethods
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  880): do suspend true
,W/bt-btif ( 5103): ag scb idx 1 not allocated
E/bt-btif ( 5103): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 5103): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5103): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5103): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5103): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 5103): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5103): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_userial_mct( 5103): exiting userial_read_thread
D/bt_userial_mct( 5103): Leaving userial_evt_read_thread()
D/bt_userial_mct( 5103): userial_close_reader Joined userial reader thread: 0
I/bt_hwcfg( 5103): hw_epilog_process
D/bt_userial_mct( 5103): userial_close
,W/ResourcesManager( 6517): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ContextImpl( 6517): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiP2pService(  880): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/AuthorizationBluetoothService( 1689): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a61569a:true
,D/BluetoothManagerService(  880): Message: 30
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6542 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  315): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.128ms
,I/bt_hwcfg( 5103): Starting hciattach daemon
I/bt_hwcfg( 5103): try to set false
,I/bt_vendor( 5103): cleanup
,I/GKI_LINUX( 5103): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 5103): GKI_exit_task 0 done
I/GKI_LINUX( 5103): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 5103): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 5103): mProfilesStarted : true supportedProfileServices.length : 7
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.038ms
,D/BluetoothManagerService(  880): Message: 30
,D/HeadsetService( 5103): Received stop request...Stopping profile...
,D/CommandListener(  296): Clearing all IP addresses on wlan0
,D/ConnectivityService(  880): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524292
,D/HeadsetStateMachine( 5103): quit
D/Nat464Xlat(  880): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  880): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
D/HeadsetStateMachine( 5103): Exit Disconnected: -1
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1520): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Disconnected - quitting
I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 20.405ms
D/BluetoothHeadset( 1502): Proxy object disconnected
,D/BluetoothHeadset( 1538): Proxy object disconnected
D/BluetoothHeadset( 1502): Proxy object disconnected
D/HeadsetStateMachine( 5103): Unbinding service...
,D/ConnectivityService(  880): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/ModemStatsDSDetect( 1520): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/BluetoothHeadset(  880): Proxy object disconnected
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/BluetoothHeadsetServiceJni( 5103): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 5103): Cleaning up Bluetooth Handsfree callback object
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/AudioService(  880): onServiceDisconnected: Bluetooth profile: 1
,E/WifiStateMachine(  880): stopping supplicant
,E/WifiStateMachine(  880): setWifiState: disabling
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/A2dpService( 5103): Received stop request...Stopping profile...
,D/A2dpStateMachine( 5103): Exit Disconnected: -1
,E/ConnectivityService(  880): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
,I/ModemStatsDSDetect( 1520): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1520): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1926): CM callback handler got msg 524292
I/ModemStatsDSDetect( 1520): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1520): onReceive() - done, currentInetCondition=0
D/HidService( 5103): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
,D/HealthService( 5103): Received stop request...Stopping profile...
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/LocalBluetoothProfileManager( 6517): Adding local MAP profile
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/PanService( 5103): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/BluetoothAdapterState( 5103): Stopping profile services that were post enabled
,D/BluetoothMap( 6517): Create BluetoothMap proxy object
D/BluetoothManagerService(  880): Message: 30
,I/GKI_LINUX( 5103): gki_task task_id=2 [A2DP-MEDIA] terminating
,D/BluetoothA2dp(  880): Proxy object disconnected
D/AudioService(  880): onServiceDisconnected: Bluetooth profile: 2
I/GKI_LINUX( 5103): GKI_exit_task 2 done
I/GKI_LINUX( 5103): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BtGatt.DebugUtils( 5103): handleDebugAction() action=null
D/BtGatt.GattService( 5103): Received stop request...Stopping profile...
D/BtGatt.GattService( 5103): stop()
D/BtGatt.AdvertiseManager( 5103): advertise clients cleared
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/wpa_supplicant( 5146): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  298): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  298):  STA Disconnected !!
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): get_property_value, Enter
I/MDMCTBK (  298): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  298): get_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
,I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  298): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  298): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
,I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
W/BluetoothHidServiceJni( 5103): Cleaning up Bluetooth HID Interface...
,D/Tethering(  880): InitialState.processMessage what=4
,W/bt-btif ( 5103): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5103): Cleaning up Bluetooth GID callback object
,D/BluetoothMapService( 5103): Received stop request...Stopping profile...
,D/BluetoothMapService( 5103): stop()
I/MDMCTBK (  298): send SAR ctrl over QMI
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  298): Event received = CTRL-EVENT-STATE-CHANGE 
,D/BluetoothMapEmailAppObserver( 5103): deinitObservers()
D/BluetoothMapEmailAppObserver( 5103): removeReceiver()
D/BluetoothAdapterService( 5103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f91988e
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/BluetoothHealthServiceJni( 5103): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 5103): Cleaning up Bluetooth Health object
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
W/BluetoothPanServiceJni( 5103): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5103): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 5103): MAP Service closeService in
D/BluetoothMapService( 5103): cleanup()
D/BluetoothMapService( 5103): MAP Service closeService in
D/BluetoothAdapterState( 5103): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 5103): Setting state to 10
I/BluetoothAdapterState( 5103): Bluetooth adapter state changed: 13-> 10
,I/BluetoothAdapterState( 5103): Entering OffState
,D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothManagerService(  880): Message: 60
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  880): Broadcasting onBluetoothStateChange(false) to 8 receivers.
D/BluetoothPan( 6517): onBluetoothStateChange on: false
,D/BluetoothHeadset(  880): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1502): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  880): onBluetoothStateChange: up=false
,D/BluetoothMap( 6517): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 6517): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1538): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1502): onBluetoothStateChange: up=false
,D/LocalBluetoothProfileManager( 6517): LocalBluetoothProfileManager construction complete
,D/BluetoothManagerService(  880): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  880): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService(  880): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2773cf8e mBinding = false
,D/BluetoothManagerService(  880): Sending unbind request.
,D/BluetoothManagerService(  880): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1288): 60142877: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1288): 60142877: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1288): 60142877: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  880): Message: 30
,I/GKI_LINUX( 5103): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 5103): GKI_exit_task 1 done
I/GKI_LINUX( 5103): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 5103): cleanupNative: return from cleanup
I/art     ( 5103): System.exit called, status: 0
I/AndroidRuntime( 5103): VM exiting with result code 0, cleanup skipped.
D/DockEventReceiver( 6517): finishStartingService: stopping service
W/ResourcesManager( 6542): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/wpa_supplicant( 5146): eap_proxy Deinitialzed
D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  298): Event received = CTRL-EVENT-BSS-REMOVED 0
I/ActivityManager(  880): Killing 6353:com.android.vending/u0a32 (adj 15): empty #7
,D/BluetoothAdapter( 1689): 87831712: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1689): 87831712: getState() :  mService = null. Returning STATE_OFF
,D/Checkin ( 2969): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2969): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/wpa_supplicant( 5146): wlan0: CTRL-EVENT-TERMINATING 
,D/MDMCTBK (  298): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  298): Event received = CTRL-EVENT-TERMINATING 
,D/MDMCTBK (  298):  Wpa Supplicant Exiting !!
D/MDMCTBK (  298): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  298): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  298): wifi_close_sockets: Exit
E/WifiStateMachine(  880): Supplicant connection lost
,E/QC-QMI  (  435): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  435): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  435): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
,E/QC-QMI  (  435): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
,E/QC-QMI  (  435): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,D/Checkin ( 2969): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2969): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin ( 2969): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/ActivityManager(  880): Process com.android.bluetooth (pid 5103) has died
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_6353/cgroup.procs: No such file or directory
,E/WifiStateMachine(  880): setWifiState: disabled
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 1689): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_SMS( 6542): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6542): MmsConfig.loadMmsSettings
I/Babel_SMS( 6542): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6542): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6542): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6542): MmsConfig.loadFromResources
,E/Babel_SMS( 6542): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6542): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6542): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6542): startup - clean
,I/Babel   ( 6542): deleted: false for 0
,W/ContextImpl( 6517): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ActivityManager(  880): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6589 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/DockEventReceiver( 6517): finishStartingService: stopping service
,D/TCMD    (  465): NL - Read 444 bytes from update socket.
D/TCMD    (  465): NL - ignore NL message, type = 17
D/TCMD    (  465): Listening for incoming client connection request
,W/VideoCapabilities( 6542): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6542): Unsupported mime audio/amr-wb-plus
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK,
D/TCMD    (  465): Listening for incoming client connection request
,W/VideoCapabilities( 6542): Unsupported mime video/mpeg2
,W/ResourcesManager( 6589): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/Checkin ( 2969): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/VideoCapabilities( 6542): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6542): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6542): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6542): Unrecognized profile 2130706433 for video/avc
D/TCMD    (  465): NL - Read 444 bytes from update socket.
D/TCMD    (  465): NL - ignore NL message, type = 17
D/TCMD    (  465): Listening for incoming client connection request
,W/VideoCapabilities( 6542): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Killing 6423:com.android.providers.calendar/u0a5 (adj 15): empty #7
,D/AdapterServiceConfig( 6589): Adding HeadsetService
D/AdapterServiceConfig( 6589): Adding A2dpService
D/AdapterServiceConfig( 6589): Adding HidService
D/AdapterServiceConfig( 6589): Adding HealthService
D/AdapterServiceConfig( 6589): Adding PanService
D/AdapterServiceConfig( 6589): Adding GattService
D/AdapterServiceConfig( 6589): Adding BluetoothMapService
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_6423/cgroup.procs: No such file or directory
I/ActivityManager(  880): Killing 6199:com.google.android.calendar/u0a49 (adj 15): empty #7
,I/vclib   ( 6542): onServiceConnected
,W/Babel   ( 6542): Attempted to change video mute state without an active call.
,D/AuthorizationBluetoothService( 1689): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  880): failed to open /acct/uid_10049/pid_6199/cgroup.procs: No such file or directory
,I/MDMCTBK (  298): NetlinkHandler, wifiStateChanged 0
,I/MDMCTBK (  298): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1461): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2556): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2556): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2556): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2556): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6629 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1461): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1461): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2556): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2556): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2556): Registering with Alarm Manager to restart CCE
,D/PollingManager( 2556): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2556): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2556): [debug] > CusSM.onRadioDown
,D/PollingManager( 2556): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2556): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2556): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2556): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2556): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2556): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2556): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/MusicStore( 6629): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6629): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6629): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6629): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6629): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6629): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6629): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6629): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6629): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@20053a0a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6629): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6629): GMSCore installation verified
,I/ConfigStore( 6629): Config Database version: 1
,I/MediaRouter( 6629): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6629): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6670 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6629): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6629): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 6542:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6542/cgroup.procs: No such file or directory
,V/Mms     ( 6670): mnc/mcc: 
,V/Mms     ( 6670): tag: int value: recipientLimit - 20
V/Mms     ( 6670): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6670): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 6670): tag: int value: maxSubjectLength - 80
V/Mms     ( 6670): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6670): tag: bool value: enableGroupMms - false
,V/Mms     ( 6670):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     (  880): Explicit concurrent mark sweep GC freed 37032(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.486ms total 129.108ms
,W/ResourcesManager( 6670): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6703 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6406:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_6406/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6703): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6703): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6703): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 1926): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ActivityManager(  880): Killing 6517:com.android.settings/1000 (adj 15): empty #7
,I/iu.UploadsManager( 1926): num queued entries: 0
,I/iu.UploadsManager( 1926): num updated entries: 0
I/iu.SyncManager( 1926): NEXT; no task
,W/libprocessgroup(  880): failed to open /acct/uid_1000/pid_6517/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6721 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6738 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6589:com.android.bluetooth/1002 (adj 15): empty #7
,D/WifiP2pService(  880): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,W/libprocessgroup(  880): failed to open /acct/uid_1002/pid_6589/cgroup.procs: No such file or directory
,W/ResourcesManager( 6738): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6738): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6738): MmsConfig.loadMmsSettings
I/Babel_SMS( 6738): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6738): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6738): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6738): MmsConfig.loadFromResources
,E/Babel_SMS( 6738): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6738): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,W/Settings( 6738): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6738): startup - clean
,I/Babel   ( 6738): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6769 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6738): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6738): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6738): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6738): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6738): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6738): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6738): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6738): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6738): onServiceConnected
,W/Babel   ( 6738): Attempted to change video mute state without an active call.
,I/Babel   ( 6738): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  880): Killing 6629:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6769): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6769): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6769):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6769):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6769): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6769): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6769): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_6629/cgroup.procs: No such file or directory
,W/GAv4    ( 6769): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6769): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6769): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6769): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6769): Time to load native libraries: 1 ms (timestamps 7412-7413)
I/LibraryLoader( 6769): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6769): Binding Chromium to main looper Looper (main, tid 1) {148e1a4d}
,I/LibraryLoader( 6769): Expected native library version number "",actual native library version number ""
,I/chromium( 6769): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6769): Initializing chromium process, singleProcess=true
,W/art     ( 6769): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6769): ApplicationContext is null in ApplicationStatus
,W/chromium( 6769): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6769): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6769): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6769): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6769): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6769): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6769): Local Branch: 
I/Adreno-EGL( 6769): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6769): Local Patches: NONE
I/Adreno-EGL( 6769): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 6769): Starting up...
,W/AudioManagerAndroid( 6769): Requires BLUETOOTH permission
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6839 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6670:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_6670/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6858 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6703:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_6703/cgroup.procs: No such file or directory
,W/ResourcesManager( 6858): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Killing 6721:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_6721/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2556): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2556): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2556): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2556): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2556): onServiceConnected()
,D/GetNotificationsWS( 2556): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2556): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6883 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6883): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6883): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6883): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6883): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6883): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6883): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6883): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6883): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6883): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@20053a0a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6883): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6883): GMSCore installation verified
,I/ConfigStore( 6883): Config Database version: 1
,I/MediaRouter( 6883): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6883): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6912 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  315): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 21.557ms
,I/GHttpClientFactory( 6883): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 736us total 21.780ms
,I/GoogleURLConnFactory( 6883): Using platform SSLCertificateSocketFactory
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.966ms
,I/ActivityManager(  880): Killing 6738:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 6912): mnc/mcc: 
V/Mms     ( 6912): tag: int value: recipientLimit - 20
,V/Mms     ( 6912): tag: int value: smsToMmsTextThreshold - 6,
V/Mms     ( 6912): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 6912): tag: int value: maxSubjectLength - 80
V/Mms     ( 6912): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6912): tag: bool value: enableGroupMms - false
V/Mms     ( 6912):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6738/cgroup.procs: No such file or directory
,W/ResourcesManager( 6912): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6946 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6769:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_6769/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6946): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6946): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6946): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 6839:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_6839/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6965 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  880): Explicit concurrent mark sweep GC freed 12992(689KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.431ms total 119.620ms
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6988 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6858:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6858/cgroup.procs: No such file or directory
,W/ResourcesManager( 6988): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6988): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6988): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6988): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6988): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6988): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6988): MmsConfig.loadFromResources
,E/Babel_SMS( 6988): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6988): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6988): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6988): startup - clean
,I/Babel   ( 6988): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7019 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6988): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6988): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6988): Unsupported mime video/mpeg2
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7019): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7019): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7019): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7019):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7019):   adb logcat -s GAv4
,I/VideoCapabilities( 6988): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6988): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6988): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6988): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6988): Unrecognized profile 2130706433 for video/avc
,W/GAv4    ( 7019): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7019): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/vclib   ( 6988): onServiceConnected
,W/Babel   ( 6988): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
I/Babel   ( 6988): connection state changed from UNKNOWN to DISCONNECTED
,W/ContextImpl( 7019): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7019): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  880): Killing 6883:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/GAv4    ( 7019): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_6883/cgroup.procs: No such file or directory
,I/WebViewFactory( 7019): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7019): Time to load native libraries: 1 ms (timestamps 590-591)
I/LibraryLoader( 7019): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7019): Binding Chromium to main looper Looper (main, tid 1) {148e1a4d}
I/LibraryLoader( 7019): Expected native library version number "",actual native library version number ""
,I/chromium( 7019): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7019): Initializing chromium process, singleProcess=true
,W/art     ( 7019): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7019): ApplicationContext is null in ApplicationStatus
,W/chromium( 7019): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7019): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7019): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7019): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7019): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7019): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7019): Local Branch: 
I/Adreno-EGL( 7019): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7019): Local Patches: NONE
I/Adreno-EGL( 7019): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7019): Requires BLUETOOTH permission
,I/NSApplication( 7019): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7088 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6912:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_6912/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7107 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6946:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_6946/cgroup.procs: No such file or directory
,W/ResourcesManager( 7107): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Killing 6988:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6988/cgroup.procs: No such file or directory
,I/MDMCTBK (  298): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  298): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  298): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  298): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  298): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  298): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
E/MDMCTBK (  298): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  298): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  298): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  298): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  298): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  298): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  298): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
I/MDMCTBK (  298): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  298): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  298): set_property_value, Enter
I/MDMCTBK (  298): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  298): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  298): set_property_value, Exit
E/MDMCTBK (  298): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,D/ConnectivityService(  880): Failed to find a new network - expiring NetTransition Wakelock
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310093, SEQNUM=4512, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10717, POWER_SUPPLY_CHARGE_COUNTER=-1769, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {151f5ac8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {b716f59, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {b716f59, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [10ms]
,V/AlarmManager(  880): done {151f5ac8, *alarm*:android.intent.action.TIME_TICK} [47ms]
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {151f5ac8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {b21354a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7155 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  880): done {151f5ac8, *alarm*:android.intent.action.TIME_TICK} [84ms]
,I/GAv4    ( 7155): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7155):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7155):   adb logcat -s GAv4
,W/GAv4    ( 7155): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7155): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7155): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  880): done {b21354a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [188ms]
,I/ActivityManager(  880): Killing 7019:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7019/cgroup.procs: No such file or directory
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=264, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310326, SEQNUM=4520, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310015, SEQNUM=4525, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=20, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310007, SEQNUM=4527, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {151f5ac8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {b716f59, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {b716f59, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [10ms]
,V/AlarmManager(  880): done {151f5ac8, *alarm*:android.intent.action.TIME_TICK} [53ms]
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {151f5ac8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {1c9c6cbb, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  880): done {1c9c6cbb, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [19ms]
,V/AlarmManager(  880): done {151f5ac8, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  311): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7223): 
D/AndroidRuntime( 7223): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7223): CheckJNI is OFF
D/AndroidRuntime( 7223): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10374 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 5052:com.test.thalitest/u0a374 (adj 9): stop com.test.thalitest
W/PackageSettings(  880): Skipping PackageSetting{32b6a847 com.example.hello/10359} due to missing metadata
I/WindowState(  880): WIN DEATH: Window{fa761d1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  880): Client connection lost with reason: 4
I/ActivityManager(  880):   Force finishing activity ActivityRecord{15ce5662 u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  880): Spurious death for ProcessRecord{2dc32d31 5052:com.test.thalitest/u0a374}, curProc for 5052: null
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10374 user=0: pkg removed
I/ActivityManager(  880):   Force finishing activity ActivityRecord{15ce5662 u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  880): Duplicate finish request for ActivityRecord{15ce5662 u0 com.test.thalitest/.MainActivity t3 f}
I/ProcessStatsService(  880): Prepared write state in 22ms
I/ProcessStatsService(  880): Prepared write state in 28ms
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
I/art     ( 2969): Explicit concurrent mark sweep GC freed 15503(2MB) AllocSpace objects, 28(448KB) LOS objects, 39% free, 7MB/12MB, paused 3.427ms total 66.644ms
W/GeofencerStateMachine( 1689): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1406): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1406): run()
I/Decoder ( 1406): createOrResetDecoder
I/art     ( 1555): Explicit concurrent mark sweep GC freed 7747(554KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 552us total 96.540ms
D/VoicemailCleanupService( 2396): Cleaning up data for package: com.test.thalitest
I/art     ( 1926): Explicit concurrent mark sweep GC freed 3979(168KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 14MB/19MB, paused 1.026ms total 121.506ms
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7255 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ConfigService( 1689): onCreate
I/ProcessStatsService(  880): Pruning old procstats: /data/system/procstats/state-2015-12-09-17-16-14.bin
W/asset   ( 7255): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7255): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7255): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7255): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): run()
I/art     (  880): Explicit concurrent mark sweep GC freed 18239(1295KB) AllocSpace objects, 10(214KB) LOS objects, 33% free, 20MB/30MB, paused 4.745ms total 254.034ms
I/art     (  880): WaitForGcToComplete blocked for 253.940ms for cause Explicit
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7279 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = contacts
I/ActivityManager(  880): Killing 1926:com.google.android.gms/u0a16 (adj 15): empty #7
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = user
I/art     (  880): Explicit concurrent mark sweep GC freed 3547(198KB) AllocSpace objects, 1(51KB) LOS objects, 33% free, 20MB/30MB, paused 2.355ms total 126.439ms
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1406): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1406): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1406): run()
I/StatsUtilsManager( 1406): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1406): shouldRecordStats() = Too Soon
D/AndroidRuntime( 7223): Shutting down VM
D/ConnectivityService(  880): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@200c09dd)
D/WifiService(  880): Client connection lost with reason: 4
D/ConnectivityService(  880): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  880): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_1926/cgroup.procs: No such file or directory
D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
I/Launcher( 1555): Deferring update until onResume
W/ContextImpl( 7279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/ActivityManager(  880): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=7297 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
I/ActivityManager(  880): Killing 3910:com.google.process.gapps/u0a16 (adj 15): empty #7
W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_3910/cgroup.procs: No such file or directory
W/ResourcesManager( 7297): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7297): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7297): VM with version 2.1.0 has multidex support
I/MultiDex( 7297): install
I/MultiDex( 7297): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  880): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7320 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
I/art     (  315): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 21.009ms
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.511ms
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.045ms
I/GservicesProvider( 7320): Gservices pushing to system: true; secure/global: true
E/SQLiteDatabase( 7320): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7320): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7320): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7320): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7320): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 7320): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 7320): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 7320): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 7320): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7320): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7320): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7320): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 7320): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7320): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1686)
E/SQLiteDatabase( 7320): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1655)
E/SQLiteDatabase( 7320): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5051)
E/SQLiteDatabase( 7320): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4646)
E/SQLiteDatabase( 7320): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4586)
E/SQLiteDatabase( 7320): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7320): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1353)
E/SQLiteDatabase( 7320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7320): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7320): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/SQLiteDatabase( 7320): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7320): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/SQLiteDatabase( 7320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
D/AndroidRuntime( 7320): Shutting down VM
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
--------- beginning of crash
E/AndroidRuntime( 7320): FATAL EXCEPTION: main
E/AndroidRuntime( 7320): Process: com.google.process.gapps, PID: 7320
E/AndroidRuntime( 7320): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7320): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5054)
E/AndroidRuntime( 7320): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4646)
E/AndroidRuntime( 7320): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4586)
E/AndroidRuntime( 7320): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 7320): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1353)
E/AndroidRuntime( 7320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7320): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7320): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 7320): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7320): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 7320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 7320): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7320): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 7320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 7320): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7320): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 7320): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 7320): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 7320): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 7320): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7320): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7320): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7320): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 7320): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7320): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1686)
E/AndroidRuntime( 7320): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1655)
E/AndroidRuntime( 7320): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5051)
E/AndroidRuntime( 7320): 	... 11 more

```
