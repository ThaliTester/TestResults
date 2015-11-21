#### Test 51335028e20f43b_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 4839): 
D/AndroidRuntime( 4839): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4839): CheckJNI is OFF
D/AndroidRuntime( 4839): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4858 uid=10306 gids={50306, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 4839): Shutting down VM
V/ActivityManager(  882): Display changed displayId=0
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 4858): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4858): Time to load native libraries: 2 ms (timestamps 7509-7511)
I/LibraryLoader( 4858): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4858): Binding Chromium to main looper Looper (main, tid 1) {1a45a237}
,I/LibraryLoader( 4858): Expected native library version number "",actual native library version number ""
I/chromium( 4858): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4858): Initializing chromium process, singleProcess=true
,W/art     ( 4858): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4858): ApplicationContext is null in ApplicationStatus
,W/chromium( 4858): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4858): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4858): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4858): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4858): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4858): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4858): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4858): Local Branch: 
I/Adreno-EGL( 4858): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4858): Local Patches: NONE
I/Adreno-EGL( 4858): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@202e83ce:true
,D/BluetoothAdapter( 4858): 662222352: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  882): Activity pause timeout for ActivityRecord{2cce891b u0 com.test.thalitest/.MainActivity t29}
,W/art     ( 4858): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4858): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4858): CordovaWebView is running on device made by: motorola
,W/art     ( 4858): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 4858): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 4858): Render dirty regions requested: true
,D/Atlas   ( 4858): Validating map...
,W/chromium( 4858): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 4858): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4858): Enabling debug mode 0
,I/Keyboard.Facilitator( 1405): onFinishInput()
,I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,998
I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +928ms (total +998ms)
,W/IInputConnectionWrapper( 4858): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 4858): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4858): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4858): Cannot call determinedVisibility() - never saw a connection for the pid: 4858
,D/JsMessageQueue( 4858): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4858): JniHelper::setJavaVM(0xb8572310), pthread_self() = -1198522784
D/JX-Cordova( 4858): jxcore cordova android initializing
,W/jxcore-log( 4858): Initializing JXcore engine
W/jxcore-log( 4858): JXcore engine is ready
,W/jxcore-log( 4858): Starting JXcore engine
,W/.test.thalitest( 4858): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10306 path="socket:[6750]" dev="sockfs" ino=6750 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 4858): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10306 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 4858): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10306 path="socket:[7537]" dev="sockfs" ino=7537 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 4858): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10306 path="socket:[22002]" dev="sockfs" ino=22002 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4858): Platform android
W/jxcore-log( 4858): 
W/jxcore-log( 4858): Process ARCH arm
W/jxcore-log( 4858): 
,I/jxcore-log( 4858): JXcore Cordova bridge is ready!
I/jxcore-log( 4858): 
W/jxcore-log( 4858): JXcore engine is started
,I/chromium( 4858): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4858): Turning radios to true
I/jxcore-log( 4858): 
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  882): enable():  mBluetooth =null mBinding = false
,W/Settings( 1466): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
D/BluetoothManagerService(  882): Message: 1
D/BluetoothManagerService(  882): MESSAGE_ENABLE: mBluetooth = null
,I/jxcore-log( 4858): toggleBluetooth - 
I/jxcore-log( 4858): 
D/WifiService(  882): New client listening to asynchronous messages
D/WifiService(  882): setWifiEnabled: true pid=4858, uid=10306
E/WifiService(  882): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine(  882): setting operational mode to 1
,I/jxcore-log( 4858): toggleWiFi
I/jxcore-log( 4858): 
,I/ActivityManager(  882): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=4919 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,W/Settings( 1466): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     (  320): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 380us total 25.437ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 19.761ms
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
W/Settings( 1466): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1466): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.053ms
,W/ResourcesManager( 4919): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 4919): Adding HeadsetService
D/AdapterServiceConfig( 4919): Adding A2dpService
D/AdapterServiceConfig( 4919): Adding HidService
D/AdapterServiceConfig( 4919): Adding HealthService
D/AdapterServiceConfig( 4919): Adding PanService
D/AdapterServiceConfig( 4919): Adding GattService
D/AdapterServiceConfig( 4919): Adding BluetoothMapService
,D/Checkin ( 2895): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2895): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@258c5ac4:true
,D/BluetoothAdapterState( 4919): make
,I/bluedroid( 4919): init
I/BluetoothAdapterState( 4919): Entering OffState
,I/bte_conf( 4919): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 4919): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 4919): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 4919): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 4919): get_profile_interface socket
I/bluedroid( 4919): get_profile_interface map_client
,D/BluetoothManagerService(  882): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  882): Message: 40
D/BluetoothManagerService(  882): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/GKI_LINUX( 4919): gki_task_entry task_id=1 [BTIF] starting
,I/bluedroid( 4919): config_hci_snoop_log
D/BluetoothAdapterProperties( 4919): Address is:44:80:EB:7B:5A:05
,D/BluetoothManagerService(  882): Bluetooth Adapter name changed to XT1072
,D/BluetoothManagerService(  882): Stored Bluetooth name: XT1072
D/BluetoothAdapterProperties( 4919): Name is: XT1072
,D/BluetoothManagerService(  882): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  882): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapterState( 4919): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 4919): Setting state to 11
,I/BluetoothAdapterState( 4919): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  882): Message: 60
D/BluetoothManagerService(  882): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  882): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 4919): make
,I/BluetoothBondStateMachine( 4919): StableState(): Entering Off State
,I/ActivityManager(  882): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4960 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TCMD    (  476): NL - Read 1008 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 1008 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  882): InitialState.processMessage what=4
,D/QsoftapCmd(  300): Got softap fwreload command we are passing on
,D/SoftapController(  300): Softap fwReload - Ok
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
,D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
,D/BluetoothHeadset( 1539): Proxy object connected
,D/BluetoothHeadset(  882): Proxy object connected
,D/BluetoothHeadset( 1503): Proxy object connected
D/HeadsetService( 4919): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 4919): classInitNative: succeeds
,I/BluetoothAdapterState( 4919): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetStateMachine( 4919): make
,D/BluetoothHeadset( 1503): Proxy object connected
,D/HeadsetStateMachine( 4919): max_hf_connections = 1
I/bluedroid( 4919): get_profile_interface handsfree
,D/HeadsetStateMachine( 4919): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 4919): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a45a237
,D/CommandListener(  300): Setting iface cfg
D/CommandListener(  300): Trying to bring down wlan0
,D/BluetoothA2dp(  882): Proxy object connected
,D/CommandListener(  300): Clearing all IP addresses on wlan0
D/A2dpService( 4919): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 4919): classInitNative: succeeds
I/bluedroid( 4919): get_profile_interface avrcp
E/WifiStateMachine(  882): setWifiState: enabling
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,E/WifiStateMachine(  882): Supplicant start successful
D/WifiMonitor(  882): startMonitoring(wlan0) with mConnected = false
,E/RemoteController( 4919): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 4919): classInitNative: succeeds
D/A2dpStateMachine( 4919): make
,I/bluedroid( 4919): get_profile_interface a2dp
I/GKI_LINUX( 4919): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 4919): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a45a237
I/BluetoothHidServiceJni( 4919): classInitNative: succeeds
D/A2dpStateMachine( 4919): Enter Disconnected: -2
,D/HidService( 4919): Received start request. Starting profile...
I/bluedroid( 4919): get_profile_interface hidhost
,D/BluetoothAdapterService( 4919): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a45a237
I/BluetoothHealthServiceJni( 4919): classInitNative: succeeds
,D/HealthService( 4919): Received start request. Starting profile...
,W/ResourcesManager( 4960): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/bluedroid( 4919): get_profile_interface health
D/BluetoothAdapterService( 4919): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a45a237
,I/BluetoothPanServiceJni( 4919): classInitNative(L105): succeeds
,D/PanService( 4919): Received start request. Starting profile...
D/BluetoothPanServiceJni( 4919): initializeNative(L110): pan
I/bluedroid( 4919): get_profile_interface pan
,I/art     (  882): Explicit concurrent mark sweep GC freed 16982(864KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 7.337ms total 209.995ms
,I/wpa_supplicant( 4981): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4981): Long line in configuration file truncated
,I/wpa_supplicant( 4981): rfkill: Cannot open RFKILL control device
,D/TCMD    (  476): NL - Read 1004 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,D/BluetoothAdapterService( 4919): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a45a237
,D/TCMD    (  476): NL - Read 1004 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/BtGatt.JNI( 4919): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 4919): handleDebugAction() action=null
,D/BtGatt.GattService( 4919): Received start request. Starting profile...
D/BtGatt.GattService( 4919): start()
I/bluedroid( 4919): get_profile_interface gatt
D/BluetoothAdapterService( 4919): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a45a237
D/BtGatt.AdvertiseManager( 4919): advertise manager created
,D/BluetoothAdapterService( 4919): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a45a237
,D/BluetoothMapService( 4919): Received start request. Starting profile...
D/BluetoothMapService( 4919): start()
,D/BluetoothMapEmailSettingsLoader( 4919): Found 0 applications
D/BluetoothMapEmailAppObserver( 4919): createReceiver()
,D/BluetoothMapEmailAppObserver( 4919): initObservers()
,D/BluetoothMapEmailAppObserver( 4919): getEnabledAccountItems()
,D/BluetoothAdapterService( 4919): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a45a237
,D/HeadsetStateMachine( 4919): Proxy object connected
D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 4919): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
I/libmdmdetect( 4981): ESOC framework not supported
D/HeadsetStateMachine( 4919): Disconnected process message: 11, size: 0
E/Diag_Lib( 4981):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,D/BluetoothAdapterState( 4919): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 4919): enable
,E/wpa_supplicant( 4981): baseband property is set to [msm]
I/libmdmdetect( 4981): ESOC framework not supported
,I/GKI_LINUX( 4919): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 4919): init
,I/bt-btu  ( 4919): btu_task pending for preload complete event
,I/bt_vendor( 4919): bt-vendor : init
D/bt_userial_mct( 4919): userial_init
,I/bt_hwcfg( 4919): Starting hciattach daemon
,I/bt_hwcfg( 4919): try to set false
,I/bt_hwcfg( 4919): Starting hciattach daemon
I/bt_hwcfg( 4919): try to set true
,E/wpa_supplicant( 4981):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 4981): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4981): card_info[i].card_state: 0x0
E/wpa_supplicant( 4981): card_info[i].error_code: 0x0
E/wpa_supplicant( 4981): SIM/USIM not ready
E/wpa_supplicant( 4981): Error while reading SIM card status
,E/wpa_supplicant( 4981): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4981): card_info[i].card_state: 0x0
E/wpa_supplicant( 4981): card_info[i].error_code: 0x0
E/wpa_supplicant( 4981): SIM/USIM not ready
I/wpa_supplicant( 4981): eap_proxy: Card not ready
,I/qcom-bluetooth( 4999): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/ActivityManager(  882): Killing 4683:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/Checkin ( 2895): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2895): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/qcom-bluetooth( 5005): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 5006): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 5008): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5009): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 5010): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/wpa_supplicant( 4981): Line 31: unknown global field 'e'.
,E/wpa_supplicant( 4981): Line 31: Invalid configuration line 'e'.
,I/wpa_supplicant( 4981): rfkill: Cannot open RFKILL control device
D/TCMD    (  476): NL - Read 1004 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_4683/cgroup.procs: No such file or directory
,E/wpa_supplicant( 4981): baseband property is set to [msm]
I/libmdmdetect( 4981): ESOC framework not supported
,E/wpa_supplicant( 4981):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 4981): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4981): card_info[i].card_state: 0x0
,E/wpa_supplicant( 4981): card_info[i].error_code: 0x0
E/wpa_supplicant( 4981): SIM/USIM not ready
E/wpa_supplicant( 4981): Error while reading SIM card status
,E/wpa_supplicant( 4981): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4981): card_info[i].card_state: 0x0
,E/wpa_supplicant( 4981): card_info[i].error_code: 0x0
E/wpa_supplicant( 4981): SIM/USIM not ready
I/wpa_supplicant( 4981): eap_proxy: Card not ready
,I/wpa_supplicant( 4981): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,D/AuthorizationBluetoothService( 1604): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/WifiStateMachine(  882): setSuspendOptimizations: 2 true
E/WifiStateMachine(  882): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  882): Supplicant connection established
E/WifiStateMachine(  882): setWifiState: enabled
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiConfigStore(  882): Loading config and enabling all networks 
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiConfigStore(  882):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  882):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  882): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  882): Setting external_sim to 1
,D/WifiStateMachine(  882): Setting OUI to DA-A1-19
I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2dda89c
D/wifi    (  882): halHandle = 0x0, mVM = 0xb8572310, mCls = 0x1018ee
I/WifiNative-HAL(  882): Could not start hal
,E/WifiStateMachine(  882): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,I/wpa_supplicant( 4981): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 4981): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/wpa_supplicant( 4981): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=5018 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,E/native  (  882): do suspend true
,D/WifiScanningService(  882): SCAN_AVAILABLE : 3
D/RttService(  882): SCAN_AVAILABLE : 3
D/WifiP2pService(  882): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  882): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa19029cc
D/wifi    (  882): halHandle = 0x0, mVM = 0xb8572310, mCls = 0x1018da
I/WifiNative-HAL(  882): Could not start hal
E/WifiScanningService(  882): could not start HAL
D/RttService(  882): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  300): Setting iface cfg
D/CommandListener(  300): Trying to bring up p2p0
,D/WifiMonitor(  882): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  882): P2pEnablingState
D/WifiP2pService(  882): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2p socket connection successful
D/WifiP2pService(  882): P2pEnabledState
D/WifiP2pService(  882): sending p2p connection changed broadcast
,E/WifiStateMachine(  882): set country code US
,E/WifiStateMachine(  882): set frequency band 2
,D/WifiNative-HAL(  882): p2pGetDeviceAddress
,D/WifiNative-HAL(  882): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
D/WifiP2pService(  882): DeviceAddress: 44:80:eb:7b:5a:07
I/wpa_supplicant( 4981): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 4981): wlan0: Failed to initiate AP scan
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/WifiP2pService(  882): MCC mode enabled 0
D/WifiP2pService(  882): mP2pAutoConnectSupport = 0
D/WifiP2pService(  882): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  882): InactiveState
,D/WifiP2pService(  882): InactiveState{ when=-22ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-22ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-24ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-24ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info0x
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/SharedPreferencesImpl(  882): Couldn't create directory for SharedPreferences file shared_prefs/android_preferences.xml
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin ( 2895): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/ResourcesManager( 5018): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/MDMCTBK (  302): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  302): MdmCutbackHndler,wifi, new_state =1
,I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): wifi_connect_to_supplicant, current pid is = 302
,D/MDMCTBK (  302): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  302): wifi_close_sockets: Exit
,E/MDMCTBK (  302): Attach monitor thread
,I/MDMCTBK (  302): createWifiMonitorThread: Started the wifi monitor thread -1195581640
D/MDMCTBK (  302): wifi_wait_on_socket: Enter monitor thread
,I/ActivityManager(  882): Killing 4710:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/Checkin ( 2895): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/libprocessgroup(  882): failed to open /acct/uid_10057/pid_4710/cgroup.procs: No such file or directory
,D/TCMD    (  476): NL - Read 1004 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,D/MDMCTBK (  302): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  302): Event received = WPS-AP-AVAILABLE 
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2dda8fc
D/wifi    (  882): halHandle = 0x0, mVM = 0xb8572310, mCls = 0x101946
I/WifiNative-HAL(  882): Could not start hal
E/WifiStateMachine(  882): [1,448,109,211,943 ms] noteScanEnd no scan source
E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1992f0df sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  882): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  882):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,I/qcom-bluetooth( 5046): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 44:80:eb:7b:5a:05 
,I/qcom-bluetooth( 5047): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 4919): bluetooth satus is on
D/bt_userial_mct( 4919): userial_open(port:0)
,I/bt_userial_vendor( 4919): Done intiailizing UART
,I/bt_userial_vendor( 4919): Done intiailizing UART
I/bt_userial_mct( 4919): CMD=53, EVT=53, ACL_Out=54, ACL_In=54
,I/bt_vendor( 4919): Bluetooth Firmware and smd is initialized
I/bt-btu  ( 4919): btu_task received preload complete event
D/bt_userial_mct( 4919): Entering userial_read_thread()
,I/        ( 4919): BTE_InitTraceLevels -- TRC_HCI
I/        ( 4919): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 4919): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 4919): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 4919): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 4919): BTE_InitTraceLevels -- TRC_A2D
I/        ( 4919): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 4919): BTE_InitTraceLevels -- TRC_BTM
I/        ( 4919): BTE_InitTraceLevels -- TRC_GAP
I/        ( 4919): BTE_InitTraceLevels -- TRC_PAN
I/        ( 4919): BTE_InitTraceLevels -- TRC_SDP
I/        ( 4919): BTE_InitTraceLevels -- TRC_GATT
I/        ( 4919): BTE_InitTraceLevels -- TRC_SMP
I/        ( 4919): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 4919): BTE_InitTraceLevels -- TRC_BTIF
,E/WifiConfigStore(  882): will read network variables netId=0
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  882): will read network variables netId=0
,E/bt-btm  ( 4919): BTM_SecRegister:p_cb_info->p_le_callback == 0xa6d8bd85 
,E/bt-btm  ( 4919): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa6d8bd85 
,E/bt-btif ( 4919): Calling BTA_HhEnable
,E/bt-btif ( 4919): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 4919): Address is:44:80:EB:7B:5A:05
D/BluetoothManagerService(  882): Bluetooth Adapter name changed to XT1072
D/BluetoothManagerService(  882): Stored Bluetooth name: XT1072
,D/BluetoothAdapterProperties( 4919): Name is: XT1072
,D/BluetoothAdapterProperties( 4919): Scan Mode:20
D/BluetoothAdapterProperties( 4919): Discoverable Timeout:120
I/wpa_supplicant( 4981): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  882): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  302): Event received = Trying to associate with
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 4981): DSDS: eapol_sm_notify_config config->sim_num = 1
D/BluetoothAdapterProperties( 4919): Adding bonded device:7C:F9:0E:37:96:AB
E/WifiConfigStore(  882): setLastSelectedConfiguration -1
,E/BluetoothRemoteDevices( 4919): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:37:96:AB, value is empty for type: 10
,E/wpa_supplicant( 4981): PNO: In assoc process
,D/bte_conf( 4919): Device ID record 1 : primary
D/bte_conf( 4919):   vendorId            = 000f
D/bte_conf( 4919):   vendorIdSource      = 0001
D/bte_conf( 4919):   product             = 1200
D/bte_conf( 4919):   version             = 1436
D/bte_conf( 4919):   clientExecutableURL = 
D/bte_conf( 4919):   serviceDescription  = 
D/bte_conf( 4919):   documentationURL    = 
D/bte_conf( 4919): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 4919): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 4919): ScanMode =  20
D/BluetoothAdapterProperties( 4919): State =  11
D/BluetoothAdapterProperties( 4919): Setting state to 12
I/BluetoothAdapterState( 4919): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  882): Message: 60
D/BluetoothManagerService(  882): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,D/BluetoothManagerService(  882): Broadcasting onBluetoothStateChange(true) to 5 receivers.
I/BluetoothAdapterState( 4919): Entering On State
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
D/BluetoothPanServiceJni( 4919): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothHeadset( 1503): onBluetoothStateChange: up=true
,E/bt_mct  ( 4919): hci lib postload completed
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/BluetoothA2dp(  882): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1503): onBluetoothStateChange: up=true
D/BluetoothHeadset(  882): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1539): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 4919): Scan Mode:21
D/BluetoothAdapterProperties( 4919): Discoverable Timeout:120
D/BluetoothManagerService(  882): Bluetooth State Change Intent: 11 -> 12
D/WifiP2pService(  882): InactiveState{ when=-2ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledStateupdate channel list
,I/Telecom ( 1503): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothMapService( 4919): onReceive
D/BluetoothMapService( 4919): STATE_ON
,D/BluetoothMapMasInstance( 4919): Map Service startRfcommSocketListener
,D/BluetoothManagerService(  882): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  882): Message: 40
D/BluetoothManagerService(  882): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapMasInstance( 4919): MAS initSocket()
,D/HeadsetStateMachine( 4919): Disconnected process message: 9, size: 0
D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/HeadsetStateMachine( 4919): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 4919): mNumber:  mType: 128
D/HeadsetStateMachine( 4919): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 4919): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/BluetoothAdapter( 4919): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 4919): Accepting socket connection...
,W/ContextImpl( 4960): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1220dca7:true
,D/LocalBluetoothProfileManager( 4960): Adding local A2DP profile
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/AuthorizationBluetoothService( 1604): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService(  882): Message: 30
,I/MDMCTBK (  302): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  302): NetlinkHandler, interfaceAdded
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
E/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
,I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  302): , Wifi = 0
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
,I/MDMCTBK (  302): send SAR ctrl over QMI
,W/BluetoothAdapter( 4919): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 4960): Adding local HEADSET profile
,D/BluetoothManagerService(  882): Message: 30
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4919): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 4919): Accept thread started.
,D/BluetoothManagerService(  882): Message: 30
,D/BluetoothManagerService(  882): Message: 30
,D/LocalBluetoothProfileManager( 4960): Adding local MAP profile
,D/BluetoothMap( 4960): Create BluetoothMap proxy object
,D/BluetoothManagerService(  882): Message: 30
,D/BluetoothManagerService(  882): Message: 30
,D/TCMD    (  476): NL - Read 312 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
,D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 192 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 68 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 1004 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,D/TCMD    (  476): NL - Read 80 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 80 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 68 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/wpa_supplicant( 4981): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  302): Event received = Associated with c0:ff:d4
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 4981): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4981): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  302): Event received = WPA: Key negotiation com
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  302): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  302):  STA Connected !!
D/TCMD    (  476): NL - Read 1004 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,E/MDMCTBK (  302): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2462, reply_len: 4, ret: 0
D/MDMCTBK (  302): get_freq !!, resp=2462
I/MDMCTBK (  302): get_freq !!, Strip data
I/MDMCTBK (  302): get_freq !!, band = 2, freq = 2462
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): get_property_value, Enter
I/MDMCTBK (  302): get_property_value, Values read from property=0,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  302): get_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, Wifi Band changed, call setWifiCutback.
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 1, data=0
I/MDMCTBK (  302): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  302): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): get_property_value, Enter
I/MDMCTBK (  302): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  302): get_property_value, Exit
I/MDMCTBK (  302): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1195565768
I/MDMCTBK (  302): return from set_get_from_wpa_supplicant
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): wifi_set_tx_pwr: SETTXPOWER = 18
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  302): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  302): , reply_len: 3, ret: 0
E/MDMCTBK (  302): MdmCutbackHndler, resp=OK
E/MDMCTBK (  302): 
D/MDMCTBK (  302): wifi_set_tx_pwr: Exit
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
,D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/LocalBluetoothProfileManager( 4960): LocalBluetoothProfileManager construction complete
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  882): Network connection established
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/DockEventReceiver( 4960): finishStartingService: stopping service
,D/BluetoothA2dp( 4960): Proxy object connected
,D/A2dpProfile( 4960): Bluetooth service connected
,D/ConnectivityService(  882): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  882): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  882): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BluetoothHeadset( 4960): Proxy object connected
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  882): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine(  882): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  882): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/HeadsetProfile( 4960): Bluetooth service connected
D/BluetoothInputDevice( 4960): Proxy object connected
D/HidProfile( 4960): Bluetooth service connected
,D/BluetoothPan( 4960): BluetoothPAN Proxy object connected
D/PanProfile( 4960): Bluetooth service connected
,D/CommandListener(  300): Setting iface cfg
,E/WifiStateMachine(  882): Start Dhcp Watchdog 1
D/BluetoothMap( 4960): Proxy object connected
D/MapProfile( 4960): Bluetooth service connected
D/BluetoothMap( 4960): getConnectedDevices()
,D/BluetoothPbap( 4960): Proxy object connected
D/PbapServerProfile( 4960): Bluetooth service connected
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend false
,E/wpa_supplicant( 4981): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
E/wpa_supplicant( 4981): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  882): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@25f83a6f target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@25f83a6f target=com.android.internal.util.StateMachine$SmHandler }
,E/DHCPCD  ( 5076): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5076): version 5.5.6 starting
,E/DHCPCD  ( 5076): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 5076): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 5076): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 5076): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 5076): wlan0: rebinding lease of 192.168.1.134
D/DHCPCD  ( 5076): wlan0: sending REQUEST (xid 0x1cafbce4), next in 3.47 seconds
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4858): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): my name is : motorola-XT1072_PT2936
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): attempting to connect to test coordinator
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): check test folder
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): found test : ./testFindPeers.js
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): found test : ./testReConnect.js
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): found test : ./testSendData.js
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): Test app app.js loaded
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4858): 
I/jxcore-log( 4858): printNetworkInfo
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): found interfaceName: lo
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4858): 
I/jxcore-log( 4858): LogCallback not set !!!!
I/jxcore-log( 4858): 
I/chromium( 4858): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DHCPCD  ( 5076): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/DHCPCD  ( 5076): wlan0: leased 192.168.1.134 for 86400 seconds
D/DHCPCD  ( 5076): wlan0: adding IP address 192.168.1.134/24
D/DHCPCD  ( 5076): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 5076): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5076): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5076): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/TCMD    (  476): NL - Read 60 bytes from update socket.
D/TCMD    (  476): NL - ignore NL message, type = 20
D/TCMD    (  476): Listening for incoming client connection request
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): WifiStateMachine DHCP successful
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  882): Calling ARP set with IP = 192.168.1.134
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/WifiStateMachine(  882): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService(  882): Adding iface wlan0 to network 100
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  882): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  882): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  882): Adding Route [fe80::/64 -> :: wlan0] to network 100
E/WifiStateMachine(  882): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  882): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  882): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  882): Setting Dns servers for network 100 to [/192.168.1.1]
,I/jxcore-log( 4858): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4858): 
I/jxcore-log( 4858): printNetworkInfo
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): found interfaceName: lo
I/jxcore-log( 4858): 
I/jxcore-log( 4858): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4858): 
I/jxcore-log( 4858): found interfaceName: wlan0
I/jxcore-log( 4858): 
I/jxcore-log( 4858): -iface: IPv4 is internal : false, has ip: 192.168.1.134
I/jxcore-log( 4858): 
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  882): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/chromium( 4858): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  882):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  882): Setting tx/rx TCP buffers to 131072,262144,3145728,4096,221184,3145728
,D/CSLegacyTypeTracker(  882): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  882): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1946): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1521): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 21 Nov 2015 12:33:35 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448109214831], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448109214810]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Validated
D/ConnectivityService(  882): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  882): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
,D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1946): CM callback handler got msg 524290
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1521): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1521): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4858): DBG, CoordinatorConnector connect called
I/jxcore-log( 4858): 
I/jxcore-log( 4858): Coordinator is now connected to the server!
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): printNetworkInfo
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): found interfaceName: lo
I/jxcore-log( 4858): 
I/jxcore-log( 4858): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4858): 
I/jxcore-log( 4858): found interfaceName: wlan0
I/jxcore-log( 4858): 
I/jxcore-log( 4858): -iface: IPv4 is internal : false, has ip: 192.168.1.134
I/jxcore-log( 4858): 
I/chromium( 4858): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1466): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AlarmManagerService(  882): Setting time of day to sec=1448109217
,W/AlarmManagerService(  882): Unable to set rtc to 1448109217: Invalid argument
,D/PollingManager( 2489): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2489): now: 409377 ,futureTime: 9223372036854775807
,D/PollingManager( 2489): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2489): now: 409417 ,futureTime: 9223372036854775807
D/PollingManager( 2489): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5160 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  882): send {25fbb27b, *alarm*:android.intent.action.TIME_TICK}
,D/Central_PollingManager( 1466): now: 409432 ,futureTime: 86473430
D/Central_PollingManager( 1466): Polling alarm set to expire at: 86473430 Current Time: 409432
,D/PollingManager( 2489): now: 409470 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2489): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  882): done {25fbb27b, *alarm*:android.intent.action.TIME_TICK} [87ms]
,D/OtaApp  ( 2489): [debug] > PollingManagerService, now: 409526 ,futureTime: 74858148
,D/OtaApp  ( 2489): [debug] > Polling alarm set to expire at: 74858148 Current Time: 409536
,D/MMApiProvisionService( 2489): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2489): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2489): createDeviceIdOrLogin update_device
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2489): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2489): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2489): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2489): generating token using payload instead of using session token
,D/MMApiProvisionService( 2489): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2489): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2489): createDeviceIdOrLogin update_device
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,D/ Nonce  ( 2489):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/MMApiProvisionService( 2489): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2489): isRequestAllowed(): already have outstanding request ... ignoring request
,D/MMApiWebService( 2489): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2489): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiProvisionService( 2489): isDeviceProvisioned: deviceId = 2072049230914535424
,I/MMApiWSBase( 2489): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 5494(260KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 7MB/12MB, paused 956us total 33.400ms
,D/CCE     ( 2489): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2489): createDeviceIdOrLogin update_device
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2489): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2489): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2489): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2489): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2489): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2489): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2489): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2489): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2489): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2489): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2489): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/art     (  882): Explicit concurrent mark sweep GC freed 45040(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.955ms total 159.306ms
,E/GpsLocationProvider(  882): No APN found to select.
,D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1946): Module APK com.google.android.play.games already loaded
,D/GpsLocationProvider(  882): NTP server returned: 1448109215024 (Sat Nov 21 13:33:35 GMT+01:00 2015) reference: 406567 certainty: 12 system time offset: -3401
,E/LocSvc_ApiV02(  882): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,I/MMApiWSBase( 2489): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MusicStore( 5160): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5160): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 1946): 0 accounts found with uca feature
,I/GamesSyncAdapter( 1946): Starting sync for 3a3529a
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GamesSyncAdapter( 1946): User is not G+ enabled. Aborting sync
,I/GamesSyncAdapter( 1946): Sync duration for 3a3529a: 24
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5160): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5160): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/jxcore-log( 4858): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 4858): 
,D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1946): Module APK com.google.android.play.games already loaded
,W/ResourcesManager( 5160): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5160): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/Auth.Api.Credentials( 1946): [CredentialSyncAdapter] Unknown sync event.
,V/JNIHelp ( 5160): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 5160): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5160): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12e51683: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5160): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5160): GMSCore installation verified
,I/ConfigStore( 5160): Config Database version: 1
,D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1946): Module APK com.google.android.play.games already loaded
,I/MediaRouter( 5160): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5160): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ Nonce  ( 2489):  Nonce Reponse 
,D/        ( 2489): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"f8d45684-556f-4153-88cd-fe56f6760a96"}
,D/MMApiWSBase( 2489): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2489):  Nonce Handle Reponse 
,I/NetworkMonitor( 5160): type=WIFI subType= reason=null isConnected=true
,D/MMApiProvisionService( 2489): mOutstandingReq set to false
,D/MMApiWSBase( 2489): doRequest(): v1/gns/list/messages resp length: 1363
,I/NetworkMonitor( 5160): type=WIFI subType= reason=null isConnected=true
,D/CCE     ( 2489): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 2489): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5232 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/MMApiProvisionService( 2489):  pTime 1448098307998 sExp 172742 cTime 1448109219328 tTime 1448271049998
D/MMApiProvisionService( 2489):  No login Required 
,D/Checkin ( 2489): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 2489): handleGetNotificationsResponse(): got 0; more=false
,I/GHttpClientFactory( 5160): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5160): Using platform SSLCertificateSocketFactory
,V/Mms     ( 5232): mnc/mcc: 
,V/Mms     ( 5232): tag: int value: recipientLimit - 20
,V/Mms     ( 5232): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 5232): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 5232): tag: int value: maxSubjectLength - 80
V/Mms     ( 5232): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 5232): tag: bool value: enableGroupMms - false
V/Mms     ( 5232):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 5232): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5265 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     ( 1539): Explicit concurrent mark sweep GC freed 29660(1913KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.104ms total 75.029ms
,D/PhoneMonitor( 5265): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 5265): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5265): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 4607:android.process.acore/u0a7 (adj 15): empty #7
,W/DataUsage( 2489): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_4607/cgroup.procs: No such file or directory
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/DataUsage( 2489): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  882): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=5286 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 4299:com.android.vending/u0a32 (adj 15): empty #7
,I/art     (  882): Explicit concurrent mark sweep GC freed 22080(944KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.478ms total 134.574ms
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_4299/cgroup.procs: No such file or directory
,I/CheckinService( 1946): Checkin interval check for package: unspecified last checkin: 1448102599285 min interval config: 0 actual interval: 6620830
,I/CheckinService( 1946): Checking schedule, now: 1448109220129 next: 1448102629259
I/CheckinService( 1946): active receiver: enabled
,I/iu.SyncManager( 1946): SYNC; picasa accounts
,D/NetworkLogImpl( 1946): Loaded NetworkSpeedPredictor
,I/CheckinService( 1946): Preparing to send checkin request
,I/EventLogService( 1946): Accumulating logs since 1448107774189
,I/iu.Environment( 1946): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1946): num queued entries: 0
D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1946): num updated entries: 0
,I/iu.SyncManager( 1946): NEXT; no task
,D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=5324 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/MDMCTBK (  302): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  302): NetlinkHandler, interfaceAdded
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
E/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  302): , Wifi = 1
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
,I/MDMCTBK (  302): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  302): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  302): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): get_property_value, Enter
I/MDMCTBK (  302): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  302): get_property_value, Exit
I/MDMCTBK (  302): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1195565768
I/MDMCTBK (  302): return from set_get_from_wpa_supplicant
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
D/MDMCTBK (  302): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  302): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  302): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  302): , reply_len: 3, ret: 0
E/MDMCTBK (  302): MdmCutbackHndler, resp=OK
E/MDMCTBK (  302): 
D/MDMCTBK (  302): wifi_set_tx_pwr: Exit
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,I/MDMCTBK (  302): send SAR ctrl over QMI
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     ( 4761): Attempt to remove local handle scope entry from IRT, ignoring
,I/GCM     ( 1604): GCM config loaded
,I/CheckinRequestBuilder( 1946): Checkin reason type: 8 attempt count: 1
,D/WifiService(  882): New client listening to asynchronous messages
,E/ActivityThread( 1946): Failed to find provider info for com.google.android.wearable.settings
,I/GAv4    ( 5286): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5286):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5286):   adb logcat -s GAv4
,I/art     ( 1604): Explicit concurrent mark sweep GC freed 16252(970KB) AllocSpace objects, 4(64KB) LOS objects, 25% free, 11MB/15MB, paused 966us total 98.814ms
,W/GAv4    ( 5286): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5286): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5286): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5286): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5286): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 5286): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5286): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5286): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 5286): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5286): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5377 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/System  ( 5286): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5286): Installed default security provider GmsCore_OpenSSL
,I/GoogleURLConnFactory( 1604): Using platform SSLCertificateSocketFactory
,D/WifiService(  882): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@1e4549b6}
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/VacuumService( 1604): Vacuum at: now=1448109221283 tag=VacuumService
,W/ResourcesManager( 5377): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Flag    ( 5286): Duration spec must be at least 2 characters long
,I/Babel_SMS( 5377): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5377): MmsConfig.loadMmsSettings
I/Babel_SMS( 5377): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5377): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5377): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5377): MmsConfig.loadFromResources
,E/Babel_SMS( 5377): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5377): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 5377): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5377): startup - clean
,I/Babel   ( 5377): deleted: false for 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5429 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 5377): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5377): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5377): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5377): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5377): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5377): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5377): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5377): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5377): onServiceConnected
,W/Babel   ( 5377): Attempted to change video mute state without an active call.
,I/Babel   ( 5377): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 4960:com.android.settings/1000 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_1000/pid_4960/cgroup.procs: No such file or directory
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5429): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5429): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5429): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5429): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/PhenotypeConfigurator( 1604): Server returned 404
,I/GAv4    ( 5429): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5429):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5429):   adb logcat -s GAv4
,W/GAv4    ( 5429): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5429): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5429): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/GetConfigurationSnapshotOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5462 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5018:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_5018/cgroup.procs: No such file or directory
,I/PhenotypeFlagCommitter( 1604): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1604): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 5462): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5462): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/GetCommittedConfigurationOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/MultiDex( 5462): VM with version 2.1.0 has multidex support
I/MultiDex( 5462): install
I/MultiDex( 5462): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5462): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/art     (  882): Explicit concurrent mark sweep GC freed 20494(973KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 20MB/30MB, paused 1.552ms total 124.042ms
,W/ActivityThread( 5462): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5462): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e5b6988: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5462): Installed default security provider GmsCore_OpenSSL
,I/WebViewFactory( 5429): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     ( 5462): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 5462): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/LibraryLoader( 5429): Time to load native libraries: 2 ms (timestamps 4404-4406)
I/LibraryLoader( 5429): Expected native library version number "",actual native library version number ""
,I/art     ( 1946): Explicit concurrent mark sweep GC freed 22080(1654KB) AllocSpace objects, 27(432KB) LOS objects, 39% free, 14MB/24MB, paused 1.313ms total 148.397ms
,V/WebViewChromiumFactoryProvider( 5429): Binding Chromium to main looper Looper (main, tid 1) {f8044b8}
I/LibraryLoader( 5429): Expected native library version number "",actual native library version number ""
,I/chromium( 5429): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5429): Initializing chromium process, singleProcess=true
,W/art     ( 5429): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5429): ApplicationContext is null in ApplicationStatus
,D/NativeLibraryUtils( 5462): Install completed successfully. count=13 extracted=0
,W/chromium( 5429): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5429): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5429): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5429): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5429): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5429): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5429): Local Branch: 
I/Adreno-EGL( 5429): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5429): Local Patches: NONE
I/Adreno-EGL( 5429): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 5429): Requires BLUETOOTH permission
,I/NSApplication( 5429): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5517 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 5160:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/art     (  320): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 348us total 21.201ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.995ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.793ms
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_5160/cgroup.procs: No such file or directory
,D/WVCdm   (  308): Instantiating CDM.
,I/WVCdm   (  308): CdmEngine::OpenSession
,I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
,D/GetCommittedConfigurationOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/UdcCache:FPQuery( 1946): Bootstrapping UDC settings cache for all accounts
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  308): Service_Initialize: starts!
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fcf000
E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fcf000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
,D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb559d960
,D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb79e0800, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb79e3ac8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb7abed10, idLength=0xb12b3730
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
D/WVCdm   (  308): PrepareKeyRequest: nonce=1765146064
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7a73478
D/DrmWidevineDash(  308): message_length=1591, signature=0xb7991dd8, signature_length=2972399380
,I/art     ( 5462): Background sticky concurrent mark sweep GC freed 25290(1495KB) AllocSpace objects, 2(32KB) LOS objects, 8% free, 10MB/11MB, paused 11.372ms total 54.692ms
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  308): CdmEngine::CloseSession
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  308): L3 Terminate.
D/DrmWidevineDash(  308): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  308): Service_Uninitialize: starts!
D/QSEECOMAPI: (  308): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  308): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  308): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=5546 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5232:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_5232/cgroup.procs: No such file or directory
,W/ResourcesManager( 5546): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/GetCommittedConfigurationOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/WVCdm   (  308): CdmEngine::OpenSession
I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  308): Service_Initialize: starts!
,D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000,
,D/QSEECOMAPI: (  308): App is not loaded in QSEE
,E/QSEECOMAPI: (  308): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fcf000
E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fcf000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xbedc74e0
,D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb798c1e8, dataLength=8
,D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb79e3ac8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb7abed50, idLength=0xb12b3730
,I/ActivityManager(  882): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=5569 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
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
D/WVCdm   (  308): PrepareKeyRequest: nonce=4270160821
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7a73478
D/DrmWidevineDash(  308): message_length=1626, signature=0xb7ab8238, signature_length=2972399380
,I/ActivityManager(  882): Killing 5265:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,D/WifiService(  882): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@1e4549b6}
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_5265/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 5324:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  308): CdmEngine::CloseSession
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  308): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  308): L3 Terminate.
D/DrmWidevineDash(  308): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  308): Service_Uninitialize: starts!
D/QSEECOMAPI: (  308): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  308): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  308): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,E/SQLiteLog( 5569): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_5324/cgroup.procs: No such file or directory
,D/GetCommittedConfigurationOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ActivityManager(  882): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5595 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5595): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AnalyticsLogBase( 5569): PlayLogger.onLoggerConnected
,I/ActivityManager(  882): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5613 uid=10096 gids={50096, 9997} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5429:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/art     ( 5462): Background partial concurrent mark sweep GC freed 14872(921KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 10MB/16MB, paused 5.037ms total 39.020ms
,I/ActivityManager(  882): Killing 5377:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_5429/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5595): Created com.android.providers.calendar.CalendarAlarmManager@bd61cd1(com.android.providers.calendar.CalendarProvider2@21982336)
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_5377/cgroup.procs: No such file or directory
,I/dex2oat ( 5630): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/Uploader( 1604):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/System.out( 5613): TimeService: Loaded Library 
D/TimeService( 5613): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448109224744
,D/        ( 5613): TimeServiceNative: User Time to be set is 1448109224744
D/QC-time-services( 5613): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5613): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5613): Lib:time_genoff_operation: pargs->ts_val = 1448109224744
D/QC-time-services( 5613): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  340): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  340): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448109224744
,D/QC-time-services(  340): Daemon:genoff_opr: Base = 2, val = 1448109224744, operation = 0
D/QC-time-services(  340): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/21/115 12:32:39
,D/QC-time-services(  340): Daemon:Value read from RTC seconds = 1448109159000
D/QC-time-services(  340): Daemon:new time 1448109224744 
,D/QC-time-services(  340): Daemon: delta 65744 genoff 65744 
D/QC-time-services(  340): Daemon:genoff_persistent_update: Writing genoff = 65744 to memory
D/QC-time-services(  340): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  340): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  340): Updating the TOD offset
,D/QC-time-services(  340): Daemon:genoff_persistent_update: Writing genoff = 65744 to memory
D/QC-time-services(  340): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  340): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  340): Daemon:Update to modem bit set
D/QC-time-services(  340): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  340): Daemon: Base = 2, Value being sent to MODEM = 18446743757744817360
,E/QC-time-services( 5613): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  340): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  340): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1946): Checkin interval check for package: unspecified last checkin: 1448102599285 min interval config: 0 actual interval: 6625535
,I/dex2oat ( 5630): dex2oat took 135.934ms (threads: 4)
,I/Adreno-EGL( 5462): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5462): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5462): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5462): Local Branch: 
I/Adreno-EGL( 5462): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5462): Local Patches: NONE
I/Adreno-EGL( 5462): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  882): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=5640 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/Adreno-EGL( 5462): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5462): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5462): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5462): Local Branch: 
I/Adreno-EGL( 5462): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5462): Local Patches: NONE
I/Adreno-EGL( 5462): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/GetCommittedConfigurationOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/Adreno-EGL( 5462): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5462): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5462): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5462): Local Branch: 
I/Adreno-EGL( 5462): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5462): Local Patches: NONE
I/Adreno-EGL( 5462): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/GAv4    ( 5640): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5640):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5640):   adb logcat -s GAv4
,W/GAv4    ( 5640): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:32000 mC
,W/GAv4    ( 5640): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 5462): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5462): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5462): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5462): Local Branch: 
I/Adreno-EGL( 5462): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5462): Local Patches: NONE
I/Adreno-EGL( 5462): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/GAv4    ( 5640): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/GetCommittedConfigurationOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ActivityManager(  882): Killing 5517:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_5517/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2489): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/CheckinRequestBuilder( 1946): Classify the device as Phone.
,I/SundryService( 2489): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,E/SQLiteLog( 2489): (284) automatic index on registration(APP_ID)
,D/WaitableIntentService( 2489): ServiceHandler.handleMessage: mWaitCount=1
,I/PushService( 2489): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2489): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2489): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2489): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  882): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetCommittedConfigurationOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/OtaApp  ( 2489): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2489): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2489): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2489): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2489): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2489): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2489): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2489): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2489): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2489): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2489): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2489): publish the event [tag = MOT_OTA event name = LOG]
,D/GetCommittedConfigurationOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/Keyboard.Facilitator( 1405): onFinishInput()
,W/IInputConnectionWrapper( 4858): showStatusIcon on inactive InputConnection
,I/SundryService( 2489): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 2489): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 2489): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 2489): ServiceHandler.handleMessage: mWaitCount=0
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5677 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinTask( 1946): Sending checkin request (9521 bytes)
,D/GetNotificationsWS( 2489): unbindWebServices(): un-registering our AIDL callback...
,I/LaunchCheckinHandler(  882): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,211
,W/ResourcesManager( 5677): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/GetCommittedConfigurationOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/CalendarProvider2( 5595): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5595): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/GetCommittedConfigurationOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ActivityManager(  882): Killing 4761:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/CheckinRequestBuilder( 1946): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_4761/cgroup.procs: No such file or directory
,E/ActivityThread( 1946): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 5677): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5677): MmsConfig.loadMmsSettings
I/Babel_SMS( 5677): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5677): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5677): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5677): MmsConfig.loadFromResources
E/Babel_SMS( 5677): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5677): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 5677): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5677): startup - clean
,I/Babel   ( 5677): deleted: false for 0
,I/CheckinRequestBuilder( 1946): Classify the device as Phone.
,I/CheckinTask( 1946): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1946): Checking schedule, now: 1448109226290 next: 1448710363284
I/CheckinService( 1946): active receiver: disabled
,D/CheckinService( 1946): Recording last checkin time for package unspecified as 1448109226335
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=5707 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 5677): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5677): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5677): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5677): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5677): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5677): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5677): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5677): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Killing 5546:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_5546/cgroup.procs: No such file or directory
,I/vclib   ( 5677): onServiceConnected
W/Babel   ( 5677): Attempted to change video mute state without an active call.
,D/WearableService( 1741): callingUid 10016, callindPid: 1741
,I/art     (  882): Explicit concurrent mark sweep GC freed 20045(886KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.460ms total 115.098ms
,I/ActivityManager(  882): Killing 5569:com.google.android.calendar/u0a49 (adj 15): empty #7
,E/MDM     ( 1741): [165] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/libprocessgroup(  882): failed to open /acct/uid_10049/pid_5569/cgroup.procs: No such file or directory
,D/LocationInitializer( 1946): Restart initialization of location
,D/GCM     ( 1604): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1604): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1946): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/GCoreFlp( 1741): No location to return for getLastLocation()
,W/FusedLocationProvider( 1604): location=null
,I/ActivityManager(  882): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.WidgetDataReceiver: pid=5738 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SQLiteLog( 5738): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/AnalyticsLogBase( 5738): PlayLogger.onLoggerConnected
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5761 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5286:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10057/pid_5286/cgroup.procs: No such file or directory
,W/ResourcesManager( 5761): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5784 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 5784): Register our PhoneStateListener
,V/SetupWizard( 5784): Connected to Gservices successfully
,I/ActivityManager(  882): Killing 5613:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10096/pid_5613/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1604): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TaskPersister(  882): removeObsoleteFile: deleting file=28_task.xml
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1539): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5811 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  320): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 20.652ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.108ms
,I/ActivityManager(  882): Killing 5640:com.google.android.deskclock/u0a55 (adj 15): empty #7
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.467ms
,W/libprocessgroup(  882): failed to open /acct/uid_10055/pid_5640/cgroup.procs: No such file or directory
,V/GmsNetworkLocationProvi( 1741): DISABLE
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
I/GCoreNlp( 1741): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1557): Deferring update until onResume
,I/art     ( 1741): Explicit concurrent mark sweep GC freed 19295(1269KB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 11MB/18MB, paused 870us total 82.195ms
V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@a3164af
,E/DataBuffer( 1741): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3802bf51)
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5849 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5707:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_5707/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5874 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/ResourcesManager( 5677): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5677): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5677): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ContactLocale( 5874): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/System  ( 5677): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5677): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5901 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5761:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_5761/cgroup.procs: No such file or directory
,W/asset   ( 5901): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5901): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 5901): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5901): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5921 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5784:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_5784/cgroup.procs: No such file or directory
,D/Finsky  ( 5921): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5921): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5921): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5921): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 5921): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5921): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 5921): Skipping gmscore version check
,D/Finsky  ( 5921): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/Launcher( 1557): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@363e9509 new=com.google.android.velvet.VelvetApplication@363e9509
I/UpdateIcingCorporaServi( 5811): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1946): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 5921): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ContextImpl( 5738): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5975 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 1946): Null package name or gms related package.  Ignoreing.
,I/GAV2    ( 5738): Thread[GAThread,5,main]: No campaign data found.
,I/Icing   ( 1946): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 5975): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5811): UpdateCorporaTask done [took 162 ms] updated apps [took 162 ms] 
,I/ActivityManager(  882): Killing 5595:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10005/pid_5595/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6008 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  882): Explicit concurrent mark sweep GC freed 19781(998KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.538ms total 113.270ms
,W/ResourcesManager( 6008): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6008): Created com.android.providers.calendar.CalendarAlarmManager@bd61cd1(com.android.providers.calendar.CalendarProvider2@21982336)
,I/ActivityManager(  882): Killing 5738:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10049/pid_5738/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 5462:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_5462/cgroup.procs: No such file or directory
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=294, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311759, SEQNUM=4452, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-723, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/CalendarProvider2( 6008): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6008): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6036 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/ActivityManager(  882): Killing 5849:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_5849/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,W/ResourcesManager( 6036): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=6064 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5901:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_5901/cgroup.procs: No such file or directory
,E/SQLiteLog( 6064): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/AnalyticsLogBase( 6064): PlayLogger.onLoggerConnected
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  882): Killing 5811:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_5811/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 5677:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_5677/cgroup.procs: No such file or directory
,W/ContextImpl( 6064): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 6064): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  882): Killing 5921:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_5921/cgroup.procs: No such file or directory
,W/SQLiteConnectionPool( 1946): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  882): send {25fbb27b, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {34c3a29e, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  882): done {34c3a29e, *walarm*:android.content.syncmanager.SYNC_ALARM} [7ms]
,V/AlarmManager(  882): done {25fbb27b, *alarm*:android.intent.action.TIME_TICK} [46ms]
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311837, SEQNUM=4460, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-742, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312348, SEQNUM=4462, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-756, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  882): send {34c3a29e, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  882): done {34c3a29e, *walarm*:android.content.syncmanager.SYNC_ALARM} [3ms]
,I/ActivityManager(  882): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6105 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/GAv4    ( 6105): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6105):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6105):   adb logcat -s GAv4
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312425, SEQNUM=4465, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-764, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/GAv4    ( 6105): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6105): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6105): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,W/AnalyticsTrackerProxyImpl( 6105): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteLog( 6105): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6105): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 6105): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6105): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6105): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6105): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6105): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 6105): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6105): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  882): Killing 5874:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_5874/cgroup.procs: No such file or directory
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1405): run()
I/Keyboard.Facilitator( 1405): flushDynamicLanguageModels()
,I/ConfigService( 1604): onCreate
,E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@17251cb1)
,E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b715596)
,E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2f595517)
,E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@7c06d04)
,E/DataBuffer( 1604): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@33dd2ed)
,I/ConfigService( 1604): onDestroy
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  882): send {25fbb27b, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {34c3a29e, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  882): done {34c3a29e, *walarm*:android.content.syncmanager.SYNC_ALARM} [10ms]
,V/AlarmManager(  882): done {25fbb27b, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4858): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): DBG, CoordinatorConnector command called
I/jxcore-log( 4858): 
I/jxcore-log( 4858): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"1000000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"2\"}","devices":19,"addressList":[{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{
I/jxcore-log( 4858): Start now : testSendData.js
I/jxcore-log( 4858): 
I/jxcore-log( 4858): stop tests now !
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"2"}, bt-address lenght : 19
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): check server
I/jxcore-log( 4858): 
I/jxcore-log( 4858): serverPort is 38017
I/jxcore-log( 4858): 
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 4858): Stoping All
,I/        ( 4858): Stopping services
I/        ( 4858): Stop Bluetooth
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 4858): Start-My BT: 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 4858):  mInstanceString : {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2936","ra":"44:80:EB:7B:5A:05"}
,I/        ( 4858): All stuff available and enabled
I/        ( 4858): Stoping All
I/        ( 4858): Stopping services
I/        ( 4858): Stop Bluetooth
I/        ( 4858): Starting All
I/        ( 4858): Stopping services
I/        ( 4858): Starting services address: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2936","ra":"44:80:EB:7B:5A:05"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@156961
,I/        ( 4858): Stopping services
,I/        ( 4858): Starting services address: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2936","ra":"44:80:EB:7B:5A:05"}
,I/        ( 4858): Add local service :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2936","ra":"44:80:EB:7B:5A:05"}, length : 81
,D/WifiP2pService(  882): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@eff26850 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@eff26850 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service
D/WifiP2pService(  882): add a new client
,I/        ( 4858): peerDiscoveryTimer timeout value:6226
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4858): Stop Bluetooth
,I/        ( 4858): StartBluetooth listener
I/        ( 4858): StartBluetooth listener
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiP2pService(  882): discovery change broadcast true
I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,W/BluetoothAdapter( 4858): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 4858): StartBroadcasting started ok
I/jxcore-log( 4858): 
I/jxcore-log( 4858): do fake peer & start
I/jxcore-log( 4858): 
I/jxcore-log( 4858): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:38:21.435Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:38:21.435Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:38:21.436Z SendDataConnector.js: do connect now
I/jxcore-log( 4858): 
,I/BTListenerThread( 4858): starting to listen
I/BTListenerThread( 4858): waiting to accept incoming Connection
,I/        ( 4858): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/BTConnectToThread( 4858): Starting to connect
,I/        ( 4858): Connecting to null, at E0:DB:10:1F:C9:5E
W/BluetoothAdapter( 4858): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 4858): 2015-11-21T12:38:21.447Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
I/jxcore-log( 4858): 
,I/chromium( 4858): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/WB      ( 4858): We already were running, thus doing nothing
D/BTIF_SOCK( 4919): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 4858): Added local service
I/        ( 4858): Cleared service requests
I/        ( 4858): Stopped peer discovery
I/        ( 4858): Started peer discovery
I/        ( 4858): Discovery state changed to Started.
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-ADDED 0 c0
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 4919): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 4919): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
,E/bt-btif ( 4919): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4919): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 4919): Entering PendingCommandState State
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1481f580:true
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5d8c7fe:true
,I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  882): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=6181 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 4919): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 4919): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 4919): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
D/BluetoothAdapterService( 4919): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a45a237
,D/BluetoothMetrics( 4919): btclass5a020c
,D/Checkin ( 4919): publish the event [tag = MOT_BT event name = PAIRING]
,I/BluetoothBondStateMachine( 4919): StableState(): Entering Off State
,W/bt-btif ( 4919): new conn_srvc id:26, app_id:1
W/bt-btif ( 4919): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4919): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 4858): Starting to Handshake
I/BTHandshakeSocketThread( 4858): Creating BTHandshakeSocketThread
I/BTConnectToThread( 4858): MESSAGE_WRITE 81 bytes.
I/BTHandshakeSocketThread( 4858): BTHandshakeSocketThread started
,W/ResourcesManager( 6181): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  882): Message: 20
,D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@232e1675:true
,I/ActivityManager(  882): Killing 5975:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/BTConnectToThread( 4858): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 4858): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT9390","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 4858): HandshakeOk : samsung-SM-N9005_PT9390
I/HS      ( 4858): Hand Shake finished outgoing for : samsung-SM-N9005_PT9390
I/BTHandshakeSocketThread( 4858): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4858): Starting the connected thread incoming : false, samsung-SM-N9005_PT9390
,I/BtToSocketBase( 4858): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4858): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 4858): mHTTPPort  set to : 43911
I/BtConnectorHelper( 4858): Request socket is using : 43911
I/BtToRequestSocket( 4858): Now accepting connections
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_5975/cgroup.procs: No such file or directory
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/wpa_supplicant( 4981): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  302): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4858): Found 1 peers.
I/SS      ( 4858): Peer(1): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
D/WifiP2pManager( 4858): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4858): Added service request
,I/BtConnectorHelper( 4858): Calling ConnectionStatusUpdate with port :43911
I/jxcore-log( 4858): 2015-11-21T12:38:23.526Z SendDataConnector.js: CLIENT connected to 43911, error: null
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:38:23.526Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:23.535Z SendDataConnector.js: CLIENT now sending 1000000 bytes of data
I/jxcore-log( 4858): 
,I/BtToRequestSocket( 4858): incoming data from: /127.0.0.1, port: 43911
I/BtToRequestSocket( 4858): Set local streams
I/BtToRequestSocket( 4858): rin ended ---------------------------;
,I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 4981): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  302): Event received = P2P: Reject scan trigger 
,I/        ( 4858): Started service discovery
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:64100
,I/jxcore-log( 4858): 2015-11-21T12:38:24.333Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:24.421Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67614
,I/jxcore-log( 4858): 2015-11-21T12:38:24.596Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 4858): 
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/jxcore-log( 4858): 2015-11-21T12:38:24.802Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 4858): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69012
,I/jxcore-log( 4858): 2015-11-21T12:38:26.309Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 4858): 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f0351c rs_disc_pending=1
W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f036dc rs_disc_pending=1
W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4858): 2015-11-21T12:38:27.444Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69420
,I/jxcore-log( 4858): 2015-11-21T12:38:27.620Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:27.901Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 4858): 
,I/BluetoothBondStateMachine( 4919): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 4919): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4919): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 4919): Entering PendingCommandState State
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f0351c rs_disc_pending=0
,W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 4919): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 4919): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 4919): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 4919): StableState(): Entering Off State
,D/BluetoothMetrics( 4919): btclass5a020c
,D/Checkin ( 4919): publish the event [tag = MOT_BT event name = PAIRING]
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69828
,I/jxcore-log( 4858): 2015-11-21T12:38:28.683Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:28.688Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 4858): 
,W/bt-btif ( 4919): new conn_srvc id:26, app_id:255
W/bt-btif ( 4919): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4919): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4858): we got incoming connection
I/BTHandshakeSocketThread( 4858): Creating BTHandshakeSocketThread
I/BTListenerThread( 4858): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4858): BTHandshakeSocketThread started
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f0351c rs_disc_pending=1
W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f036dc rs_disc_pending=1
W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 4858): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 4858): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1736","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4858): MESSAGE_WRITE 81 bytes.
,I/HS      ( 4858): Incoming connection Hand Shake finished for : LGE-LG-D722_PT1736
,I/BTHandshakeSocketThread( 4858): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4858): Starting the connected thread incoming : true, LGE-LG-D722_PT1736
I/BtToSocketBase( 4858): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4858): Creating BTConnectedThread
I/BtConnectorHelper( 4858): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4858): --DoOneRunRound started
,I/BtToRequestSocket( 4858): LocalHost address: localhost/127.0.0.1, port: 38017
,I/jxcore-log( 4858): 2015-11-21T12:38:29.582Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4858): 
,I/BtToRequestSocket( 4858): --DoOneRunRound ended
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:62180
,I/jxcore-log( 4858): 2015-11-21T12:38:30.206Z SendDataConnector.js: CLIENT is data received : 120000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:30.311Z SendDataConnector.js: CLIENT is data received : 130000
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71634
,I/jxcore-log( 4858): 2015-11-21T12:38:30.700Z SendDataConnector.js: CLIENT is data received : 140000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:30.789Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4858): 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-REMOVED 0 
,I/jxcore-log( 4858): 2015-11-21T12:38:30.927Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:31.095Z SendDataConnector.js: CLIENT is data received : 150000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:31.112Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69926
,I/jxcore-log( 4858): 2015-11-21T12:38:31.439Z SendDataConnector.js: CLIENT is data received : 160000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:31.447Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4858): 
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 4858): 2015-11-21T12:38:31.541Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:31.700Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:31.792Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:31.932Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:31.937Z SendDataConnector.js: CLIENT is data received : 170000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:32.027Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:32.058Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:32.246Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:32.272Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:32.328Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:32.355Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:32.781Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:33.160Z SendDataTCPServer.js: TCP/IP server has received 29972 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:33.432Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:33.528Z SendDataTCPServer.js: TCP/IP server has received 33932 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:33.693Z SendDataTCPServer.js: TCP/IP server has received 35912 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:55348
,I/jxcore-log( 4858): 2015-11-21T12:38:33.883Z SendDataConnector.js: CLIENT is data received : 200000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:33.984Z SendDataConnector.js: CLIENT is data received : 210000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:34.013Z SendDataTCPServer.js: TCP/IP server has received 37892 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:34.181Z SendDataTCPServer.js: TCP/IP server has received 39872 bytes of data
I/jxcore-log( 4858): 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 ea
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 ea
,I/jxcore-log( 4858): 2015-11-21T12:38:34.335Z SendDataTCPServer.js: TCP/IP server has received 41852 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:34.387Z SendDataTCPServer.js: TCP/IP server has received 43832 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72004
,I/jxcore-log( 4858): 2015-11-21T12:38:34.498Z SendDataTCPServer.js: TCP/IP server has received 45812 bytes of data
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:38:34.499Z SendDataConnector.js: CLIENT is data received : 220000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:34.607Z SendDataTCPServer.js: TCP/IP server has received 47792 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:34.678Z SendDataConnector.js: CLIENT is data received : 230000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:34.708Z SendDataTCPServer.js: TCP/IP server has received 49772 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:35.074Z SendDataTCPServer.js: TCP/IP server has received 51752 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70296
,I/jxcore-log( 4858): 2015-11-21T12:38:35.083Z SendDataConnector.js: CLIENT is data received : 240000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:35.223Z SendDataTCPServer.js: TCP/IP server has received 53732 bytes of data
I/jxcore-log( 4858): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4858): 2015-11-21T12:38:35.365Z SendDataTCPServer.js: TCP/IP server has received 55712 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:35.438Z SendDataConnector.js: CLIENT is data received : 250000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:35.609Z SendDataTCPServer.js: TCP/IP server has received 57692 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:35.931Z SendDataTCPServer.js: TCP/IP server has received 59672 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:36.367Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:56708
,I/jxcore-log( 4858): 2015-11-21T12:38:36.388Z SendDataConnector.js: CLIENT is data received : 280000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:36.594Z SendDataConnector.js: CLIENT is data received : 290000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:36.699Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72374
,I/jxcore-log( 4858): 2015-11-21T12:38:36.943Z SendDataConnector.js: CLIENT is data received : 300000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:37.103Z SendDataTCPServer.js: TCP/IP server has received 65612 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:37.133Z SendDataConnector.js: CLIENT is data received : 310000
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71656
,I/jxcore-log( 4858): 2015-11-21T12:38:37.569Z SendDataConnector.js: CLIENT is data received : 320000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:37.616Z SendDataTCPServer.js: TCP/IP server has received 67592 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:37.797Z SendDataConnector.js: CLIENT is data received : 330000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:38.044Z SendDataTCPServer.js: TCP/IP server has received 69572 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:38.538Z SendDataTCPServer.js: TCP/IP server has received 71552 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:58068
,I/jxcore-log( 4858): 2015-11-21T12:38:38.663Z SendDataConnector.js: CLIENT is data received : 360000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:38.854Z SendDataConnector.js: CLIENT is data received : 370000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:39.046Z SendDataTCPServer.js: TCP/IP server has received 73532 bytes of data
I/jxcore-log( 4858): 
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70628
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 4858): 2015-11-21T12:38:39.169Z SendDataConnector.js: CLIENT is data received : 380000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:39.506Z SendDataTCPServer.js: TCP/IP server has received 75512 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:39.524Z SendDataConnector.js: CLIENT is data received : 390000
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68920
,I/jxcore-log( 4858): 2015-11-21T12:38:39.840Z SendDataConnector.js: CLIENT is data received : 400000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:39.987Z SendDataTCPServer.js: TCP/IP server has received 77492 bytes of data
I/jxcore-log( 4858): 
,D/UdcCache:FPQuery( 1946): Bootstrapping UDC settings cache for all accounts
,I/jxcore-log( 4858): 2015-11-21T12:38:40.150Z SendDataConnector.js: CLIENT is data received : 410000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:41.187Z SendDataTCPServer.js: TCP/IP server has received 79472 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:59428
,I/jxcore-log( 4858): 2015-11-21T12:38:41.355Z SendDataConnector.js: CLIENT is data received : 440000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:41.799Z SendDataConnector.js: CLIENT is data received : 450000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:41.913Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70998
,I/jxcore-log( 4858): 2015-11-21T12:38:42.261Z SendDataConnector.js: CLIENT is data received : 460000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:42.374Z SendDataTCPServer.js: TCP/IP server has received 83432 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:42.718Z SendDataConnector.js: CLIENT is data received : 470000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:42.851Z SendDataTCPServer.js: TCP/IP server has received 85412 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69290
,I/jxcore-log( 4858): 2015-11-21T12:38:43.074Z SendDataConnector.js: CLIENT is data received : 480000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:43.353Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:43.518Z SendDataConnector.js: CLIENT is data received : 490000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:43.793Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:44.216Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:60788
,I/jxcore-log( 4858): 2015-11-21T12:38:44.454Z SendDataConnector.js: CLIENT is data received : 520000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:44.739Z SendDataConnector.js: CLIENT is data received : 530000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:44.757Z SendDataTCPServer.js: TCP/IP server has received 93332 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72358
,I/jxcore-log( 4858): 2015-11-21T12:38:45.120Z SendDataConnector.js: CLIENT is data received : 540000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:45.211Z SendDataTCPServer.js: TCP/IP server has received 95312 bytes of data
I/jxcore-log( 4858): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4858): 2015-11-21T12:38:45.762Z SendDataConnector.js: CLIENT is data received : 550000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:45.913Z SendDataTCPServer.js: TCP/IP server has received 97292 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70650
,I/jxcore-log( 4858): 2015-11-21T12:38:46.119Z SendDataConnector.js: CLIENT is data received : 560000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:46.400Z SendDataTCPServer.js: TCP/IP server has received 99272 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:46.434Z SendDataConnector.js: CLIENT is data received : 570000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:46.939Z SendDataTCPServer.js: TCP/IP server has received 101252 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:47.417Z SendDataTCPServer.js: TCP/IP server has received 103232 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:47.771Z SendDataTCPServer.js: TCP/IP server has received 105212 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:58052
,I/jxcore-log( 4858): 2015-11-21T12:38:47.897Z SendDataConnector.js: CLIENT is data received : 600000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:48.099Z SendDataConnector.js: CLIENT is data received : 610000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:48.248Z SendDataTCPServer.js: TCP/IP server has received 107192 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67642
,I/jxcore-log( 4858): 2015-11-21T12:38:48.608Z SendDataConnector.js: CLIENT is data received : 620000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:48.626Z SendDataTCPServer.js: TCP/IP server has received 109172 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:48.869Z SendDataConnector.js: CLIENT is data received : 630000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:49.032Z SendDataTCPServer.js: TCP/IP server has received 111152 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71020
,I/jxcore-log( 4858): 2015-11-21T12:38:49.292Z SendDataConnector.js: CLIENT is data received : 640000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:50.076Z SendDataTCPServer.js: TCP/IP server has received 113132 bytes of data
I/jxcore-log( 4858): 
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f0351c rs_disc_pending=0
W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4858): 2015-11-21T12:38:50.428Z SendDataConnector.js: CLIENT is data received : 650000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:50.480Z SendDataTCPServer.js: TCP/IP server has received 115112 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:50.818Z SendDataTCPServer.js: TCP/IP server has received 117092 bytes of data
I/jxcore-log( 4858): 
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f036dc rs_disc_pending=0
W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4858): 2015-11-21T12:38:51.434Z SendDataTCPServer.js: TCP/IP server has received 119072 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:59412
,I/jxcore-log( 4858): 2015-11-21T12:38:51.794Z SendDataConnector.js: CLIENT is data received : 670000
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:38:51.795Z SendDataConnector.js: CLIENT is data received : 680000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:51.855Z SendDataTCPServer.js: TCP/IP server has received 121052 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:52.513Z SendDataConnector.js: CLIENT is data received : 690000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:52.519Z SendDataConnector.js: CLIENT is data received : 700000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:52.891Z SendDataTCPServer.js: TCP/IP server has received 123032 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:53.240Z SendDataTCPServer.js: TCP/IP server has received 125012 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:53.590Z SendDataTCPServer.js: TCP/IP server has received 126992 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:53.607Z SendDataTCPServer.js: TCP/IP server has received 128972 bytes of data
I/jxcore-log( 4858): 
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:65042
,I/jxcore-log( 4858): 2015-11-21T12:38:53.627Z SendDataConnector.js: CLIENT is data received : 710000
I/jxcore-log( 4858): 
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312698, SEQNUM=4487, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3230, POWER_SUPPLY_CHARGE_COUNTER=14, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/jxcore-log( 4858): 2015-11-21T12:38:53.756Z SendDataTCPServer.js: TCP/IP server has received 130952 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:53.833Z SendDataTCPServer.js: TCP/IP server has received 132932 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:53.868Z SendDataTCPServer.js: TCP/IP server has received 134912 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:53.981Z SendDataTCPServer.js: TCP/IP server has received 136892 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.054Z SendDataTCPServer.js: TCP/IP server has received 138872 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.129Z SendDataTCPServer.js: TCP/IP server has received 140852 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.237Z SendDataTCPServer.js: TCP/IP server has received 142832 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.378Z SendDataTCPServer.js: TCP/IP server has received 144812 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.401Z SendDataConnector.js: CLIENT is data received : 720000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.447Z SendDataTCPServer.js: TCP/IP server has received 146792 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.525Z SendDataTCPServer.js: TCP/IP server has received 148772 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.532Z SendDataTCPServer.js: TCP/IP server has received 150752 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.554Z SendDataTCPServer.js: TCP/IP server has received 152732 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.639Z SendDataTCPServer.js: TCP/IP server has received 154712 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.717Z SendDataTCPServer.js: TCP/IP server has received 156692 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.805Z SendDataTCPServer.js: TCP/IP server has received 158672 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.882Z SendDataTCPServer.js: TCP/IP server has received 160652 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.889Z SendDataTCPServer.js: TCP/IP server has received 162632 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:54.978Z SendDataTCPServer.js: TCP/IP server has received 164612 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:55.092Z SendDataTCPServer.js: TCP/IP server has received 166592 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:55.229Z SendDataTCPServer.js: TCP/IP server has received 168572 bytes of data
I/jxcore-log( 4858): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4858): 2015-11-21T12:38:55.310Z SendDataTCPServer.js: TCP/IP server has received 170552 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:55.318Z SendDataTCPServer.js: TCP/IP server has received 172532 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:55.400Z SendDataTCPServer.js: TCP/IP server has received 174512 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:55.485Z SendDataTCPServer.js: TCP/IP server has received 176492 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:55.562Z SendDataTCPServer.js: TCP/IP server has received 178472 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:55.733Z SendDataTCPServer.js: TCP/IP server has received 180452 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:55.815Z SendDataTCPServer.js: TCP/IP server has received 182432 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:55.892Z SendDataTCPServer.js: TCP/IP server has received 184412 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:55.928Z SendDataTCPServer.js: TCP/IP server has received 186392 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:55.978Z SendDataTCPServer.js: TCP/IP server has received 188372 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.018Z SendDataTCPServer.js: TCP/IP server has received 190352 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:56676
,I/jxcore-log( 4858): 2015-11-21T12:38:56.033Z SendDataConnector.js: CLIENT is data received : 750000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.067Z SendDataTCPServer.js: TCP/IP server has received 192332 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.098Z SendDataTCPServer.js: TCP/IP server has received 194312 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.134Z SendDataConnector.js: CLIENT is data received : 760000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.157Z SendDataTCPServer.js: TCP/IP server has received 196292 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.262Z SendDataTCPServer.js: TCP/IP server has received 198272 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.346Z SendDataTCPServer.js: TCP/IP server has received 200252 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.353Z SendDataTCPServer.js: TCP/IP server has received 202232 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.508Z SendDataTCPServer.js: TCP/IP server has received 204212 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.566Z SendDataConnector.js: CLIENT is data received : 770000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.595Z SendDataTCPServer.js: TCP/IP server has received 206192 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.628Z SendDataTCPServer.js: TCP/IP server has received 208172 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.677Z SendDataTCPServer.js: TCP/IP server has received 210152 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.684Z SendDataTCPServer.js: TCP/IP server has received 212132 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:56.767Z SendDataTCPServer.js: TCP/IP server has received 214112 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:59353
,I/jxcore-log( 4858): 2015-11-21T12:38:56.928Z SendDataConnector.js: CLIENT is data received : 780000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.019Z SendDataTCPServer.js: TCP/IP server has received 216092 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.100Z SendDataTCPServer.js: TCP/IP server has received 218072 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.108Z SendDataTCPServer.js: TCP/IP server has received 220052 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.190Z SendDataTCPServer.js: TCP/IP server has received 222032 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.269Z SendDataTCPServer.js: TCP/IP server has received 224012 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.278Z SendDataTCPServer.js: TCP/IP server has received 225992 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.350Z SendDataTCPServer.js: TCP/IP server has received 227972 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.358Z SendDataTCPServer.js: TCP/IP server has received 229952 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.471Z SendDataConnector.js: CLIENT is data received : 790000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.526Z SendDataTCPServer.js: TCP/IP server has received 231932 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.627Z SendDataTCPServer.js: TCP/IP server has received 233912 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.658Z SendDataTCPServer.js: TCP/IP server has received 235892 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.718Z SendDataTCPServer.js: TCP/IP server has received 237872 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:49453
,I/jxcore-log( 4858): 2015-11-21T12:38:57.742Z SendDataConnector.js: CLIENT is data received : 800000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.798Z SendDataTCPServer.js: TCP/IP server has received 239852 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.805Z SendDataTCPServer.js: TCP/IP server has received 241832 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:57.988Z SendDataTCPServer.js: TCP/IP server has received 243812 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:58.028Z SendDataTCPServer.js: TCP/IP server has received 245792 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:58.159Z SendDataTCPServer.js: TCP/IP server has received 247772 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:58.230Z SendDataTCPServer.js: TCP/IP server has received 249752 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:58.310Z SendDataTCPServer.js: TCP/IP server has received 251732 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:58.320Z SendDataTCPServer.js: TCP/IP server has received 253712 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:58.405Z SendDataTCPServer.js: TCP/IP server has received 255692 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:58.488Z SendDataTCPServer.js: TCP/IP server has received 257672 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:58.573Z SendDataTCPServer.js: TCP/IP server has received 259652 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:58.607Z SendDataTCPServer.js: TCP/IP server has received 261632 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:58.789Z SendDataTCPServer.js: TCP/IP server has received 263612 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:58.828Z SendDataTCPServer.js: TCP/IP server has received 265592 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:58.879Z SendDataTCPServer.js: TCP/IP server has received 267572 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:58.958Z SendDataTCPServer.js: TCP/IP server has received 269552 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.042Z SendDataTCPServer.js: TCP/IP server has received 271532 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.212Z SendDataTCPServer.js: TCP/IP server has received 273512 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.297Z SendDataTCPServer.js: TCP/IP server has received 275492 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.377Z SendDataTCPServer.js: TCP/IP server has received 277472 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.454Z SendDataTCPServer.js: TCP/IP server has received 279452 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:29653
,I/jxcore-log( 4858): 2015-11-21T12:38:59.498Z SendDataConnector.js: CLIENT is data received : 830000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.536Z SendDataTCPServer.js: TCP/IP server has received 281432 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.542Z SendDataTCPServer.js: TCP/IP server has received 283412 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.560Z SendDataConnector.js: CLIENT is data received : 840000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.577Z SendDataTCPServer.js: TCP/IP server has received 285392 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.623Z SendDataTCPServer.js: TCP/IP server has received 287372 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.659Z SendDataTCPServer.js: TCP/IP server has received 289352 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.705Z SendDataTCPServer.js: TCP/IP server has received 291332 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.710Z SendDataTCPServer.js: TCP/IP server has received 293312 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.790Z SendDataTCPServer.js: TCP/IP server has received 295292 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.828Z SendDataTCPServer.js: TCP/IP server has received 297272 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.908Z SendDataTCPServer.js: TCP/IP server has received 299252 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.965Z SendDataTCPServer.js: TCP/IP server has received 301232 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:38:59.987Z SendDataTCPServer.js: TCP/IP server has received 303212 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:22723
,I/jxcore-log( 4858): 2015-11-21T12:39:00.004Z SendDataConnector.js: CLIENT is data received : 850000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.067Z SendDataTCPServer.js: TCP/IP server has received 305192 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.098Z SendDataTCPServer.js: TCP/IP server has received 309152 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.155Z SendDataTCPServer.js: TCP/IP server has received 311132 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.162Z SendDataTCPServer.js: TCP/IP server has received 313112 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.379Z SendDataConnector.js: CLIENT is data received : 860000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.418Z SendDataTCPServer.js: TCP/IP server has received 315092 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.522Z SendDataTCPServer.js: TCP/IP server has received 317072 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.528Z SendDataTCPServer.js: TCP/IP server has received 319052 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.597Z SendDataTCPServer.js: TCP/IP server has received 321032 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.680Z SendDataTCPServer.js: TCP/IP server has received 323012 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.718Z SendDataTCPServer.js: TCP/IP server has received 324992 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.754Z SendDataTCPServer.js: TCP/IP server has received 326972 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.760Z SendDataTCPServer.js: TCP/IP server has received 328952 bytes of data
I/jxcore-log( 4858): 
,D/        ( 4919): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13813
,I/jxcore-log( 4858): 2015-11-21T12:39:00.819Z SendDataConnector.js: CLIENT is data received : 870000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.835Z SendDataTCPServer.js: TCP/IP server has received 330932 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.842Z SendDataTCPServer.js: TCP/IP server has received 332912 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.878Z SendDataTCPServer.js: TCP/IP server has received 334892 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.917Z SendDataTCPServer.js: TCP/IP server has received 336872 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:00.996Z SendDataTCPServer.js: TCP/IP server has received 338852 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.077Z SendDataTCPServer.js: TCP/IP server has received 340832 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.188Z SendDataTCPServer.js: TCP/IP server has received 342812 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.228Z SendDataTCPServer.js: TCP/IP server has received 344792 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.274Z SendDataTCPServer.js: TCP/IP server has received 346772 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.307Z SendDataTCPServer.js: TCP/IP server has received 348752 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.353Z SendDataTCPServer.js: TCP/IP server has received 350732 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.359Z SendDataTCPServer.js: TCP/IP server has received 352712 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.413Z SendDataConnector.js: CLIENT is data received : 880000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.437Z SendDataTCPServer.js: TCP/IP server has received 354692 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.517Z SendDataTCPServer.js: TCP/IP server has received 356672 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.582Z SendDataTCPServer.js: TCP/IP server has received 358652 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.659Z SendDataTCPServer.js: TCP/IP server has received 360632 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.665Z SendDataTCPServer.js: TCP/IP server has received 362612 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.742Z SendDataTCPServer.js: TCP/IP server has received 364592 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.778Z SendDataTCPServer.js: TCP/IP server has received 366572 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.828Z SendDataTCPServer.js: TCP/IP server has received 368552 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:01.912Z SendDataTCPServer.js: TCP/IP server has received 370532 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:02.028Z SendDataTCPServer.js: TCP/IP server has received 372512 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:02.068Z SendDataTCPServer.js: TCP/IP server has received 374492 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:02.115Z SendDataTCPServer.js: TCP/IP server has received 376472 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:02.284Z SendDataTCPServer.js: TCP/IP server has received 378452 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:02.359Z SendDataTCPServer.js: TCP/IP server has received 380432 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:02.377Z SendDataTCPServer.js: TCP/IP server has received 382412 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:02.501Z SendDataTCPServer.js: TCP/IP server has received 384392 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:02.570Z SendDataTCPServer.js: TCP/IP server has received 386372 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:02.645Z SendDataTCPServer.js: TCP/IP server has received 388352 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:02.678Z SendDataTCPServer.js: TCP/IP server has received 392312 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:02.747Z SendDataTCPServer.js: TCP/IP server has received 394292 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:02.816Z SendDataTCPServer.js: TCP/IP server has received 396272 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:02.886Z SendDataTCPServer.js: TCP/IP server has received 398252 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:02.951Z SendDataTCPServer.js: TCP/IP server has received 400232 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.046Z SendDataTCPServer.js: TCP/IP server has received 402212 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.122Z SendDataConnector.js: CLIENT is data received : 910000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.170Z SendDataTCPServer.js: TCP/IP server has received 404192 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.237Z SendDataTCPServer.js: TCP/IP server has received 406172 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.248Z SendDataConnector.js: CLIENT is data received : 920000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.308Z SendDataTCPServer.js: TCP/IP server has received 408152 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.348Z SendDataTCPServer.js: TCP/IP server has received 410132 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.447Z SendDataTCPServer.js: TCP/IP server has received 412112 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.533Z SendDataTCPServer.js: TCP/IP server has received 414092 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.549Z SendDataConnector.js: CLIENT is data received : 930000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.606Z SendDataTCPServer.js: TCP/IP server has received 416072 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.638Z SendDataTCPServer.js: TCP/IP server has received 418052 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.690Z SendDataTCPServer.js: TCP/IP server has received 420032 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.767Z SendDataTCPServer.js: TCP/IP server has received 422012 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.837Z SendDataTCPServer.js: TCP/IP server has received 423992 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.848Z SendDataConnector.js: CLIENT is data received : 940000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:03.993Z SendDataTCPServer.js: TCP/IP server has received 425972 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.028Z SendDataTCPServer.js: TCP/IP server has received 427952 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.068Z SendDataTCPServer.js: TCP/IP server has received 429932 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.140Z SendDataTCPServer.js: TCP/IP server has received 431912 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.147Z SendDataTCPServer.js: TCP/IP server has received 433892 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.178Z SendDataConnector.js: CLIENT is data received : 950000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.372Z SendDataTCPServer.js: TCP/IP server has received 435872 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.378Z SendDataTCPServer.js: TCP/IP server has received 437852 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.446Z SendDataTCPServer.js: TCP/IP server has received 439832 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.527Z SendDataTCPServer.js: TCP/IP server has received 441812 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.534Z SendDataTCPServer.js: TCP/IP server has received 443792 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.555Z SendDataConnector.js: CLIENT is data received : 960000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.608Z SendDataTCPServer.js: TCP/IP server has received 445772 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.687Z SendDataTCPServer.js: TCP/IP server has received 447752 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.693Z SendDataTCPServer.js: TCP/IP server has received 449732 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.707Z SendDataTCPServer.js: TCP/IP server has received 451712 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.794Z SendDataTCPServer.js: TCP/IP server has received 453692 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.828Z SendDataTCPServer.js: TCP/IP server has received 459632 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.910Z SendDataTCPServer.js: TCP/IP server has received 461612 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:04.979Z SendDataTCPServer.js: TCP/IP server has received 463592 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:05.018Z SendDataTCPServer.js: TCP/IP server has received 465572 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:05.074Z SendDataTCPServer.js: TCP/IP server has received 467552 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:05.108Z SendDataTCPServer.js: TCP/IP server has received 469532 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:05.254Z SendDataTCPServer.js: TCP/IP server has received 471512 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:05.277Z SendDataTCPServer.js: TCP/IP server has received 473492 bytes of data
I/jxcore-log( 4858): 
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4858): 2015-11-21T12:39:05.380Z SendDataTCPServer.js: TCP/IP server has received 475472 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:05.418Z SendDataTCPServer.js: TCP/IP server has received 477452 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:05.554Z SendDataTCPServer.js: TCP/IP server has received 479432 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:05.858Z SendDataTCPServer.js: TCP/IP server has received 481412 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:05.976Z SendDataTCPServer.js: TCP/IP server has received 483392 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.047Z SendDataTCPServer.js: TCP/IP server has received 485372 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.053Z SendDataTCPServer.js: TCP/IP server has received 487352 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.122Z SendDataTCPServer.js: TCP/IP server has received 489332 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.128Z SendDataTCPServer.js: TCP/IP server has received 491312 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.150Z SendDataTCPServer.js: TCP/IP server has received 493292 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.188Z SendDataTCPServer.js: TCP/IP server has received 495272 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.223Z SendDataTCPServer.js: TCP/IP server has received 497252 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.233Z SendDataTCPServer.js: TCP/IP server has received 499232 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.299Z SendDataTCPServer.js: TCP/IP server has received 501212 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.309Z SendDataTCPServer.js: TCP/IP server has received 503192 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.348Z SendDataTCPServer.js: TCP/IP server has received 505172 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.385Z SendDataTCPServer.js: TCP/IP server has received 507152 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.427Z SendDataConnector.js: CLIENT is data received : 990000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.454Z SendDataTCPServer.js: TCP/IP server has received 509132 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.488Z SendDataTCPServer.js: TCP/IP server has received 515072 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.496Z SendDataConnector.js: CLIENT is data received : 1000000
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.499Z SendDataConnector.js: got all data for this round
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.507Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:39:06.507Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4858): 
I/BtConnectorHelper( 4858): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 4858): Stop ReceivingThread
I/BtToSocketBase( 4858): Stop SendingThread
I/BtToSocketBase( 4858): Close local in
,I/BtToSocketBase( 4858): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 4858): Close LocalOutputStream
,I/BtToSocketBase( 4858): Close localHostSocket
I/BtToSocketBase( 4858): Close bt in
,I/BtToSocketBase( 4858): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4858): Close bt out
I/BtToSocketBase( 4858): Close bt socket
I/BtToRequestSocket( 4858): Close server socket
,I/jxcore-log( 4858): 2015-11-21T12:39:06.524Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): ---- round done--------
I/jxcore-log( 4858): 
I/jxcore-log( 4858): do fake peer & start
I/jxcore-log( 4858): 
I/jxcore-log( 4858): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:39:06.527Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:39:06.528Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:39:06.528Z SendDataConnector.js: do connect now
I/jxcore-log( 4858): 
,I/        ( 4858): Selected device address: 58:3F:54:73:64:C0, name: null
,I/BTConnectToThread( 4858): Starting to connect
W/BluetoothAdapter( 4858): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 4858): Connecting to null, at 58:3F:54:73:64:C0
,I/chromium( 4858): [INFO:CONSOLE(63)] "logCallback round[0] time: 45066 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 4919): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 4858): 2015-11-21T12:39:06.545Z SendDataTCPServer.js: TCP/IP server has received 517052 bytes of data
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:06.660Z SendDataTCPServer.js: TCP/IP server has received 519032 bytes of data
I/jxcore-log( 4858): 
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f0351c rs_disc_pending=1
W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4858): 2015-11-21T12:39:06.781Z SendDataTCPServer.js: TCP/IP server has received 521012 bytes of data
I/jxcore-log( 4858): 
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f036dc rs_disc_pending=1
W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4919): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,W/bt-sdp  ( 4919): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 4919): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4919): invalid rfc slot id: 7
,I/BTConnectToThread( 4858): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4858): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4858): 2015-11-21T12:39:12.390Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:39:12.390Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:39:12.391Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4858): 
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=6284 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  320): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 328us total 22.251ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.274ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 22.297ms
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@574f212:true
,I/BTConnectionReceiver( 6284): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6319 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/BluetoothClassifier( 6284): Bluetooth Device Name: Note3-1
,I/ActivityManager(  882): Killing 6008:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10005/pid_6008/cgroup.procs: No such file or directory
,W/bt-btif ( 4919): dm_pm_timer expires
,W/bt-btif ( 4919): dm_pm_timer expires 0
W/bt-btif ( 4919): proc dm_pm_timer expires
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4858): 2015-11-21T12:39:17.392Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:39:17.393Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:22.395Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:22.396Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:39:22.396Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:39:22.396Z SendDataConnector.js: do connect now
I/jxcore-log( 4858): 
,I/        ( 4858): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 4858): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 4858): Starting to connect
W/BluetoothAdapter( 4858): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4919): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4858): Cleared service requests
,I/        ( 4858): Started peer discovery
,I/wpa_supplicant( 4981): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032 vendor_elems=1 level=-58
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
D/MDMCTBK (  302): Event received = P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService(  882):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  882):  WFD CtrlPort: 7236
D/WifiP2pService(  882):  WFD MaxThroughput: 50
D/WifiP2pService(  882):  level: -58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService(  882):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  882):  WFD CtrlPort: 7236
D/WifiP2pService(  882):  WFD MaxThroughput: 50
D/WifiP2pService(  882):  level: -58 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
,D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4858): Found 2 peers.
I/SS      ( 4858): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4858): Peer(2): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 4858): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4858): Added service request
,I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4858): Started service discovery
,I/wpa_supplicant( 4981): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
,D/MDMCTBK (  302): Event received = P2P: Reject scan trigger 
,I/wpa_supplicant( 4981): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-42
,D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/MDMCTBK (  302): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/ActivityManager(  882): Waited long enough for: ServiceRecord{14cf4474 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 4919): invalid rfc slot id: 4
,D/BluetoothMapService( 4919): onReceive
,I/BtToSocketBase( 4858): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4858): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4858): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT1736
I/BtToSocketBase( 4858): Stop ReceivingThread
I/BtToSocketBase( 4858): Stop SendingThread
I/BtToSocketBase( 4858): Close local in
I/BtToSocketBase( 4858): Close LocalOutputStream
I/BtToSocketBase( 4858): Close localHostSocket
I/BtToSocketBase( 4858): Close bt in
I/BtToSocketBase( 4858): Close bt out
I/BtToSocketBase( 4858): Close bt socket
,I/BtToSocketBase( 4858): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4858): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BTConnectionReceiver( 6284): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6284): Bluetooth Device Name: G3s-1
,I/jxcore-log( 4858): 2015-11-21T12:39:28.115Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4858): 
,I/wpa_supplicant( 4981): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  302): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-REMOVED 1 
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=279, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312118, SEQNUM=4499, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=5955, POWER_SUPPLY_CHARGE_COUNTER=74, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1144","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1144","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/        ( 4858): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1144","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 4858): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1144","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT1144, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 4858): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT1144, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP b6:ce:
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-RESP b6:ce:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4548"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4548"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/        ( 4858): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4548"}, typeCordovap2p._tcp.local.:
I/        ( 4858): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT4548"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT4548, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 4858): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT4548, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-ADDED 2 c0
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 4981): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  302): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT2510","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT2510","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/        ( 4858): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT2510","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 4858): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT2510","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT2510, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 4858): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT2510, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-REMOVED 2 
,I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-ADDED 3 c0
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 4981): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-37
,D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  302): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT994","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT994","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/        ( 4858): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT994","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 4858): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT994","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT994, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 4858): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT994, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 4981): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2
,D/MDMCTBK (  302): Event received = P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Android_d8c3
D/WifiP2pService(  882):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Android_d8c3
D/WifiP2pService(  882):  deviceAddress: 02:ee:bd:dd:33:d2
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 02
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 02
,D/TCMD    (  476): NL - Read 1004 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 68 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/wpa_supplicant( 4981): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  302): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  302):  STA Disconnected !!
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): get_property_value, Enter
I/MDMCTBK (  302): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  302): get_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  476): NL - Read 68 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
I/MDMCTBK (  302): send SAR ctrl over QMI
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 4981): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
I/wpa_supplicant( 4981): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  302): Event received = CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  302): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  882): InitialState.processMessage what=4
,E/WifiStateMachine(  882): NETWORK_DISCONNECTION_EVENT in connected state BSSID=c0:ff:d4:d3:aa:48 RSSI=-127 freq=-1 was debouncing=false reason=0 ajst=0
,W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882):  0
,D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  882): Missed CTRL-EVENT-DISCONNECTED, disconnect
E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  882): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 4981): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  300): Clearing all IP addresses on wlan0
,D/TCMD    (  476): NL - Read 60 bytes from update socket.
D/TCMD    (  476): NL - ignore NL message, type = 21
D/TCMD    (  476): Listening for incoming client connection request
,V/NativeCrypto( 1604): Read error: ssl=0xb8811630: I/O error during system call, Connection timed out
,V/NativeCrypto( 1604): SSL shutdown failed: ssl=0xb8811630: I/O error during system call, Broken pipe
,D/ConnectivityService(  882): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,I/jxcore-log( 4858): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 4858): 
I/jxcore-log( 4858): The Coordinator has disconnected!
I/jxcore-log( 4858): 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
I/        ( 4858): Cleared service requests
I/        ( 4858): Started peer discovery
,D/WifiMetrics(  882): connected time updated 375984
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6389 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  882): WifiStateMachine: Leaving Connected state
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/ConnectivityService(  882): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  882): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524292
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Disconnected - quitting
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  882): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1946): CM callback handler got msg 524292
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/ConnectivityService(  882): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1521): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  882): NetworkAgent: NetworkAgent channel lost
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1521): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-REMOVED 3 
,I/art     (  882): Explicit concurrent mark sweep GC freed 35240(1916KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.469ms total 128.271ms
,W/ResourcesManager( 6389): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  476): NL - Read 56 bytes from update socket.
,D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/wpa_supplicant( 4981): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
D/MDMCTBK (  302): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  302): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  882):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  882):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4858): Found 6 peers.
,I/SS      ( 4858): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 4858): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4858): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4858): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 4858): Peer(5): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 4858): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=16 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=16 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState add service request
D/WifiP2pManager( 4858): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4858): Added service request
,I/Babel_SMS( 6389): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6389): MmsConfig.loadMmsSettings
I/Babel_SMS( 6389): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6389): MmsConfig.loadFromDatabase
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-REMOVED 0
,E/Babel_SMS( 6389): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6389): MmsConfig.loadFromResources
,E/Babel_SMS( 6389): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6389): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6389): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6389): startup - clean
,I/Babel   ( 6389): deleted: false for 0
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,W/VideoCapabilities( 6389): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6389): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6389): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6389): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6389): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6389): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6389): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6389): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Killing 6064:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10049/pid_6064/cgroup.procs: No such file or directory
,I/vclib   ( 6389): onServiceConnected
,W/Babel   ( 6389): Attempted to change video mute state without an active call.
,I/wpa_supplicant( 4981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 4858): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4858): 
I/jxcore-log( 4858): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 4858): 
I/jxcore-log( 4858): printNetworkInfo
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): found interfaceName: lo
I/jxcore-log( 4858): 
I/jxcore-log( 4858): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 4858): 
I/jxcore-log( 4858): Turning Wifi off
I/jxcore-log( 4858): 
D/WifiService(  882): setWifiEnabled: false pid=4858, uid=10306
,E/WifiService(  882): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings( 1466): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,E/wpa_supplicant( 4981): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
E/wpa_supplicant( 4981): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/Settings( 1466): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  882): [1,448,109,591,506 ms] noteScanEnd no scan source
D/WifiP2pService(  882): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  882): SCAN_AVAILABLE : 1
D/RttService(  882): SCAN_AVAILABLE : 1
,D/WifiP2pService(  882): discovery change broadcast false
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
D/WifiP2pService(  882): P2pDisablingState
D/WifiScanningService(  882): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  882): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): p2p socket connection lost
,D/WifiP2pService(  882): P2pDisabledState
,E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - enter - invokeEnterMethods
E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
,D/WifiP2pService(  882): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 4981): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  300): Clearing all IP addresses on wlan0
,I/jxcore-log( 4858): Turning Wifi back on
I/jxcore-log( 4858): 
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiService(  882): setWifiEnabled: true pid=4858, uid=10306
E/WifiService(  882): Invoking mWifiStateMachine.setWifiEnabled
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): stopping supplicant
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): setWifiState: disabling
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/wpa_supplicant( 4981): eap_proxy Deinitialzed
,D/WifiController(  882): WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 455ms
,W/Settings( 1466): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1466): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/jxcore-log( 4858): toggleWiFi finished
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): ReconnectWifiAP finished
I/jxcore-log( 4858): 
D/TCMD    (  476): NL - Read 1004 bytes from update socket.
,D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/wpa_supplicant( 4981): wlan0: CTRL-EVENT-TERMINATING 
D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  302): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  302):  Wpa Supplicant Exiting !!
D/MDMCTBK (  302): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  302): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  302): wifi_close_sockets: Exit
,E/WifiStateMachine(  882): Supplicant connection lost
,I/        ( 4858): Discovery state changed to Stopped.
,I/WB      ( 4858): Wifi is DISABLED !!
I/        ( 4858): Stoping All
D/WifiP2pService(  882): P2pDisabledState{ when=0 what=139265 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139265 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 4858): Stopping services
I/        ( 4858): Stopping services
D/WifiP2pService(  882): P2pDisabledState{ when=0 what=139298 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=-1ms what=139298 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4858): Stop Bluetooth
,I/        ( 4858): Stop Bluetooth
,I/BTListenerThread( 4858): Stopped
I/BTConnectToThread( 4858): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/WifiP2pService(  882): P2pDisabledState{ when=0 what=139307 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139307 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
E/bt-btif ( 4919): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:8, channel:-1
I/chromium( 4858): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
D/WifiP2pService(  882): P2pDisabledState{ when=-1ms what=139268 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=-1ms what=139268 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 4858): Starting peer discovery failed, error code 2
I/        ( 4858): Clearing local services failed, error code 2
I/CONNEC  ( 4858): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 4858): 2015-11-21T12:39:51.571Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:39:51.572Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:51.574Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:51.575Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 4858): 
I/jxcore-log( 4858): ---- round done--------
I/jxcore-log( 4858): 
I/jxcore-log( 4858): ---- gotta redo : 58:3F:54:73:64:C0, try count now: 1
I/jxcore-log( 4858): 
I/jxcore-log( 4858): do fake peer & start
I/jxcore-log( 4858): 
I/jxcore-log( 4858): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:39:51.576Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4858): 
I/jxcore-log( 4858): 2015-11-21T12:39:51.576Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): 2015-11-21T12:39:51.576Z SendDataConnector.js: do connect now
I/jxcore-log( 4858): 
D/AndroidRuntime( 4858): Shutting down VM
I/BtConnection( 4858): Got uncaughtException: java.lang.RuntimeException: Connector class is not initialized properly
,E/QC-QMI  (  388): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  388): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  388): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
,E/QC-QMI  (  388): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
E/QC-QMI  (  388): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,D/Checkin ( 2895): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,E/WifiStateMachine(  882): setWifiState: disabled
,W/Settings( 6389): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 1741): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Checkin ( 2895): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2895): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2895): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiController(  882): DEFERRED_TOGGLE handled
E/WifiStateMachine(  882): setting operational mode to 1
,D/TCMD    (  476): NL - Read 444 bytes from update socket.
D/TCMD    (  476): NL - ignore NL message, type = 17
D/TCMD    (  476): Listening for incoming client connection request
,D/TCMD    (  476): NL - Read 1004 bytes from update socket.
,D/TCMD    (  476): NL - message type is RTM_NEWLINK
,D/TCMD    (  476): Listening for incoming client connection request
,D/TCMD    (  476): NL - Read 444 bytes from update socket.
,D/TCMD    (  476): NL - ignore NL message, type = 17
,D/TCMD    (  476): Listening for incoming client connection request
,I/MDMCTBK (  302): NetlinkHandler, wifiStateChanged 0
,I/MDMCTBK (  302): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
,D/TCMD    (  476): NL - Read 1008 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  882): InitialState.processMessage what=4
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  476): NL - Read 1008 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,D/QsoftapCmd(  300): Got softap fwreload command we are passing on
D/SoftapController(  300): Softap fwReload - Ok
,D/CommandListener(  300): Setting iface cfg
D/CommandListener(  300): Trying to bring down wlan0
,D/CommandListener(  300): Clearing all IP addresses on wlan0
,I/wpa_supplicant( 6460): Successfully initialized wpa_supplicant
I/wpa_supplicant( 6460): Long line in configuration file truncated
,I/wpa_supplicant( 6460): rfkill: Cannot open RFKILL control device
,D/TCMD    (  476): NL - Read 1004 bytes from update socket.
,D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,D/TCMD    (  476): NL - Read 1004 bytes from update socket.
,D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/libmdmdetect( 6460): ESOC framework not supported
,E/Diag_Lib( 6460):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
E/wpa_supplicant( 6460): baseband property is set to [msm]
I/libmdmdetect( 6460): ESOC framework not supported
,E/wpa_supplicant( 6460):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 6460): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 6460): card_info[i].card_state: 0x0
,E/wpa_supplicant( 6460): card_info[i].error_code: 0x0
E/wpa_supplicant( 6460): SIM/USIM not ready
E/wpa_supplicant( 6460): Error while reading SIM card status
,E/wpa_supplicant( 6460): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/WifiStateMachine(  882): setWifiState: enabling
E/wpa_supplicant( 6460): card_info[i].card_state: 0x0
,E/wpa_supplicant( 6460): card_info[i].error_code: 0x0
E/wpa_supplicant( 6460): SIM/USIM not ready
I/wpa_supplicant( 6460): eap_proxy: Card not ready
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): Supplicant start successful
D/WifiMonitor(  882): startMonitoring(wlan0) with mConnected = false
,E/wpa_supplicant( 6460): Line 31: unknown global field 'o'.
E/wpa_supplicant( 6460): Line 31: Invalid configuration line 'o'.
I/wpa_supplicant( 6460): rfkill: Cannot open RFKILL control device
,D/TCMD    (  476): NL - Read 1004 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,E/wpa_supplicant( 6460): baseband property is set to [msm]
I/libmdmdetect( 6460): ESOC framework not supported
,E/wpa_supplicant( 6460):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 6460): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 6460): card_info[i].card_state: 0x0
E/wpa_supplicant( 6460): card_info[i].error_code: 0x0
E/wpa_supplicant( 6460): SIM/USIM not ready
E/wpa_supplicant( 6460): Error while reading SIM card status
,E/wpa_supplicant( 6460): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 6460): card_info[i].card_state: 0x0
E/wpa_supplicant( 6460): card_info[i].error_code: 0x0
E/wpa_supplicant( 6460): SIM/USIM not ready
I/wpa_supplicant( 6460): eap_proxy: Card not ready
,E/WifiStateMachine(  882): setSuspendOptimizations: 2 true
,E/WifiStateMachine(  882): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  882): Supplicant connection established
E/WifiStateMachine(  882): setWifiState: enabled
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiConfigStore(  882): Loading config and enabling all networks 
,E/WifiConfigStore(  882):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  882):  got CRC SSID "NG7005g" -> 1656539502
E/WifiConfigStore(  882): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 6389): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  882): Setting external_sim to 1
,D/WifiStateMachine(  882): Setting OUI to DA-A1-19
I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2dda89c
D/wifi    (  882): halHandle = 0x0, mVM = 0xb8572310, mCls = 0x1b7e
I/WifiNative-HAL(  882): Could not start hal
,E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/wpa_supplicant( 6460): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/native  (  882): do suspend true
,D/WifiScanningService(  882): SCAN_AVAILABLE : 3
,D/RttService(  882): SCAN_AVAILABLE : 3
D/WifiP2pService(  882): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  882): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  882): startHal
D/RttService(  882): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  300): Setting iface cfg
D/CommandListener(  300): Trying to bring up p2p0
D/WifiMonitor(  882): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  882): P2pEnablingState
D/WifiP2pService(  882): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2p socket connection successful
D/WifiP2pService(  882): P2pEnabledState
D/WifiP2pService(  882): sending p2p connection changed broadcast
E/WifiStateMachine(  882): set country code US
,E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa19029cc
D/wifi    (  882): halHandle = 0x0, mVM = 0xb8572310, mCls = 0x1b7a
I/WifiNative-HAL(  882): Could not start hal
E/WifiScanningService(  882): could not start HAL
,E/WifiStateMachine(  882): set frequency band 2
,I/wpa_supplicant( 6460): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiNative-HAL(  882): p2pGetDeviceAddress
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info0x
,D/WifiNative-HAL(  882): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  882): DeviceAddress: 44:80:eb:7b:5a:07
,D/WifiP2pService(  882): MCC mode enabled 0
,D/WifiP2pService(  882): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  882): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  882): InactiveState
D/WifiP2pService(  882): InactiveState{ when=-17ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-17ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  882): InactiveState{ when=-22ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-22ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/MDMCTBK (  302): NetlinkHandler, wifiStateChanged 1
,I/MDMCTBK (  302): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): wifi_connect_to_supplicant, current pid is = 302
D/MDMCTBK (  302): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  302): wifi_close_sockets: Exit
E/MDMCTBK (  302): Attach monitor thread
I/MDMCTBK (  302): createWifiMonitorThread: Started the wifi monitor thread -1195581640
D/MDMCTBK (  302): wifi_wait_on_socket: Enter monitor thread
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2489): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1466): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2489): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2489): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2489): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6479 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/Tethering(  882): MasterInitialState.processMessage what=3
,D/PollingManager( 2489): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1466): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2489): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2489): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2489): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2489): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2489): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2489): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2489): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2489): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2489): [debug] > CusSM.onRadioDown
,D/Central_PollingManager( 1466): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2489): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2489): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2489): Registering with Alarm Manager to restart CCE
,W/bt-sdp  ( 4919): SDP - Rcvd conn cnf with error: 0x22  CID 0x45
E/bt-btif ( 4919): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4919): invalid rfc slot id: 8
,I/MusicStore( 6479): Database version: 120
,D/TCMD    (  476): NL - Read 1004 bytes from update socket.
,D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6479): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6479): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6479): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/bt-btif ( 4919): info:x10
D/        ( 4919): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,W/ResourcesManager( 6479): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6479): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6479): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 6479): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6479): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12e51683: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6479): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6479): GMSCore installation verified
,I/ConfigStore( 6479): Config Database version: 1
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledStateupdate channel list
,I/MediaRouter( 6479): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6479): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6511 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6479): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6479): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 6105:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10057/pid_6105/cgroup.procs: No such file or directory
,V/Mms     ( 6511): mnc/mcc: 
,V/Mms     ( 6511): tag: int value: recipientLimit - 20
,V/Mms     ( 6511): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6511): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6511): tag: int value: maxSubjectLength - 80
V/Mms     ( 6511): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6511): tag: bool value: enableGroupMms - false
,V/Mms     ( 6511):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6511): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6537 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6181:com.android.settings/1000 (adj 15): empty #7
,D/PhoneMonitor( 6537): Register our PhoneStateListener
,W/libprocessgroup(  882): failed to open /acct/uid_1000/pid_6181/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6537): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6537): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 1946): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1946): num queued entries: 0
,I/iu.UploadsManager( 1946): num updated entries: 0
,I/iu.SyncManager( 1946): NEXT; no task
,D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  882): Killing 6319:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_6319/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6561 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6582 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 6389): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  882): Killing 6284:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_6284/cgroup.procs: No such file or directory
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6582): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6582): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6582): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6582):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6582):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6582): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6582): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6582): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6582): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6582): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6582): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6582): Time to load native libraries: 2 ms (timestamps 7326-7328)
I/LibraryLoader( 6582): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6582): Binding Chromium to main looper Looper (main, tid 1) {358af12a}
,I/LibraryLoader( 6582): Expected native library version number "",actual native library version number ""
,I/chromium( 6582): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6582): Initializing chromium process, singleProcess=true
,W/art     ( 6582): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6582): ApplicationContext is null in ApplicationStatus
,W/chromium( 6582): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6582): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6582): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6582): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6582): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6582): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6582): Local Branch: 
I/Adreno-EGL( 6582): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6582): Local Patches: NONE
I/Adreno-EGL( 6582): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6582): Requires BLUETOOTH permission
,I/NSApplication( 6582): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6644 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6479:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_6479/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6666 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6511:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_6511/cgroup.procs: No such file or directory
,W/ResourcesManager( 6666): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6686 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6707 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6561:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  320): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 442us total 21.720ms
,D/WifiP2pService(  882): InactiveState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/art     (  320): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 21.076ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 20.420ms
,I/ContactLocale( 6686): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 6537:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_6561/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_6537/cgroup.procs: No such file or directory
,I/MusicStore( 6707): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6707): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     (  882): Explicit concurrent mark sweep GC freed 33155(1686KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.399ms total 123.075ms
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6707): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6707): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6707): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6707): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6707): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 6707): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6707): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12e51683: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6707): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6707): GMSCore installation verified
,I/ConfigStore( 6707): Config Database version: 1
,I/MediaRouter( 6707): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6707): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6753 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6707): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6707): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 6389:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 6753): mnc/mcc: 
V/Mms     ( 6753): tag: int value: recipientLimit - 20
V/Mms     ( 6753): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6753): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6753): tag: int value: maxSubjectLength - 80
V/Mms     ( 6753): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6753): tag: bool value: enableGroupMms - false
V/Mms     ( 6753):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_6389/cgroup.procs: No such file or directory
,W/ResourcesManager( 6753): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6787 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6582:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/MDMCTBK (  302): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
,D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  302): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 38:f8:89:11:e9:11
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-ADDED 1 38:f8:89:11:e9:11
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  302): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  302): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  476): NL - Read 56 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2dda8fc
D/wifi    (  882): halHandle = 0x0, mVM = 0xb8572310, mCls = 0x2019a6
I/WifiNative-HAL(  882): Could not start hal
E/WifiStateMachine(  882): [1,448,109,597,510 ms] noteScanEnd no scan source
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1992f0df sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  882): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  882):  rewrite network history for "NG700"WPA_PSK
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_6582/cgroup.procs: No such file or directory
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  882): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,D/PhoneMonitor( 6787): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6787): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6787): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  882): Killing 6644:com.android.chrome/u0a52 (adj 15): empty #7
,E/WifiConfigStore(  882): will read network variables netId=0
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_6644/cgroup.procs: No such file or directory
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  882): will read network variables netId=0
,I/wpa_supplicant( 6460): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  302): Event received = Trying to associate with
D/WifiMonitor(  882): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 6460): DSDS: eapol_sm_notify_config config->sim_num = 1
E/WifiConfigStore(  882): setLastSelectedConfiguration -1
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6809 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/wpa_supplicant( 6460): PNO: In assoc process
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6832 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  882): Killing 6666:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_6666/cgroup.procs: No such file or directory
,W/ResourcesManager( 6832): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 02
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 02
,D/TCMD    (  476): NL - Read 312 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 88 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 68 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 1004 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/TCMD    (  476): NL - Read 80 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 80 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
D/TCMD    (  476): NL - Read 68 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
,I/wpa_supplicant( 6460): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  302): Event received = Associated with c0:ff:d4
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 6460): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6460): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  302): Event received = WPA: Key negotiation com
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  302): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  302):  STA Connected !!
D/TCMD    (  476): NL - Read 1004 bytes from update socket.
D/TCMD    (  476): NL - message type is RTM_NEWLINK
D/TCMD    (  476): Listening for incoming client connection request
E/MDMCTBK (  302): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2462, reply_len: 4, ret: 0
,D/MDMCTBK (  302): get_freq !!, resp=2462
I/MDMCTBK (  302): get_freq !!, Strip data
I/MDMCTBK (  302): get_freq !!, band = 2, freq = 2462
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): get_property_value, Enter
I/MDMCTBK (  302): get_property_value, Values read from property=0,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  302): get_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  302): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  302): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  302): MdmCutbackHndler, set WIFI TX pwr !!
,I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
,I/MDMCTBK (  302): get_property_value, Enter
I/MDMCTBK (  302): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  302): get_property_value, Exit
,I/MDMCTBK (  302): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1195565768
I/MDMCTBK (  302): return from set_get_from_wpa_supplicant
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,D/MDMCTBK (  302): wifi_set_tx_pwr: SETTXPOWER = 18
,I/MDMCTBK (  302): send SAR ctrl over QMI
D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  302): Event received = CTRL-EVENT-STATE-CHANGE 
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/MDMCTBK (  302): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  302): , reply_len: 3, ret: 0
E/MDMCTBK (  302): MdmCutbackHndler, resp=OK
E/MDMCTBK (  302): 
D/MDMCTBK (  302): wifi_set_tx_pwr: Exit
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  882): Network connection established
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  882): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  882): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  882): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  882): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  300): Setting iface cfg
,E/WifiStateMachine(  882): Start Dhcp Watchdog 2
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend false
,E/wpa_supplicant( 6460): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
E/wpa_supplicant( 6460): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@74b50f3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@74b50f3 target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_SMS( 6832): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6832): MmsConfig.loadMmsSettings
I/Babel_SMS( 6832): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6832): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6832): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6832): MmsConfig.loadFromResources
E/Babel_SMS( 6832): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6832): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6832): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6832): startup - clean
,I/Babel   ( 6832): deleted: false for 0
,E/DHCPCD  ( 6871): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
I/DHCPCD  ( 6871): version 5.5.6 starting
E/DHCPCD  ( 6871): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6871): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6871): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6873 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,W/VideoCapabilities( 6832): Unrecognized profile 2130706433 for video/avc
,D/DHCPCD  ( 6871): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6871): wlan0: rebinding lease of 192.168.1.134
D/DHCPCD  ( 6871): wlan0: sending REQUEST (xid 0xb80734ae), next in 4.72 seconds
,W/AudioCapabilities( 6832): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6832): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6832): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6832): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6832): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6832): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6832): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6832): onServiceConnected
W/Babel   ( 6832): Attempted to change video mute state without an active call.
I/Babel   ( 6832): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  882): Killing 6686:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_6686/cgroup.procs: No such file or directory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6873): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6873): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6873): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6873):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6873):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6873): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6873): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6873): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6873): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6873): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6873): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6873): Time to load native libraries: 2 ms (timestamps 756-758)
,I/LibraryLoader( 6873): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6873): Binding Chromium to main looper Looper (main, tid 1) {358af12a}
,I/LibraryLoader( 6873): Expected native library version number "",actual native library version number ""
,I/chromium( 6873): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6873): Initializing chromium process, singleProcess=true
W/art     ( 6873): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6873): ApplicationContext is null in ApplicationStatus
,W/chromium( 6873): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6873): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6873): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6873): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6873): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6873): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6873): Local Branch: 
I/Adreno-EGL( 6873): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6873): Local Patches: NONE
I/Adreno-EGL( 6873): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6873): Requires BLUETOOTH permission
,I/NSApplication( 6873): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6946 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6707:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_6707/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6965 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6753:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_6753/cgroup.procs: No such file or directory
,W/ResourcesManager( 6965): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6985 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6809:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ActivityManager(  882): Killing 6787:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/ContactLocale( 6985): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_6809/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2489): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_6787/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2489): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2489): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2489): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2489): onServiceConnected()
,D/GetNotificationsWS( 2489): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2489): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7009 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/ActivityManager(  882): Killing 6832:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_6832/cgroup.procs: No such file or directory
,V/AlarmManager(  882): send {25fbb27b, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {3009e26e, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  882): send {6471d0f, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  882): done {3009e26e, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [9ms]
,V/AlarmManager(  882): done {6471d0f, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [12ms]
,I/DHCPCD  ( 6871): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/art     (  882): Explicit concurrent mark sweep GC freed 24666(1217KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.917ms total 123.732ms
,I/DHCPCD  ( 6871): wlan0: leased 192.168.1.134 for 86400 seconds
,D/DHCPCD  ( 6871): wlan0: adding IP address 192.168.1.134/24
,D/DHCPCD  ( 6871): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6871): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6871): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  476): NL - Read 60 bytes from update socket.
D/TCMD    (  476): NL - ignore NL message, type = 20
D/TCMD    (  476): Listening for incoming client connection request
D/DHCPCD  ( 6871): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,V/AlarmManager(  882): done {25fbb27b, *alarm*:android.intent.action.TIME_TICK} [168ms]
,I/EventLogService( 1946): Aggregate from 1448109220460 (log), 1448107774189 (data)
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7057 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7057): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): WifiStateMachine DHCP successful
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  882): Calling ARP set with IP = 192.168.1.134
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  882): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
E/WifiStateMachine(  882): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel_SMS( 7057): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7057): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7057): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7057): MmsConfig.loadFromDatabase
,E/ConnectivityService(  882): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  882): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  882): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  882): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  882): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  882): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  882):    accepting network in place of null
D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  882): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1946): CM callback handler got msg 524290
I/ModemStatsDSDetect( 1521): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/Babel_SMS( 7057): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7057): MmsConfig.loadFromResources
E/Babel_SMS( 7057): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7057): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7057): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7057): startup - clean
,I/Babel   ( 7057): deleted: false for 0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 21 Nov 2015 12:40:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448109601221], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448109601185]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Validated
D/ConnectivityService(  882): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1946): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1521): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1521): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7057): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7057): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7057): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7057): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Killing 6873:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,E/libprocessgroup(  882): failed to kill 1 processes for processgroup 6873
,I/vclib   ( 7057): onServiceConnected
,W/Babel   ( 7057): Attempted to change video mute state without an active call.
,D/ConnectivityService(  882): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/PollingManager( 2489): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2489): now: 795652 ,futureTime: 9223372036854775807
,D/PollingManager( 2489): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2489): now: 795656 ,futureTime: 9223372036854775807
,D/PollingManager( 2489): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2489): now: 795658 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2489): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1466): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7125 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Central_PollingManager( 1466): now: 795729 ,futureTime: 86473430
D/Central_PollingManager( 1466): Polling alarm set to expire at: 86473430 Current Time: 795729
,D/OtaApp  ( 2489): [debug] > PollingManagerService, now: 795728 ,futureTime: 74858148
D/OtaApp  ( 2489): [debug] > Polling alarm set to expire at: 74858148 Current Time: 795732
,D/OtaApp  ( 2489): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2489): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2489): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/art     (  320): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 48.321ms
,D/OtaApp  ( 2489): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2489): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2489): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2489): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2489): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2489): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2489): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/art     (  320): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 19.165ms
,D/MMApiProvisionService( 2489): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2489): trying to auto login since I haven't yet and the radio is up now
I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.174ms
I/MMApiProvisionService( 2489): createDeviceIdOrLogin update_device
D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2489): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2489): isDeviceProvisioned: deviceId = 2072049230914535424
,I/MusicStore( 7125): Database version: 120
,I/art     ( 2489): Explicit concurrent mark sweep GC freed 43333(2MB) AllocSpace objects, 6(142KB) LOS objects, 40% free, 11MB/19MB, paused 1.075ms total 88.728ms
,D/CCE     ( 2489): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2489): createDeviceIdOrLogin update_device
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7125): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/MMApiProvisionService( 2489): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2489): set mOutstandingReq to true.
I/ Nonce  ( 2489):  Nonce getNonce 
I/ Nonce  ( 2489):  Nonce Request 
I/ Nonce  ( 2489):  Nonce execute Request 
,D/MMApiWebService( 2489): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2489): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2489): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2489): createDeviceIdOrLogin update_device
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2489): Not proxy app, so login/provision not allowed
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7125): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7125): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 6109(321KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/12MB, paused 1.603ms total 42.345ms
,D/MMApiWebService( 2489): generating token using payload instead of using session token
,W/ResourcesManager( 7125): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7125): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ Nonce  ( 2489):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2489): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,V/JNIHelp ( 7125): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 7125): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7125): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12e51683: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7125): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7125): GMSCore installation verified
,I/ConfigStore( 7125): Config Database version: 1
,I/MediaRouter( 7125): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7125): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7125): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7125): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7174 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7125): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7125): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 6946:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_6946/cgroup.procs: No such file or directory
,V/Mms     ( 7174): mnc/mcc: 
,V/Mms     ( 7174): tag: int value: recipientLimit - 20
V/Mms     ( 7174): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7174): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7174): tag: int value: maxSubjectLength - 80
V/Mms     ( 7174): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7174): tag: bool value: enableGroupMms - false
V/Mms     ( 7174):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7174): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7200 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6965:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_6965/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7200): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7200): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7200): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 1946): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1946): num queued entries: 0
I/iu.UploadsManager( 1946): num updated entries: 0
I/iu.SyncManager( 1946): NEXT; no task
,I/ActivityManager(  882): Killing 6985:android.process.acore/u0a7 (adj 15): empty #7
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:32000 mC
,I/art     (  882): Explicit concurrent mark sweep GC freed 17594(870KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.858ms total 115.065ms
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_6985/cgroup.procs: No such file or directory
,I/CheckinService( 1946): Checkin interval check for package: unspecified last checkin: 1448109226335 min interval config: 0 actual interval: 378997
,I/CheckinService( 1946): Checking schedule, now: 1448109605338 next: 1448109256284
,I/CheckinService( 1946): active receiver: enabled
,I/CheckinService( 1946): Preparing to send checkin request
I/EventLogService( 1946): Accumulating logs since 1448109600739
D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 1946): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7225 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 1946): Failed to find provider info for com.google.android.wearable.settings
,I/Babel   ( 7057): connection state changed from UNKNOWN to CONNECTED
,I/art     ( 1604): Explicit concurrent mark sweep GC freed 4424(280KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 11MB/15MB, paused 706us total 64.443ms
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7225): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7225): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7225): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7225):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7225):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7225): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7225): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7257 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/GAv4    ( 7225): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7225): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7225): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 7257): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7257): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7257): VM with version 2.1.0 has multidex support
I/MultiDex( 7257): install
I/MultiDex( 7257): VM has multidex support, MultiDex support library is disabled.
,I/ Nonce  ( 2489):  Nonce Reponse 
D/        ( 2489): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"0fb1c5cc-e689-4bf8-b335-14a4623a38c3"}
D/MMApiWSBase( 2489): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2489):  Nonce Handle Reponse 
D/MMApiProvisionService( 2489): mOutstandingReq set to false
,V/JNIHelp ( 7257): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/MMApiProvisionService( 2489):  pTime 1448098307998 sExp 172742 cTime 1448109605815 tTime 1448271049998
D/MMApiProvisionService( 2489):  No login Required 
,W/ActivityThread( 7257): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7257): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e5b6988: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7257): Installed default security provider GmsCore_OpenSSL
,I/art     ( 7257): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 7257): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/WebViewFactory( 7225): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7225): Time to load native libraries: 1 ms (timestamps 7530-7531)
I/LibraryLoader( 7225): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7225): Binding Chromium to main looper Looper (main, tid 1) {f8044b8}
,I/LibraryLoader( 7225): Expected native library version number "",actual native library version number ""
,I/chromium( 7225): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7225): Initializing chromium process, singleProcess=true
,W/art     ( 7225): Attempt to remove local handle scope entry from IRT, ignoring
,D/NativeLibraryUtils( 7257): Install completed successfully. count=13 extracted=0
,E/SysUtils( 7225): ApplicationContext is null in ApplicationStatus
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
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,W/chromium( 7225): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7225): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7225): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7225): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7225): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7225): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7225): Local Branch: 
I/Adreno-EGL( 7225): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7225): Local Patches: NONE
I/Adreno-EGL( 7225): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fc2000
,E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fc2000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb549d960
D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb798c718, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb79e3ac8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb7abed30, idLength=0xb13b3730
,D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: starts!
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
D/WVCdm   (  308): PrepareKeyRequest: nonce=2581454259
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7a73478
D/DrmWidevineDash(  308): message_length=1591, signature=0xb7991dd8, signature_length=2973447956
,W/AudioManagerAndroid( 7225): Requires BLUETOOTH permission
,I/NSApplication( 7225): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7312 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/DataUsage( 2489): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
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
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7332 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 7125:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_7125/cgroup.procs: No such file or directory
,W/ResourcesManager( 7332): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WVCdm   (  308): CdmEngine::OpenSession
I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  308): Service_Initialize: starts!
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,I/MDMCTBK (  302): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  302): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
,I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
,E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fc2000
E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fc2000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb559d960
D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb7ab2c28, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb79e3ac8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb7abed50, idLength=0xb13b3730
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
D/WVCdm   (  308): PrepareKeyRequest: nonce=1020311179
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7a73478
D/DrmWidevineDash(  308): message_length=1626, signature=0xb7ab8238, signature_length=2973447956
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7357 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  308): CdmEngine::CloseSession
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  308): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  308): L3 Terminate.
D/DrmWidevineDash(  308): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  308): Service_Uninitialize: starts!
D/QSEECOMAPI: (  308): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  308): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  308): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  882): Killing 7200:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 7357): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 7174:com.android.mms/u0a23 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2489): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7200/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_7174/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2489): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2489): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2489): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2489): onServiceConnected()
,D/GetNotificationsWS( 2489): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2489): unbindWebServices(): un-registering our AIDL callback...
D/OtaApp  ( 2489): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2489): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2489): [debug] > In cancelAnyPendingIntentSetPreviously
,I/PushService( 2489): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  882): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2489): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2489): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2489): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2489): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2489): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2489): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2489): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2489): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2489): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2489): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2489): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2489): publish the event [tag = MOT_OTA event name = LOG]
,D/WearableService( 1741): callingUid 10016, callindPid: 1741
,E/MDM     ( 1741): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1604): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/LocationInitializer( 1946): Restart initialization of location
,D/AuthorizationBluetoothService( 1604): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1946): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/GCoreFlp( 1741): No location to return for getLastLocation()
,W/FusedLocationProvider( 1604): location=null
,W/bt-btif ( 4919): info:x10
D/        ( 4919): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/dex2oat ( 7393): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7393): dex2oat took 56.016ms (threads: 4)
,I/Adreno-EGL( 7257): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7257): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7257): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7257): Local Branch: 
I/Adreno-EGL( 7257): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7257): Local Patches: NONE
I/Adreno-EGL( 7257): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7257): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7257): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7257): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7257): Local Branch: 
I/Adreno-EGL( 7257): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7257): Local Patches: NONE
I/Adreno-EGL( 7257): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7257): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7257): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7257): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7257): Local Branch: 
I/Adreno-EGL( 7257): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7257): Local Patches: NONE
I/Adreno-EGL( 7257): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7257): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7257): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7257): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7257): Local Branch: 
I/Adreno-EGL( 7257): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7257): Local Patches: NONE
I/Adreno-EGL( 7257): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 1946): Classify the device as Phone.
,I/CheckinTask( 1946): Sending checkin request (9437 bytes)
,I/CheckinRequestBuilder( 1946): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1946): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  882): Explicit concurrent mark sweep GC freed 12245(569KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.820ms total 118.623ms
,I/CheckinRequestBuilder( 1946): Classify the device as Phone.
,I/CheckinTask( 1946): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1946): Checking schedule, now: 1448109608865 next: 1448710745859
I/CheckinService( 1946): active receiver: disabled
,D/CheckinService( 1946): Recording last checkin time for package unspecified as 1448109608876
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7420 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7420): Register our PhoneStateListener
,V/SetupWizard( 7420): Connected to Gservices successfully
,I/ActivityManager(  882): Killing 7225:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_7225/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1604): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ActivityManager(  882): Killing 7332:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  882): Killing 7312:com.android.chrome/u0a52 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7332/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7312/cgroup.procs: No such file or directory
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=289, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312819, SEQNUM=4600, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=7571, POWER_SUPPLY_CHARGE_COUNTER=139, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/MDMCTBK (  302): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  302): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
,I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  302): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  302): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
,I/MDMCTBK (  302): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:32000 mC,
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7443 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/MDMCTBK (  302): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  302): NetlinkHandler, interfaceAdded
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
E/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  302): , Wifi = 0
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
,I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@170e3a2b
,V/GmsNetworkLocationProvi( 1741): DISABLE
,I/GCoreNlp( 1741): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1557): Deferring update until onResume
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7480 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7499 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  320): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 317us total 21.031ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.743ms
,W/ResourcesManager( 7057): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7057): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/asset   ( 7499): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7499): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7499): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7499): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.737ms
,V/JNIHelp ( 7057): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7531 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/System  ( 7057): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7057): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  882): Killing 7009:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7009/cgroup.procs: No such file or directory
,D/Finsky  ( 7531): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/bt-btif ( 4919): info:x10
D/        ( 4919): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/Finsky  ( 7531): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7531): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7531): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7531): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7531): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7531): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Ads     ( 7531): Skipping gmscore version check
,I/UpdateIcingCorporaServi( 7443): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/Finsky  ( 7531): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/Launcher( 1557): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@363e9509 new=com.google.android.velvet.VelvetApplication@363e9509
,D/PackageBroadcastService( 1946): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7581 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 1946): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1946): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7581): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7443): UpdateCorporaTask done [took 150 ms] updated apps [took 150 ms] 
,I/ActivityManager(  882): Killing 7420:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7420/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 7257:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_7257/cgroup.procs: No such file or directory
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ActivityManager(  882): Killing 7480:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_7480/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 7057:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7057/cgroup.procs: No such file or directory
,I/MDMCTBK (  302): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  302): NetlinkHandler, interfaceAdded
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
E/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  302): , Wifi = 0
I/MDMCTBK (  302): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
I/MDMCTBK (  302): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  302): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  302): set_property_value, Enter
I/MDMCTBK (  302): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  302): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  302): set_property_value, Exit
E/MDMCTBK (  302): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  882): send {249f4160, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  882): done {249f4160, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [15ms]
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=281, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312698, SEQNUM=4612, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=5450, POWER_SUPPLY_CHARGE_COUNTER=167, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311985, SEQNUM=4614, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1614, POWER_SUPPLY_CHARGE_COUNTER=4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
,I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=272, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312556, SEQNUM=4616, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-9, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16a029c4:true
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: A5-1
,I/ActivityManager(  882): Killing 7499:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_7499/cgroup.procs: No such file or directory
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: A5-1
,I/art     (  882): Explicit concurrent mark sweep GC freed 20375(1074KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.424ms total 157.301ms
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=272, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311968, SEQNUM=4628, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=-11, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ActivityManager(  882): Waited long enough for: ServiceRecord{83b0ad u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ClearcutLoggerApiImpl( 1604): disconnect managed GoogleApiClient
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=271, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4313132, SEQNUM=4629, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=6561, POWER_SUPPLY_CHARGE_COUNTER=3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  302): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4313102, SEQNUM=4631, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312828, SEQNUM=4632, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3230, POWER_SUPPLY_CHARGE_COUNTER=-3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312807, SEQNUM=4634, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=8781, POWER_SUPPLY_CHARGE_COUNTER=25, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  882): send {25fbb27b, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {2ab51fe2, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/LaunchCheckinHandler(  882): cleanup(): cleared. Last call was 284499 ms ago
I/ActivityManager(  882): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7671 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  882): done {25fbb27b, *alarm*:android.intent.action.TIME_TICK} [97ms]
,I/GAv4    ( 7671): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7671):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7671):   adb logcat -s GAv4
,W/GAv4    ( 7671): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7671): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7671): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  882): done {2ab51fe2, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [228ms]
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312789, SEQNUM=4640, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=193, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=267, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312478, SEQNUM=4642, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=186, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  882): User[0] Flushing usage stats to disk
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4919): info:x10
,W/bt_mct  ( 4919): dropping incomplete ACL frame
,D/        ( 4919): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 6, f, 410d
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f0469c rs_disc_pending=1
,W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=267, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312495, SEQNUM=4645, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=120, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [80:01:84:8a:b3:68]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f0351c rs_disc_pending=1
,W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f04a1c rs_disc_pending=0
,W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f03a5c rs_disc_pending=1
,W/bt-btif ( 4919): bta_dm_check_av:0
W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f0351c rs_disc_pending=1
,W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312517, SEQNUM=4654, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312513, SEQNUM=4656, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-5, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [f4:f1:e1:5c:3b:e2]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 6, 1d, 7d3
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [08:ec:a9:50:75:41]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311946, SEQNUM=4657, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-11, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/art     (  882): Explicit concurrent mark sweep GC freed 16448(1036KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.444ms total 121.078ms
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=269, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312513, SEQNUM=4669, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-27, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
,I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [f8:95:c7:87:85:54]: 7, f, 6109
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: G3s-1
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: G3s-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: G3s-1
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f036dc rs_disc_pending=1
,W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f03f9c rs_disc_pending=0
,W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: G3s-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 6, f, 410d
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f03f9c rs_disc_pending=1
,W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f0351c rs_disc_pending=0
,W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f03a5c rs_disc_pending=1
W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f03f9c rs_disc_pending=0
,W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, f, 230f
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f03c1c rs_disc_pending=1
,W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f0351c rs_disc_pending=1
,W/bt-btif ( 4919): bta_dm_check_av:0
W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/art     ( 4919): Explicit concurrent mark sweep GC freed 45588(2MB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 7MB/13MB, paused 1.008ms total 76.343ms
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f04d9c rs_disc_pending=1
,W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 6, f, 410d
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f0351c rs_disc_pending=1
,W/bt-btif ( 4919): bta_dm_check_av:0
W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=271, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312582, SEQNUM=4672, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=4844, POWER_SUPPLY_CHARGE_COUNTER=19, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [f8:cf:c5:d9:e5:61]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f03a5c rs_disc_pending=1
W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f03f9c rs_disc_pending=1
,W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): tBTM_SEC_DEV:0xa6f03f9c rs_disc_pending=0
,W/bt-btif ( 4919): bta_dm_check_av:0
,W/bt-btif ( 4919): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, f, 610c
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 6109
E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4919): aclStateChangeCallback: Device is NULL
,V/AlarmManager(  882): send {25fbb27b, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {34c3a29e, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  882): done {34c3a29e, *walarm*:android.content.syncmanager.SYNC_ALARM} [9ms]
,V/AlarmManager(  882): done {25fbb27b, *alarm*:android.intent.action.TIME_TICK} [40ms]
,W/bt-btif ( 4919): info:x10
,D/        ( 4919): remote version info [e0:db:10:1f:c9:5e]: 7, f, 230f
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/btif_config_util( 4919): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4919): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4919): onReceive
,I/BTConnectionReceiver( 7443): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7443): Bluetooth Device Name: Note3-1
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312184, SEQNUM=4676, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-33, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4919): Disconnected process message: 10, size: 0
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312465, SEQNUM=4677, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-11, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  882): send {249f4160, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  882): send {25fbb27b, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {300c5bd1, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,V/AlarmManager(  882): send {36583f06, *walarm*:com.google.android.intent.action.MCS_HEARTBEAT}
,I/ProcessStatsService(  882): Prepared write state in 19ms
,V/AlarmManager(  882): send {b6ad9c7, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,V/AlarmManager(  882): send {21c38bf4, *alarm*:com.google.android.gms/.common.download.DownloadAlarmReceiver}
,V/AlarmManager(  882): done {249f4160, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [52ms]
,I/ProcessStatsService(  882): Prepared write state in 19ms
,V/AlarmManager(  882): done {300c5bd1, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [88ms]
,V/AlarmManager(  882): done {36583f06, *walarm*:com.google.android.intent.action.MCS_HEARTBEAT} [101ms]
,V/AlarmManager(  882): done {b6ad9c7, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [113ms]
,V/AlarmManager(  882): done {25fbb27b, *alarm*:android.intent.action.TIME_TICK} [126ms]
V/AlarmManager(  882): done {21c38bf4, *alarm*:com.google.android.gms/.common.download.DownloadAlarmReceiver} [126ms]
,I/ProcessStatsService(  882): Pruning old procstats: /data/system/procstats/state-2015-11-20-18-21-53.bin
,D/UdcCache:FPQuery( 1946): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  882): Explicit concurrent mark sweep GC freed 16731(915KB) AllocSpace objects, 4(150KB) LOS objects, 33% free, 20MB/30MB, paused 1.878ms total 127.733ms
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 ea
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 ea
,D/MDMCTBK (  302): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
D/MDMCTBK (  302): Event received = P2P-SERV-DISC-REQ 2462 0a
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  316): Sensor:xo_therm_pu2:29000 mC

```
