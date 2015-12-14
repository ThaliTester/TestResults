#### Test 50650278e3ff7c2_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
D/AndroidRuntime( 5234): 
D/AndroidRuntime( 5234): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5234): CheckJNI is OFF
D/AndroidRuntime( 5234): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5253 uid=10362 gids={50362, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5234): Shutting down VM
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5253): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5253): Time to load native libraries: 1 ms (timestamps 7482-7483)
I/LibraryLoader( 5253): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5253): Binding Chromium to main looper Looper (main, tid 1) {479dd50}
,I/LibraryLoader( 5253): Expected native library version number "",actual native library version number ""
I/chromium( 5253): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5253): Initializing chromium process, singleProcess=true
W/art     ( 5253): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5253): ApplicationContext is null in ApplicationStatus
,W/chromium( 5253): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5253): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5253): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5253): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5253): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5253): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5253): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5253): Local Branch: 
I/Adreno-EGL( 5253): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5253): Local Patches: NONE
I/Adreno-EGL( 5253): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@212731c8:true
,D/BluetoothAdapter( 5253): 71488261: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  880): Activity pause timeout for ActivityRecord{3368252d u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 5253): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5253): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5253): CordovaWebView is running on device made by: motorola
,W/art     ( 5253): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5253): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5253): Render dirty regions requested: true
,D/Atlas   ( 5253): Validating map...
,W/chromium( 5253): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5253): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5253): Enabling debug mode 0
,I/Keyboard.Facilitator( 1408): onFinishInput()
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,983
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +912ms (total +983ms)
,W/IInputConnectionWrapper( 5253): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5253): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5253): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5253): Cannot call determinedVisibility() - never saw a connection for the pid: 5253
,D/JsMessageQueue( 5253): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5253): JniHelper::setJavaVM(0xb72fc310), pthread_self() = -1217871048
D/JX-Cordova( 5253): jxcore cordova android initializing
,W/jxcore-log( 5253): Initializing JXcore engine
W/jxcore-log( 5253): JXcore engine is ready
,W/jxcore-log( 5253): Starting JXcore engine
,W/.test.thalitest( 5253): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10362 path="socket:[5649]" dev="sockfs" ino=5649 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 5253): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10362 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5253): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10362 path="socket:[7498]" dev="sockfs" ino=7498 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5253): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10362 path="socket:[24681]" dev="sockfs" ino=24681 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5253): Platform android
W/jxcore-log( 5253): 
W/jxcore-log( 5253): Process ARCH arm
W/jxcore-log( 5253): 
,I/jxcore-log( 5253): JXcore Cordova bridge is ready!
I/jxcore-log( 5253): 
,W/jxcore-log( 5253): JXcore engine is started
I/chromium( 5253): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5253): Toggling radios to true
I/jxcore-log( 5253): 
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  880): enable():  mBluetooth =null mBinding = false
,W/Settings( 1460): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  880): Message: 1
D/BluetoothManagerService(  880): MESSAGE_ENABLE: mBluetooth = null
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiService(  880): New client listening to asynchronous messages
,I/ActivityManager(  880): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5311 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,W/Settings( 1460): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiService(  880): setWifiEnabled: true pid=5253, uid=10362
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings( 1460): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/WifiStateMachine(  880): setting operational mode to 1
W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/jxcore-log( 5253): Radios toggled
I/jxcore-log( 5253): 
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 5253): Got Device Bluetooth address: 08:00:00:10:DD:3C
I/jxcore-log( 5253): 
W/Settings( 1460): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 5253): Perf Test app loaded loaded
I/jxcore-log( 5253): 
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/jxcore-log( 5253): check test folder
I/jxcore-log( 5253): 
,I/jxcore-log( 5253): found test : ./testFindPeers.js
I/jxcore-log( 5253): 
,W/ResourcesManager( 5311): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/jxcore-log( 5253): found test : ./testSendData.js
I/jxcore-log( 5253): 
,D/AdapterServiceConfig( 5311): Adding HeadsetService
D/AdapterServiceConfig( 5311): Adding A2dpService
D/AdapterServiceConfig( 5311): Adding HidService
D/AdapterServiceConfig( 5311): Adding HealthService
D/AdapterServiceConfig( 5311): Adding PanService
D/AdapterServiceConfig( 5311): Adding GattService
D/AdapterServiceConfig( 5311): Adding BluetoothMapService
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@164f880e:true
D/BluetoothAdapterState( 5311): make
,I/BluetoothAdapterState( 5311): Entering OffState
I/bluedroid( 5311): init
,I/bte_conf( 5311): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 5311): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 5311): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5311): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 5311): get_profile_interface socket
I/bluedroid( 5311): get_profile_interface map_client
,I/GKI_LINUX( 5311): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 5311): Address is:44:80:EB:7B:5A:05
D/BluetoothManagerService(  880): Bluetooth Adapter name changed to XT1072
,D/BluetoothManagerService(  880): Stored Bluetooth name: XT1072
D/BluetoothAdapterProperties( 5311): Name is: XT1072
,D/BluetoothManagerService(  880): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  880): Message: 40
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 5311): config_hci_snoop_log
,I/chromium( 5253): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/BluetoothManagerService(  880): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  880): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 5311): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 5311): Setting state to 11
I/BluetoothAdapterState( 5311): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  880): Message: 60
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  880): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 5311): make
,I/BluetoothBondStateMachine( 5311): StableState(): Entering Off State
,I/ActivityManager(  880): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5353 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/TCMD    (  480): NL - Read 1008 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 1008 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/QsoftapCmd(  291): Got softap fwreload command we are passing on
,E/Tethering(  880): ApnList is empty for checkDunConfigured()
,D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
,D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
,D/SoftapController(  291): Softap fwReload - Ok
,D/Tethering(  880): InitialState.processMessage what=4
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
,D/Tethering(  880):  5
D/Tethering(  880):  7
,D/BluetoothHeadset( 1539): Proxy object connected
,D/HeadsetService( 5311): Received start request. Starting profile...
,D/BluetoothHeadset( 1503): Proxy object connected
I/BluetoothHeadsetServiceJni( 5311): classInitNative: succeeds
,D/BluetoothHeadset(  880): Proxy object connected
,D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
,I/BluetoothAdapterState( 5311): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetStateMachine( 5311): make
,D/HeadsetStateMachine( 5311): max_hf_connections = 1
I/bluedroid( 5311): get_profile_interface handsfree
,D/HeadsetStateMachine( 5311): Enter Disconnected: -2, size: 0
,D/BluetoothHeadset( 1503): Proxy object connected
,D/BluetoothAdapterService( 5311): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@479dd50
,D/CommandListener(  291): Setting iface cfg
,D/CommandListener(  291): Trying to bring down wlan0
D/CommandListener(  291): Clearing all IP addresses on wlan0
,D/BluetoothA2dp(  880): Proxy object connected
D/A2dpService( 5311): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 5311): classInitNative: succeeds
I/bluedroid( 5311): get_profile_interface avrcp
,W/ResourcesManager( 5353): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,E/RemoteController( 5311): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 5311): classInitNative: succeeds
,D/A2dpStateMachine( 5311): make
I/bluedroid( 5311): get_profile_interface a2dp
I/GKI_LINUX( 5311): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 5311): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@479dd50
D/A2dpStateMachine( 5311): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 5311): classInitNative: succeeds
,D/HidService( 5311): Received start request. Starting profile...
,I/bluedroid( 5311): get_profile_interface hidhost
D/BluetoothAdapterService( 5311): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@479dd50
,I/BluetoothHealthServiceJni( 5311): classInitNative: succeeds
,D/HealthService( 5311): Received start request. Starting profile...
,I/bluedroid( 5311): get_profile_interface health
,D/BluetoothAdapterService( 5311): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@479dd50
I/BluetoothPanServiceJni( 5311): classInitNative(L105): succeeds
,D/PanService( 5311): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 5311): initializeNative(L110): pan
I/bluedroid( 5311): get_profile_interface pan
,D/BluetoothAdapterService( 5311): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@479dd50
,I/BtGatt.JNI( 5311): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 5311): handleDebugAction() action=null
,D/BtGatt.GattService( 5311): Received start request. Starting profile...
D/BtGatt.GattService( 5311): start()
I/bluedroid( 5311): get_profile_interface gatt
,D/BluetoothAdapterService( 5311): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@479dd50
D/BtGatt.AdvertiseManager( 5311): advertise manager created
,D/BluetoothAdapterService( 5311): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@479dd50
,D/Checkin ( 2906): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/BluetoothMapService( 5311): Received start request. Starting profile...
D/BluetoothMapService( 5311): start()
D/Checkin ( 2906): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/ActivityManager(  880): Killing 5094:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/BluetoothMapEmailSettingsLoader( 5311): Found 0 applications
,D/BluetoothMapEmailAppObserver( 5311): createReceiver()
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_5094/cgroup.procs: No such file or directory
,D/BluetoothMapEmailAppObserver( 5311): initObservers()
D/BluetoothMapEmailAppObserver( 5311): getEnabledAccountItems()
,D/BluetoothAdapterService( 5311): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@479dd50
D/HeadsetStateMachine( 5311): Proxy object connected
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 5311): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 5311): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 5311): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5311): enable
,D/AuthorizationBluetoothService( 1690): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/GKI_LINUX( 5311): gki_task_entry task_id=0 [BTU] starting
,I/bt_hci_bdroid( 5311): init
,I/bt-btu  ( 5311): btu_task pending for preload complete event
,I/wpa_supplicant( 5382): Successfully initialized wpa_supplicant
I/wpa_supplicant( 5382): Long line in configuration file truncated
,E/WifiStateMachine(  880): setWifiState: enabling
,I/wpa_supplicant( 5382): rfkill: Cannot open RFKILL control device
E/WifiStateMachine(  880): Supplicant start successful
D/WifiMonitor(  880): startMonitoring(wlan0) with mConnected = false
,I/bt_vendor( 5311): bt-vendor : init
D/bt_userial_mct( 5311): userial_init
,I/bt_hwcfg( 5311): Starting hciattach daemon
I/bt_hwcfg( 5311): try to set false
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/bt_hwcfg( 5311): Starting hciattach daemon
I/bt_hwcfg( 5311): try to set true
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,I/qcom-bluetooth( 5388): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/libmdmdetect( 5382): ESOC framework not supported
,E/Diag_Lib( 5382):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 5382): baseband property is set to [msm]
,I/libmdmdetect( 5382): ESOC framework not supported
,E/wpa_supplicant( 5382):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5382): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5382): card_info[i].card_state: 0x0
E/wpa_supplicant( 5382): card_info[i].error_code: 0x0
E/wpa_supplicant( 5382): SIM/USIM not ready
E/wpa_supplicant( 5382): Error while reading SIM card status
,E/wpa_supplicant( 5382): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5382): card_info[i].card_state: 0x0
E/wpa_supplicant( 5382): card_info[i].error_code: 0x0
E/wpa_supplicant( 5382): SIM/USIM not ready
I/wpa_supplicant( 5382): eap_proxy: Card not ready
,I/qcom-bluetooth( 5395): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 5396): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 5398): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5399): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 5400): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/wpa_supplicant( 5382): Line 31: unknown global field 't'.
E/wpa_supplicant( 5382): Line 31: Invalid configuration line 't'.
I/wpa_supplicant( 5382): rfkill: Cannot open RFKILL control device
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
,E/wpa_supplicant( 5382): baseband property is set to [msm]
,I/libmdmdetect( 5382): ESOC framework not supported
,D/Checkin ( 2906): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2906): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
E/wpa_supplicant( 5382):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5382): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5382): card_info[i].card_state: 0x0
E/wpa_supplicant( 5382): card_info[i].error_code: 0x0
E/wpa_supplicant( 5382): SIM/USIM not ready
E/wpa_supplicant( 5382): Error while reading SIM card status
,E/wpa_supplicant( 5382): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5382): card_info[i].card_state: 0x0
,E/wpa_supplicant( 5382): card_info[i].error_code: 0x0
E/wpa_supplicant( 5382): SIM/USIM not ready
I/wpa_supplicant( 5382): eap_proxy: Card not ready
I/wpa_supplicant( 5382): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,E/WifiStateMachine(  880): setSuspendOptimizations: 2 true
,E/WifiStateMachine(  880): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  880): Supplicant connection established
,E/WifiStateMachine(  880): setWifiState: enabled
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiConfigStore(  880): Loading config and enabling all networks 
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiConfigStore(  880):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  880):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  880): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  880): Setting external_sim to 1
,D/WifiStateMachine(  880): Setting OUI to DA-A1-19
I/WifiNative-HAL(  880): startHal
,E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2e0589c
D/wifi    (  880): halHandle = 0x0, mVM = 0xb72fc310, mCls = 0x1017f2
I/WifiNative-HAL(  880): Could not start hal
E/WifiStateMachine(  880): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/wpa_supplicant( 5382): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=5406 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,E/native  (  880): do suspend true
,D/WifiP2pService(  880): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  880): SCAN_AVAILABLE : 3
D/RttService(  880): SCAN_AVAILABLE : 3
D/WifiScanningService(  880): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa1a119cc
D/wifi    (  880): halHandle = 0x0, mVM = 0xb72fc310, mCls = 0x1015b6
I/WifiNative-HAL(  880): Could not start hal
E/WifiScanningService(  880): could not start HAL
D/RttService(  880): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  291): Setting iface cfg
D/CommandListener(  291): Trying to bring up p2p0
D/WifiMonitor(  880): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  880): P2pEnablingState
,D/WifiP2pService(  880): P2pEnablingState{ when=-2ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2p socket connection successful
,D/WifiP2pService(  880): P2pEnabledState
,D/WifiP2pService(  880): sending p2p connection changed broadcast
,I/wpa_supplicant( 5382): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,D/WifiNative-HAL(  880): p2pGetDeviceAddress
,D/WifiNative-HAL(  880): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,E/WifiStateMachine(  880): set country code US
,D/WifiP2pService(  880): DeviceAddress: 44:80:eb:7b:5a:07
,E/WifiStateMachine(  880): set frequency band 2
,D/WifiP2pService(  880): MCC mode enabled 0
,D/WifiP2pService(  880): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  880): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  880): InactiveState
D/WifiP2pService(  880): InactiveState{ when=-5ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-5ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5382): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  880): InactiveState{ when=-8ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-8ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/SharedPreferencesImpl(  880): Couldn't create directory for SharedPreferences file shared_prefs/android_preferences.xml
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 5406): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Killing 5035:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_5035/cgroup.procs: No such file or directory
,D/Checkin ( 2906): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  293): NetlinkHandler, wifiStateChanged 1
,I/MDMCTBK (  293): MdmCutbackHndler,wifi, new_state =1
,I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
,I/MDMCTBK (  293): checkDefaultInst, pid match
,I/MDMCTBK (  293): wifi_connect_to_supplicant, current pid is = 293
,D/MDMCTBK (  293): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  293): wifi_close_sockets: Exit
,E/MDMCTBK (  293): Attach monitor thread
I/MDMCTBK (  293): createWifiMonitorThread: Started the wifi monitor thread -1193582792
D/MDMCTBK (  293): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2906): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  293): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/MDMCTBK (  293): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 38:f8:89:11:e9:11
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 1 38:f8:89:11:e9:11
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2e058fc
D/wifi    (  880): halHandle = 0x0, mVM = 0xb72fc310, mCls = 0x1018be
I/WifiNative-HAL(  880): Could not start hal
E/WifiStateMachine(  880): [1,450,100,641,085 ms] noteScanEnd no scan source
,E/WifiStateMachine(  880): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3a580d04 sup_state=SCANNING debouncing=false
,I/qcom-bluetooth( 5436): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 44:80:eb:7b:5a:05 
,I/qcom-bluetooth( 5437): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 5311): bluetooth satus is on
,D/bt_userial_mct( 5311): userial_open(port:0)
,I/bt_userial_vendor( 5311): Done intiailizing UART
,I/bt_userial_vendor( 5311): Done intiailizing UART
I/bt_userial_mct( 5311): CMD=53, EVT=53, ACL_Out=54, ACL_In=54
I/bt_vendor( 5311): Bluetooth Firmware and smd is initialized
,I/bt-btu  ( 5311): btu_task received preload complete event
,D/bt_userial_mct( 5311): Entering userial_read_thread()
,I/        ( 5311): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 5311): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5311): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5311): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5311): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5311): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5311): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5311): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5311): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5311): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5311): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5311): BTE_InitTraceLevels -- TRC_GATT
,I/        ( 5311): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5311): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5311): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 5311): BTM_SecRegister:p_cb_info->p_le_callback == 0xa6dc3d85 
E/bt-btm  ( 5311): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa6dc3d85 
,E/bt-btif ( 5311): Calling BTA_HhEnable
E/bt-btif ( 5311): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 5311): Address is:44:80:EB:7B:5A:05
,D/BluetoothManagerService(  880): Bluetooth Adapter name changed to XT1072
D/BluetoothManagerService(  880): Stored Bluetooth name: XT1072
,D/BluetoothAdapterProperties( 5311): Name is: XT1072
,D/BluetoothAdapterProperties( 5311): Scan Mode:20
D/BluetoothAdapterProperties( 5311): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5311): Adding bonded device:7C:F9:0E:37:96:AB
D/BluetoothAdapterProperties( 5311): Adding bonded device:E0:DB:10:14:E2:C0
D/BluetoothAdapterProperties( 5311): Adding bonded device:58:2A:F7:ED:96:BE
,E/BluetoothRemoteDevices( 5311): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:37:96:AB, value is empty for type: 10
,E/BluetoothRemoteDevices( 5311): devicePropertyChangedCallback: bdDevice: E0:DB:10:14:E2:C0, value is empty for type: 10
,E/BluetoothRemoteDevices( 5311): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/bte_conf( 5311): Device ID record 1 : primary
D/bte_conf( 5311):   vendorId            = 000f
D/bte_conf( 5311):   vendorIdSource      = 0001
D/bte_conf( 5311):   product             = 1200
D/bte_conf( 5311):   version             = 1436
D/bte_conf( 5311):   clientExecutableURL = 
D/bte_conf( 5311):   serviceDescription  = 
D/bte_conf( 5311):   documentationURL    = 
D/bte_conf( 5311): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 5311): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5311): ScanMode =  20
,D/BluetoothAdapterProperties( 5311): State =  11
D/BluetoothAdapterProperties( 5311): Setting state to 12
I/BluetoothAdapterState( 5311): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  880): Message: 60
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  880): Broadcasting onBluetoothStateChange(true) to 5 receivers.
,I/BluetoothAdapterState( 5311): Entering On State
,D/BluetoothAdapterProperties( 5311): Scan Mode:21
D/BluetoothAdapterProperties( 5311): Discoverable Timeout:120
,D/BluetoothHeadset( 1503): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1539): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  880): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1503): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  880): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  880): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothMapService( 5311): onReceive
D/BluetoothMapService( 5311): STATE_ON
,D/BluetoothMapMasInstance( 5311): Map Service startRfcommSocketListener
,D/BluetoothManagerService(  880): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  880): Message: 40
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledStateupdate channel list
,E/bt_mct  ( 5311): hci lib postload completed
,D/BluetoothPanServiceJni( 5311): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothMapMasInstance( 5311): MAS initSocket()
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5311): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 5311): Accepting socket connection...
,I/Telecom ( 1503): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/HeadsetStateMachine( 5311): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 5311): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 5311): mNumber:  mType: 128
D/HeadsetStateMachine( 5311): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 5311): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/ContextImpl( 5353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@211afea0:true
,D/LocalBluetoothProfileManager( 5353): Adding local A2DP profile
,D/BluetoothManagerService(  880): Message: 30
,D/LocalBluetoothProfileManager( 5353): Adding local HEADSET profile
,D/BluetoothManagerService(  880): Message: 30
,D/AuthorizationBluetoothService( 1690): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5311): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  880): Message: 30
,D/BluetoothManagerService(  880): Message: 30
,D/LocalBluetoothProfileManager( 5353): Adding local MAP profile
,D/BluetoothMap( 5353): Create BluetoothMap proxy object
,D/BluetoothManagerService(  880): Message: 30
,D/BluetoothManagerService(  880): Message: 30
,D/LocalBluetoothProfileManager( 5353): LocalBluetoothProfileManager construction complete
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5311): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 5311): Accept thread started.
D/DockEventReceiver( 5353): finishStartingService: stopping service
,D/BluetoothA2dp( 5353): Proxy object connected
,I/MDMCTBK (  293): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  293): NetlinkHandler, interfaceAdded
,I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
E/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  293): , Wifi = 0
I/MDMCTBK (  293): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
,I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
D/A2dpProfile( 5353): Bluetooth service connected
,I/MDMCTBK (  293): send SAR ctrl over QMI
,D/BluetoothHeadset( 5353): Proxy object connected
D/HeadsetProfile( 5353): Bluetooth service connected
,D/BluetoothInputDevice( 5353): Proxy object connected
D/HidProfile( 5353): Bluetooth service connected
,D/BluetoothPan( 5353): BluetoothPAN Proxy object connected
D/PanProfile( 5353): Bluetooth service connected
,D/BluetoothMap( 5353): Proxy object connected
,D/MapProfile( 5353): Bluetooth service connected
D/BluetoothMap( 5353): getConnectedDevices()
,D/BluetoothPbap( 5353): Proxy object connected
D/PbapServerProfile( 5353): Bluetooth service connected
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  293): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 5382): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  293): Event received = Trying to associate with
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2e058fc
D/wifi    (  880): halHandle = 0x0, mVM = 0xb72fc310, mCls = 0x10105a
I/WifiNative-HAL(  880): Could not start hal
,E/WifiStateMachine(  880): [1,450,100,641,687 ms] noteScanEnd no scan source
E/wpa_supplicant( 5382): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/WifiMonitor(  880): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  880): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3a580d04 sup_state=SCANNING debouncing=false
,E/WifiConfigStore(  880):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TCMD    (  480): NL - Read 312 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 192 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 5382): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/TCMD    (  480): NL - Read 80 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 80 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  293): Event received = Associated with c0:ff:d4
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 5382): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  293): Event received = WPA: Key negotiation com
I/wpa_supplicant( 5382): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293):  STA Connected !!
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
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
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, Wifi Band changed, call setWifiCutback.
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 1, data=0
I/MDMCTBK (  293): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  293): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1193566960
I/MDMCTBK (  293): return from set_get_from_wpa_supplicant
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): wifi_set_tx_pwr: SETTXPOWER = 18
,E/MDMCTBK (  293): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  293): , reply_len: 3, ret: 0
E/MDMCTBK (  293): MdmCutbackHndler, resp=OK
E/MDMCTBK (  293): 
D/MDMCTBK (  293): wifi_set_tx_pwr: Exit
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  880): Network connection established
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  880): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
,E/WifiStateMachine(  880): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  880): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine(  880): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  880): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,D/CommandListener(  291): Setting iface cfg
,E/WifiStateMachine(  880): Start Dhcp Watchdog 1
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend false
,E/wpa_supplicant( 5382): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 5382): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  880): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@6bc91c7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@6bc91c7 target=com.android.internal.util.StateMachine$SmHandler }
,E/DHCPCD  ( 5477): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5477): version 5.5.6 starting
,E/DHCPCD  ( 5477): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 5477): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 5477): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 5477): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5477): wlan0: discarding expired lease
,I/DHCPCD  ( 5477): wlan0: broadcasting for a lease
D/DHCPCD  ( 5477): wlan0: sending DISCOVER (xid 0xe3644076), next in 3.16 seconds
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/art     (  880): Explicit concurrent mark sweep GC freed 35713(1789KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.842ms total 172.121ms
,I/DHCPCD  ( 5477): wlan0: offered 192.168.1.123 from 192.168.1.1
D/DHCPCD  ( 5477): wlan0: sending REQUEST (xid 0xe3644076), next in 3.94 seconds
,I/DHCPCD  ( 5477): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 5477): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 5477): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 5477): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 5477): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5477): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  480): NL - Read 60 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 20
D/TCMD    (  480): Listening for incoming client connection request
,D/DHCPCD  ( 5477): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason BOUND
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  880): WifiStateMachine DHCP successful
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  880): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService(  880): Adding iface wlan0 to network 100
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  880): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  880): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  880): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  880): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  880): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  880): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  880): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  880): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  880):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Connected
D/ConnectivityService(  880): Setting tx/rx TCP buffers to 131072,262144,3145728,4096,221184,3145728
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,D/CSLegacyTypeTracker(  880): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  880): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
I/ModemStatsDSDetect( 1520): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1937): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1520): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1520): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 14 Dec 2015 13:44:04 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450100644388], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450100644371]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Validated
D/ConnectivityService(  880): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  880): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1937): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1520): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1520): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1520): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1520): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/jxcore-log( 5253): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 5253): 
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1937): CM callback handler got msg 524295
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,I/jxcore-log( 5253): Connected to the server!
I/jxcore-log( 5253): 
,I/chromium( 5253): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/PollingManager( 2504): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2504): now: 451168 ,futureTime: 9223372036854775807
D/PollingManager( 2504): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1460): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AlarmManagerService(  880): Setting time of day to sec=1450100647
,W/AlarmManagerService(  880): Unable to set rtc to 1450100647: Invalid argument
,D/PollingManager( 2504): now: 451200 ,futureTime: 9223372036854775807
,D/PollingManager( 2504): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2504): now: 451222 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2504): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5566 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  880): send {174a9eb4, *alarm*:android.intent.action.TIME_TICK}
,D/OtaApp  ( 2504): [debug] > PollingManagerService, now: 451247 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1460): now: 451249 ,futureTime: 86476629
D/Central_PollingManager( 1460): Polling alarm set to expire at: 86476629 Current Time: 451249
,D/MMApiProvisionService( 2504): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2504): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2504): createDeviceIdOrLogin update_device
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2504): Not proxy app, so login/provision not allowed
D/MMApiWebService( 2504): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2504): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2504): isDeviceProvisioned: deviceId = 2072049230914535424
,V/AlarmManager(  880): done {174a9eb4, *alarm*:android.intent.action.TIME_TICK} [98ms]
,D/CCE     ( 2504): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2504): createDeviceIdOrLogin update_device
D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2504): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2504): isRequestAllowed(): already have outstanding request ... ignoring request
D/MMApiWebService( 2504): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,E/GpsLocationProvider(  880): No APN found to select.
,D/GpsLocationProvider(  880): NTP server returned: 1450100644461 (Mon Dec 14 14:44:04 GMT+01:00 2015) reference: 448521 certainty: 27 system time offset: -2865
,E/LocSvc_ApiV02(  880): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,D/MMApiWebService( 2504): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiProvisionService( 2504): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2504): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2504): createDeviceIdOrLogin update_device
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2504): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2504): generating token using payload instead of using session token
,D/OtaApp  ( 2504): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2504): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2504): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2504): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2504): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2504): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2504): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2504): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,E/ActivityThread( 1937): Failed to find provider info for com.android.contacts.metadata
,D/ Nonce  ( 2504):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/SyncManager(  880): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 482417, reason: UserStart
,I/art     ( 1460): Explicit concurrent mark sweep GC freed 5490(259KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 7MB/12MB, paused 849us total 45.171ms
,I/MMApiWSBase( 2504): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWSBase( 2504): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/MusicStore( 5566): Database version: 120
,I/ActivityManager(  880): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=5624 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5566): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5566): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5566): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 5566): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5566): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5566): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 5624): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5624): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5624): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5566): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5566): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1aafb76c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5566): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 5566): GMSCore installation verified
,I/ConfigStore( 5566): Config Database version: 1
,W/System  ( 5624): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5624): Installed default security provider GmsCore_OpenSSL
,I/MediaRouter( 5566): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5566): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5566): type=WIFI subType= reason=null isConnected=true
,W/art     ( 5624): Suspending all threads took: 26.369ms
,E/Auth.Api.Credentials( 1937): [CredentialSyncAdapter] Unknown sync event.
,I/GoogleURLConnFactory( 1690): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 5624): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5624): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MMApiWSBase( 2504): doRequest(): error in response: 403
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWSBase( 2504): doRequest(): error in response: {"error":"INVALID_SESSION","error_text":"Please provide a valid authtoken"}
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWSBase( 2504): doRequest(): v1/gns/list/messages resp length: 75
,I/MMApiWebService( 2504): inspectMMApiResponse(): found an error from a web service response: ForbiddenError msg: INVALID_SESSION req: 
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/ Nonce  ( 2504):  Nonce Reponse 
D/        ( 2504): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"9727adcc-d0ff-4eee-b39d-95b6e9d0379f"}
D/MMApiWSBase( 2504): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2504):  Nonce Handle Reponse 
,I/MMApiWebService( 2504): inspectMMApiResponse(): received invalid session error from the server.. need to re-login
,D/MMApiProvisionService( 2504): mOutstandingReq set to false
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2504): initiateDeviceLogin(): sending login request
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/art     (  880): Explicit concurrent mark sweep GC freed 28563(1491KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 2.106ms total 163.357ms
,I/MMApiWebService( 2504): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/NetworkMonitor( 5566): type=WIFI subType= reason=null isConnected=true
,D/MMApiProvisionService( 2504): Got request to obtain new Session .. doing so now
I/MMApiProvisionService( 2504): createDeviceIdOrLogin update_device
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2504): Not proxy app, so login/provision not allowed
D/MMApiProvisionService( 2504): Got request to obtain new Session .. doing so now
I/MMApiProvisionService( 2504): createDeviceIdOrLogin update_device
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/dex2oat ( 5665): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-2118966873.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-2118966873.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/MMApiProvisionService( 2504): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2504): set mOutstandingReq to true.
I/ Nonce  ( 2504):  Nonce getNonce 
I/ Nonce  ( 2504):  Nonce Request 
I/ Nonce  ( 2504):  Nonce execute Request 
,D/MMApiProvisionService( 2504): Got request to obtain new Session .. doing so now
I/MMApiProvisionService( 2504): createDeviceIdOrLogin update_device
D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2504): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2504): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
E/YouTube MDX( 5624): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5678 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,I/GHttpClientFactory( 5566): Using our fixed implementation of GMSCore's GoogleHttpClient
W/ContextImpl( 5624): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/GoogleURLConnFactory( 5566): Using platform SSLCertificateSocketFactory
,D/MMApiProvisionService( 2504): mForceLogin set to false.
D/MMApiProvisionService( 2504): createDeviceIdOrLogin(): Got request to login .. processing now
,D/BSUtils ( 2504): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/MMApiWebService( 2504): generating token using payload instead of using session token
,V/Mms     ( 5678): mnc/mcc: 
V/Mms     ( 5678): tag: int value: recipientLimit - 20
V/Mms     ( 5678): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 5678): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 5678): tag: int value: maxSubjectLength - 80
V/Mms     ( 5678): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 5678): tag: bool value: enableGroupMms - false
V/Mms     ( 5678):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     ( 2504): Explicit concurrent mark sweep GC freed 39262(2MB) AllocSpace objects, 5(125KB) LOS objects, 40% free, 11MB/19MB, paused 1.868ms total 104.896ms
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5624): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5624): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5624): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,W/ResourcesManager( 5678): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/dex2oat ( 5665): dex2oat took 378.290ms (threads: 4)
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5731 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.608ms
,W/InstanceID/Rpc( 5624): Found 10016
D/DownloadManager( 2450): [84] Starting
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 27.810ms
,W/ActivityThread( 2450): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.034ms
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5624): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/art     ( 1539): Explicit concurrent mark sweep GC freed 30067(1928KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.549ms total 75.248ms
,I/ActivityManager(  880): Killing 5170:com.google.android.gms:car/u0a16 (adj 15): empty #7
,D/PhoneMonitor( 5731): Register our PhoneStateListener
,I/art     ( 1460): Explicit concurrent mark sweep GC freed 3344(133KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 527us total 26.327ms
,D/ Nonce  ( 2504):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2504): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_5170/cgroup.procs: No such file or directory
D/BSUtils ( 2504): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/MobileConnectivityChangeReceiver( 5731): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5731): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 5119:com.android.vending/u0a32 (adj 15): empty #7
,I/BSUtils ( 2504): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2504): doRequest() with req : MMApiWSRequest(/v1/gdi/devices.json)
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_5119/cgroup.procs: No such file or directory
,I/art     (  880): Explicit concurrent mark sweep GC freed 11460(480KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.870ms total 131.642ms
,D/MMApiWebService( 2504): generating token using payload instead of using session token
,I/MMApiWSBase( 2504): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/devices.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/CheckinService( 1937): Checkin interval check for package: unspecified last checkin: 1449861420526 min interval config: 0 actual interval: 239228902
,I/MDMCTBK (  293): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  293): NetlinkHandler, interfaceAdded
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
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  293): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  293): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1193566960
I/MDMCTBK (  293): return from set_get_from_wpa_supplicant
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
D/MDMCTBK (  293): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  293): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
,E/MDMCTBK (  293): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  293): , reply_len: 3, ret: 0
E/MDMCTBK (  293): MdmCutbackHndler, resp=OK
E/MDMCTBK (  293): 
D/MDMCTBK (  293): wifi_set_tx_pwr: Exit
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,I/MDMCTBK (  293): send SAR ctrl over QMI
,I/CheckinService( 1937): Checking schedule, now: 1450100649448 next: 1449861450505
I/CheckinService( 1937): active receiver: enabled
,I/art     ( 1690): Explicit concurrent mark sweep GC freed 46822(2MB) AllocSpace objects, 16(279KB) LOS objects, 39% free, 13MB/22MB, paused 953us total 116.295ms
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1866fbd3)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1cc5b310)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b1c4e09)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3eca280e)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1d1b822f)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@25baf03c)
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1032c1c5)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4b71a)
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29e8124b)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3e64d428)
,I/CheckinService( 1937): Preparing to send checkin request
,I/EventLogService( 1937): Accumulating logs since 1450099083387
,W/PhenotypeConfigurator( 1690): Server returned 404
,I/iu.SyncManager( 1937): SYNC; picasa accounts
,D/NetworkLogImpl( 1937): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1937): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1937): num queued entries: 0
,I/iu.UploadsManager( 1937): num updated entries: 0
,I/iu.SyncManager( 1937): NEXT; no task
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Checkin ( 2450): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=5791 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/DownloadManager( 2450): [84] Finished with status SUCCESS
,I/CheckinRequestBuilder( 1937): Checkin reason type: 8 attempt count: 1
,D/WifiService(  880): New client listening to asynchronous messages
,E/ActivityThread( 1937): Failed to find provider info for com.google.android.wearable.settings
,I/ Nonce  ( 2504):  Nonce Reponse 
,D/        ( 2504): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"10acd1b0-374f-4c11-ab11-1e6c2f5ed1e9"}
D/MMApiWSBase( 2504): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2504):  Nonce Handle Reponse 
D/MMApiProvisionService( 2504): mOutstandingReq set to false
,D/MMApiProvisionService( 2504):  pTime 1449860801477 sExp 172742 cTime 1450100649968 tTime 1450033543477
D/MMApiProvisionService( 2504): createDeviceIdOrLogin(): Got request to login .. processing now
,D/BSUtils ( 2504): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/ActivityManager(  880): Killing 5353:com.android.settings/1000 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_1000/pid_5353/cgroup.procs: No such file or directory
,D/BSUtils ( 2504): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2504): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2504): doRequest() with req : MMApiWSRequest(/v1/gdi/devices.json)
,W/DataUsage( 2504): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/art     ( 1460): Explicit concurrent mark sweep GC freed 3586(141KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 733us total 50.886ms
,D/MMApiProvisionService( 2504): ProvisionWS.Response: processing response data: {"error":"ACCESS_DENIED"}
,E/MMApiProvisionService( 2504): ProvisionWS.Response: received error code: ACCESS_DENIED Extra Info: 
D/MMApiWSBase( 2504): doRequest(): /v1/gdi/devices.json resp length: 25
,D/MMApiWebService( 2504): generating token using payload instead of using session token
,I/MMApiWSBase( 2504): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/devices.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/DeviceSettingsProvider( 1460):  Number of rows updated 1
,D/MMApiProvisionService( 2504): MMApiProvisionService.handleResponse (update_device) : true (None)
E/MMApiProvisionService( 2504): handleResponse(): got ACCESS_DENIED, nothing can be done with it, so we're bailing...
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=5818 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2504): notifyProvisioningDone(): Sending Device Provision response intent
,D/CCE     ( 2504): NOT Backing up config to settings provider
,D/CCE     ( 2504): NOT Backing up config to settings provider
D/CCE     ( 2504): NOT Backing up config to settings provider
,W/ResourcesManager( 5818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GCM     ( 1690): GCM config loaded
,I/art     (  880): Explicit concurrent mark sweep GC freed 12127(541KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.731ms total 118.427ms
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5846 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5870 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ContactLocale( 5846): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 5406:com.motorola.context/u0a8 (adj 15): empty #7
,I/art     ( 4835): Explicit concurrent mark sweep GC freed 1672(74KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 698us total 33.008ms
,W/DataUsage( 2504): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_5406/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1937): Module APK com.google.android.play.games already loaded
,W/ResourcesManager( 5870): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MMApiProvisionService( 2504): ProvisionWS.Response: processing response data: {"sessionToken":"0-c5ad97fa762d335c2cea8846b56c0c491436765851","error":"OK","sessionExpiration":"172742","deviceId":"2072049230914535424"}
,D/MMApiProvisionService( 2504): ProvisionWS.Response: Completed parsing response.. no settings sent by server
D/MMApiWSBase( 2504): doRequest(): /v1/gdi/devices.json resp length: 138
I/GamesSyncServiceMain( 1937): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 1937): Failed to execute periodic sync, missing client context - aborting
,W/DataUsage( 2504): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/DeviceSettingsProvider( 1460):  Number of rows updated 1
,D/MMApiProvisionService( 2504): MMApiProvisionService.handleResponse (update_device) : true (None)
,I/Babel_SMS( 5870): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5870): MmsConfig.loadMmsSettings
I/Babel_SMS( 5870): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5870): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5870): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5870): MmsConfig.loadFromResources
,E/Babel_SMS( 5870): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5870): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/GoogleURLConnFactory( 1937): Using platform SSLCertificateSocketFactory
,W/art     ( 5870): Suspending all threads took: 6.734ms
,I/DeviceSettingsProvider( 1460):  Number of rows updated 1
,E/MMApiProvisionService( 2504): Caught IOException:/pds/public/svcs/activation_date: open failed: EACCES (Permission denied)
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,W/FileUtils( 2504): Failed to chmod(/pds/public/svcs/activation_date): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
D/MMApiProvisionService( 2504): handleResponse(): Session Expiration alarm set to expire at: Wed Dec 16 14:43:13 GMT+01:00 2015
I/MMApiProvisionService( 2504):  value of type 2072049230914535424 0-c5ad97fa762d335c2cea8846b56c0c491436765851 172742
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2504):  get value of the device MOTO
I/MMApiProvisionService( 2504):  came in moto 
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2504): setMMApiCredInfoToMainApp: storing credential info
I/MMApiProvisionService( 2504): setMMApiCredInfoToMainApp: deviceId = 2072049230914535424
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,W/Settings( 5870): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5870): startup - clean
,I/Babel   ( 5870): deleted: false for 0
,I/DeviceSettingsProvider( 1460):  Number of rows updated 1
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5915 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DeviceSettingsProvider( 1460):  Number of rows updated 1
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/VideoCapabilities( 5870): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5870): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5870): Unsupported mime video/mpeg2,
,I/VideoCapabilities( 5870): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5870): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5870): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5870): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5870): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5870): onServiceConnected
,W/Babel   ( 5870): Attempted to change video mute state without an active call.
,I/Babel   ( 5870): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 5566:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_5566/cgroup.procs: No such file or directory
,I/DeviceSettingsProvider( 1460):  Number of rows updated 1
,E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/DeviceSettingsProvider( 1460):  Number of rows updated 1
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5915): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5915): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 5915): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5915):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5915):   adb logcat -s GAv4
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5915): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5915): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 5915): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/DataUsage( 2504): invalid counter update blocked: 'err' by 0
I/DeviceSettingsProvider( 1460):  Number of rows updated 1
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,W/GAv4    ( 5915): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5915): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/DeviceSettingsProvider( 1460):  Number of rows updated 1
,I/DeviceSettingsProvider( 1460):  Number of rows updated 1
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DeviceSettingsProvider( 1460):  Number of rows updated 1
,D/BSUtils ( 2504): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/MMApiProvisionService( 2504):  response.hasSettings() false
D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
E/MMApiProvisionService( 2504): handleResponse(): no settings sent by the server:
D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2504): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
D/MMApiWebService( 2504): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,D/MMApiWebService( 2504): MMApiWebService told us to retry waiting request since device is successfully provisioned: 1
,D/MMApiWebService( 2504): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/MMApiWSBase( 2504): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5976 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:31000 mC
,I/WebViewFactory( 5915): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5915): Time to load native libraries: 1 ms (timestamps 6712-6713)
I/LibraryLoader( 5915): Expected native library version number "",actual native library version number ""
,W/ResourcesManager( 5976): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5976): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/WebViewChromiumFactoryProvider( 5915): Binding Chromium to main looper Looper (main, tid 1) {22a3490d}
,I/LibraryLoader( 5915): Expected native library version number "",actual native library version number ""
I/chromium( 5915): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5915): Initializing chromium process, singleProcess=true
,W/art     ( 5915): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5915): ApplicationContext is null in ApplicationStatus
,I/MultiDex( 5976): VM with version 2.1.0 has multidex support
I/MultiDex( 5976): install
I/MultiDex( 5976): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5976): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/chromium( 5915): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5915): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5915): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5915): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5915): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5915): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5915): Local Branch: 
I/Adreno-EGL( 5915): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5915): Local Patches: NONE
I/Adreno-EGL( 5915): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityThread( 5976): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5976): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b007e9d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5976): Installed default security provider GmsCore_OpenSSL
,I/art     ( 5976): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5976): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/AudioManagerAndroid( 5915): Requires BLUETOOTH permission
,I/NSApplication( 5915): Starting up...
,I/PhenotypeConfigurator( 1690): Scheduling Phenotype for one-off execution 5067 seconds from now (1450100652906)
,W/art     ( 5818): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6019 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 5678:com.android.mms/u0a23 (adj 15): empty #7
,D/NativeLibraryUtils( 5976): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_5678/cgroup.procs: No such file or directory
,D/GetConfigurationSnapshotOperation( 1690): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
,I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,I/art     (  880): Explicit concurrent mark sweep GC freed 26104(1154KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.697ms total 138.710ms
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa5000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa5000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb1389960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb7c853c8, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7c317c8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb7d5ed98, idLength=0xb5473730
,I/GoogleURLConnFactory( 5976): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=2755157256
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7c97450
D/DrmWidevineDash(  295): message_length=1591, signature=0xb7c9dd10, signature_length=3041343252
,D/MMApiWSBase( 2504): doRequest(): v1/gns/list/messages resp length: 1363
,D/CCE     ( 2504): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 2504): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,D/Checkin ( 2504): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 2504): handleGetNotificationsResponse(): got 0; more=false
,I/ActivityManager(  880): Killing 5731:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_5731/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=6055 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 6055): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=6074 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 5791:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_5791/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 5846:android.process.acore/u0a7 (adj 15): empty #7
,E/SQLiteLog( 6074): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/PhenotypeFlagCommitter( 1690): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1690): Using platform SSLCertificateSocketFactory
,W/DataUsage( 2504): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_5846/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6096 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6096): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/PeopleSync( 1937): onPerformSync() [5005f081]
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AnalyticsLogBase( 6074): PlayLogger.onLoggerConnected
,I/ActivityManager(  880): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6119 uid=10096 gids={50096, 9997} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 5915:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/art     (  313): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.702ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 19.514ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 19.799ms
,I/ActivityManager(  880): Killing 5870:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_5915/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_5870/cgroup.procs: No such file or directory
,I/CalendarProvider2( 6096): Created com.android.providers.calendar.CalendarAlarmManager@230dc202(com.android.providers.calendar.CalendarProvider2@2d846713)
,I/System.out( 6119): TimeService: Loaded Library 
,D/TimeService( 6119): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450100654593
D/        ( 6119): TimeServiceNative: User Time to be set is 1450100654593
D/QC-time-services( 6119): Lib:time_genoff_operation: pargs->base = 2
,D/QC-time-services( 6119): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6119): Lib:time_genoff_operation: pargs->ts_val = 1450100654593
D/QC-time-services( 6119): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  324): Daemon: Connection accepted:time_genoff
D/QC-time-services(  324): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450100654593
,D/QC-time-services(  324): Daemon:genoff_opr: Base = 2, val = 1450100654593, operation = 0
D/QC-time-services(  324): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/14/115 13:42:58
D/QC-time-services(  324): Daemon:Value read from RTC seconds = 1450100578000
D/QC-time-services(  324): Daemon:new time 1450100654593 
D/QC-time-services(  324): Daemon: delta 76593 genoff 76593 
D/QC-time-services(  324): Daemon:genoff_persistent_update: Writing genoff = 76593 to memory
D/QC-time-services(  324): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  324): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  324): Updating the TOD offset
D/QC-time-services(  324): Daemon:genoff_persistent_update: Writing genoff = 76593 to memory
D/QC-time-services(  324): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  324): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  324): Daemon:Update to modem bit set
,D/QC-time-services(  324): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 6119): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  324): Daemon: Base = 2, Value being sent to MODEM = 18446743757744828209
,E/QC-time-services(  324): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  324): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1937): Checkin interval check for package: unspecified last checkin: 1449861420526 min interval config: 0 actual interval: 239234092
,I/ActivityManager(  880): Killing 6019:com.android.chrome/u0a52 (adj 15): empty #7
,I/dex2oat ( 6144): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=35 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_6019/cgroup.procs: No such file or directory
,W/AbstractGoogleClient( 6074): Application name is not set. Call Builder#setApplicationName.
,I/AnalyticsLogBase( 6074): PlayLogger.onLoggerConnected
,I/dex2oat ( 6144): dex2oat took 152.979ms (threads: 4)
,I/Adreno-EGL( 5976): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5976): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5976): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5976): Local Branch: 
I/Adreno-EGL( 5976): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5976): Local Patches: NONE
I/Adreno-EGL( 5976): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=6159 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/Adreno-EGL( 5976): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5976): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5976): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5976): Local Branch: 
I/Adreno-EGL( 5976): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5976): Local Patches: NONE
I/Adreno-EGL( 5976): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/PeopleSync( 1937): Setting subscription: result=true [5005f081]
,I/PeopleSync( 1937): Starting sync, feed=null [5005f081]
,I/GAv4    ( 6159): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6159):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6159):   adb logcat -s GAv4
,W/GAv4    ( 6159): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6159): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6159): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1937): Explicit concurrent mark sweep GC freed 25633(1800KB) AllocSpace objects, 42(695KB) LOS objects, 25% free, 15MB/20MB, paused 1.279ms total 108.707ms
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/PeopleSync( 1937): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/EmailService.MarketingOptInSetter( 2504): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 2504): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
E/SQLiteLog( 2504): (284) automatic index on registration(APP_ID)
,D/WaitableIntentService( 2504): ServiceHandler.handleMessage: mWaitCount=1
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f98000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f98000
,I/PushService( 2504): started with background data enabled, making sure notification mechanism is enabled
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/OtaApp  ( 2504): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2504): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2504): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xbe9114e0
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb7c40eb0, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7c41178, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb7d5edd8, idLength=0xb1389730
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
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
D/WVCdm   (  295): PrepareKeyRequest: nonce=645997695
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7d134c0
D/DrmWidevineDash(  295): message_length=1626, signature=0xb7c9dd10, signature_length=2973275924
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2504): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2504): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,I/DictionaryProvider:UpdateHandler( 1408): downloadFinished() : DownloadId = 84
,I/art     ( 2504): Explicit concurrent mark sweep GC freed 31382(1908KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 11MB/19MB, paused 2.074ms total 78.448ms
,D/OtaApp  ( 2504): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2504): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2504): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2504): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,I/ConfigService( 1690): onCreate
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/ActivationLocation( 2504): Provisioning status received: ERROR_FAIL
,I/Keyboard.Facilitator( 1408): onFinishInput()
,W/IInputConnectionWrapper( 5253): showStatusIcon on inactive InputConnection
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6191 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CalendarProvider2( 6096): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6096): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/Adreno-EGL( 5976): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5976): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5976): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5976): Local Branch: 
I/Adreno-EGL( 5976): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5976): Local Patches: NONE
I/Adreno-EGL( 5976): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/LaunchCheckinHandler(  880): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,370
,W/ResourcesManager( 6191): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Adreno-EGL( 5976): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5976): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5976): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5976): Local Branch: 
I/Adreno-EGL( 5976): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5976): Local Patches: NONE
I/Adreno-EGL( 5976): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Babel_SMS( 6191): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6191): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6191): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6191): MmsConfig.loadFromDatabase
,I/CheckinRequestBuilder( 1937): Classify the device as Phone.
,E/Babel_SMS( 6191): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6191): MmsConfig.loadFromResources
,E/Babel_SMS( 6191): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6191): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6191): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6191): startup - clean
,I/art     (  880): Explicit concurrent mark sweep GC freed 21383(1039KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.661ms total 160.845ms
,I/Babel   ( 6191): deleted: false for 0
,I/art     ( 4835): Explicit concurrent mark sweep GC freed 2941(115KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 415us total 60.738ms
,I/DictionaryProvider:UpdateHandler( 1408): downloadFinished() : Success = true
I/DictionaryProvider:UpdateHandler( 1408): downloadFinished() : Metadata Success
,I/Keyboard.Facilitator( 1408): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1408): run()
,I/Decoder ( 1408): createOrResetDecoder
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): run()
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6230 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6191): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6191): Unsupported mime audio/amr-wb-plus
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,W/VideoCapabilities( 6191): Unsupported mime video/mpeg2
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = contacts
,I/VideoCapabilities( 6191): Unsupported profile 4 for video/mp4v-es
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = history
,W/VideoCapabilities( 6191): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6191): Unrecognized profile 2130706433 for video/avc
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = user
,W/VideoCapabilities( 6191): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6191): Unrecognized profile 2130706433 for video/avc
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1408): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1408): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1408): run()
I/StatsUtilsManager( 1408): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1408): shouldRecordStats() = Too Soon
,I/ActivityManager(  880): Killing 6055:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_6055/cgroup.procs: No such file or directory
,I/vclib   ( 6191): onServiceConnected
W/Babel   ( 6191): Attempted to change video mute state without an active call.
,I/DictionaryProvider:UpdateHandler( 1408): downloadFinished() : Success = true
I/DictionaryProvider:UpdateHandler( 1408): downloadFinished() : Metadata Success
,I/Keyboard.Facilitator( 1408): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1408): run()
I/Decoder ( 1408): createOrResetDecoder
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1408): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1408): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1408): run()
I/StatsUtilsManager( 1408): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1408): shouldRecordStats() = Too Soon
,I/CalendarSyncAdapter( 6074): Found no pending settings
,I/ActivityManager(  880): Killing 6119:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,I/CheckinTask( 1937): Sending checkin request (10586 bytes)
,W/libprocessgroup(  880): failed to open /acct/uid_10096/pid_6119/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 5818:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_5818/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 6096:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_6096/cgroup.procs: No such file or directory
,W/BaseAppContext( 1690): Using Auth Proxy for data requests.
,E/BaseAppContext( 1690): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/GCM     ( 1690): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,I/CheckinResponseProcessor( 1937): From server: 2 gservices updates and 0 deletes
,I/art     ( 1690): Background sticky concurrent mark sweep GC freed 110925(6MB) AllocSpace objects, 39(624KB) LOS objects, 31% free, 15MB/22MB, paused 1.801ms total 106.983ms
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@13e1cb67)
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3bc72d14)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@150279bd)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18539bb2)
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@32b5b703)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4740680)
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@105bc0fe)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e52c05f)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18530aac)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@15a42375)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1b2eef0a)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b8d037b)
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@ea081f1)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1354f1d6)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3e5e5c57)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@109a0344)
,I/SundryService( 2504): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 2504): Received shoulder tap
,I/PeopleSync( 1937): Sync finished, successful=true, took 2267ms
,I/PeopleContactsSync( 1937): CP2 sync start [5005f081]
,D/WaitableIntentService( 2504): setWaitEnabled(): mWaitCount=2 isWaitEnabled=true
D/WearableService( 1690): callingUid 10016, callindPid: 1690
D/GetNotificationsWS( 2504): GetNotificationsWS.Request: message={"request":{"wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","requestFormat":"json","httpMethod":"post","baseUrl":"v1\/gns\/list\/messages","isSecure":true,"useOAuth":true,"retries":"-1","appendDeviceId":true,"queryParams":{"appid":"6R1TANEX3ZMQ6EU1UH43P34C8B868KTE"},"payload":{"type":"json","data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}"}}}
D/GetNotificationsWS( 2504): sendAidlRequest(): was sent by CCE successfully!
D/WaitableIntentService( 2504): ServiceHandler.handleMessage: mWaitCount=2
,D/MMApiWebService( 2504): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
D/LocationInitializer( 1937): Restart initialization of location
,E/MDM     ( 1690): [201] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1690): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/PeopleContactsSync( 1937): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 1937): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/CertBlacklister(  880): Certificate blacklist changed, updating...
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CertBlacklister(  880): Certificate blacklist updated
,I/GservicesProvider( 4835): main difference update completed
,I/MMApiWSBase( 2504): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6273 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1937): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1937): Failed to find provider info for com.google.android.wearable.settings
,W/GCoreFlp( 1690): No location to return for getLastLocation()
W/FusedLocationProvider( 1690): location=null
,I/SundryService( 2504): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 2504): setWaitEnabled(): mWaitCount=1 isWaitEnabled=false
D/SundryService( 2504): onHandleIntent(): isWaitEnabled=true
D/WaitableIntentService( 2504): ServiceHandler.handleMessage: mWaitCount=1
,I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6297 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ContactLocale( 6273): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6314 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 6297): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 6314): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6297): Created com.android.providers.calendar.CalendarAlarmManager@230dc202(com.android.providers.calendar.CalendarProvider2@2d846713)
,I/PeopleContactsSync( 1937): CP2 cleanup done, kept= duration=441 ms
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6341 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/art     ( 4835): Explicit concurrent mark sweep GC freed 8813(436KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 724us total 34.641ms
,I/art     (  880): Explicit concurrent mark sweep GC freed 19006(877KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.424ms total 117.716ms
,I/art     (  880): WaitForGcToComplete blocked for 36.934ms for cause HeapTrim
,I/ActivityManager(  880): Killing 6159:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10055/pid_6159/cgroup.procs: No such file or directory
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
,I/PeopleContactsSync( 1937): ===CP2 sync finished, success=true, time=789,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,D/MMApiWSBase( 2504): doRequest(): v1/gns/list/messages resp length: 1363
,D/CCE     ( 2504): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 2504): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/PeopleSync( 1937): ***Sync finished***, duration: 4215 [5005f081]
,D/Checkin ( 2504): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 2504): handleGetNotificationsResponse(): got 0; more=false
,I/ActivityManager(  880): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6370 uid=10054 gids={50054, 9997, 3003} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1937): Classify the device as Phone.
,I/CheckinTask( 1937): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1937): Checking schedule, now: 1450100658531 next: 1450701795518
I/CheckinService( 1937): active receiver: disabled
,D/CheckinService( 1937): Recording last checkin time for package unspecified as 1450100658622
,E/UpdateRequestReceiver( 6370): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6370): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6370): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6370): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/CheckinService( 1937): Checkin interval check for package: unspecified last checkin: 1450100658622 min interval config: 0 actual interval: 101
,I/SystemUpdateService( 1937): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,I/ActivityManager(  880): Killing 5624:com.google.android.youtube/u0a101 (adj 15): empty #7
,I/CheckinService( 1937): Checking schedule, now: 1450100658849 next: 1450701795518
I/CheckinService( 1937): active receiver: disabled
,D/SystemUpdateService( 1937): onCreate
,W/libprocessgroup(  880): failed to open /acct/uid_10101/pid_5624/cgroup.procs: No such file or directory
,D/SystemUpdateService( 1937): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1937): cancelUpdate (empty URL)
I/SystemUpdateService( 1937): active receiver: disabled
,I/GCoreUlr( 1690): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1690): DispatchingService.onCreate()
,W/DataUsage( 2504): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2504): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  880): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6407 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CalendarProvider2( 6297): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6297): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/art     ( 1937): Explicit concurrent mark sweep GC freed 30577(1952KB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 15MB/25MB, paused 1.279ms total 88.969ms
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6415 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
W/SQLiteConnectionPool( 1937): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ActivityManager(  880): Killing 6191:com.google.android.talk/u0a70 (adj 15): empty #7
,W/ContextImpl( 6074): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/art     ( 4835): Explicit concurrent mark sweep GC freed 3962(167KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 694us total 26.963ms
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6191/cgroup.procs: No such file or directory
,I/GAV2    ( 6074): Thread[GAThread,5,main]: No campaign data found.
,W/ResourcesManager( 6415): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GCoreUlr( 1690): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1690): Unbound from all location providers
I/GCoreUlr( 1690): Place inference reporting - stopped
,I/art     ( 4835): Explicit concurrent mark sweep GC freed 2819(110KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 544us total 23.199ms
,I/GCoreUlr( 1690): DispatchingService.onDestroy()
I/GCoreUlr( 1690): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1690): Unbound from all location providers
I/GCoreUlr( 1690): Place inference reporting - stopped
,I/Gmail   ( 6407): getAccountsCursor
,D/ActivityThread( 6407): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,D/SystemUpdateService( 1937): onDestroy
,E/DynamiteModule( 1937): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1937): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 1937): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1937): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 1937): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 1937): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1937): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1937): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1937): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1937): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1937): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1937): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2611)
E/DynamiteModule( 1937): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/DynamiteModule( 1937): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1369)
E/DynamiteModule( 1937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1937): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 1937): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/DynamiteModule( 1937): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 1937): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 1937): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/DynamiteModule( 1937): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/DynamiteModule( 1937): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 1937): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 1937): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 1937): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 1937): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 1937): 		... 17 more
E/DynamiteModule( 1937): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,I/DynamiteModule( 1937): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 1937): Selected local version of com.google.android.gms.flags
,I/ActivityManager(  880): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=6457 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 326us total 24.138ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.634ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 20.210ms
,D/SystemEventReceiver( 1937): Received GSERVICES_CHANGED broadcast
W/GAV2    ( 6407): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/OcrUtils( 1937): Updating ocr activity enabled=false
,I/Exchange( 6457): EasService.onCreate
,W/ActivityManager(  880): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Exchange( 6457): RestartPingTask
,W/ResourcesManager( 1539): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,I/Exchange( 6457): RestartPingsTask did not start any pings.
I/Exchange( 6457): PSS stopIfIdle
I/Exchange( 6457): PSS has no active accounts; stopping service.
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  880): Explicit concurrent mark sweep GC freed 20146(952KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.524ms total 145.832ms
,I/Gmail   ( 6407): Observing account changes for notifications
,I/Exchange( 6457): onDestroy
,I/ActivityManager(  880): Killing 6230:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     ( 1937): Explicit concurrent mark sweep GC freed 9141(549KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 15MB/25MB, paused 1.161ms total 80.751ms
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_6230/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 6314:com.motorola.context/u0a8 (adj 15): empty #7
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_6314/cgroup.procs: No such file or directory
I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Gmail   ( 6407): getAccountsCursor
,W/Gmail   ( 6407): Sync started for account: account:61035162
,I/Launcher( 1556): Deferring update until onResume
,I/GoogleHttpClient( 4835): GMS http client unavailable, use old client
,E/SQLiteLog( 6407): (283) recovered 118 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/art     ( 1690): Explicit concurrent mark sweep GC freed 65900(3MB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 14MB/23MB, paused 1.276ms total 96.247ms
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1c8a8f8d
,I/GCoreNlp( 1690): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Gmail   ( 6407): MailSyncAdapterService#onSyncCanceled Thread[SyncAdapterThread-1,5,main]
,I/Gmail   ( 6407): notifyAccountChanged
,I/Gmail   ( 6407): getAccountsCursor
,I/Gmail   ( 6407): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6407): notifyAccountChanged
,I/Gmail   ( 6407): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/ActivityManager(  880): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,I/Gmail   ( 6407): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6407): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/OcrModelManager( 1937): Updating downloaded model state (gservices changed)
,I/art     ( 4835): Explicit concurrent mark sweep GC freed 3156(143KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 757us total 34.945ms
,I/Gmail   ( 6407): getAccountsCursor
,I/Gmail   ( 6407): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 12263, normalSync: true
,W/ResourcesManager( 6407): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6407): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/GCM     ( 1690): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 6407): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 4835): Explicit concurrent mark sweep GC freed 11832(566KB) AllocSpace objects, 1(39KB) LOS objects, 40% free, 7MB/12MB, paused 1.384ms total 36.342ms
,W/System  ( 6407): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6407): Installed default security provider GmsCore_OpenSSL
,I/ValidateNoPeople(  880): mEvictionCount: 0
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1690): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=6524 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6297:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/GCoreUlr( 1690): DispatchingService.onCreate()
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_6297/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=288, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311651, SEQNUM=4417, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-847, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,E/SQLiteLog( 6273): (284) automatic index on sqlite_sq_B7561FC8(STAT_DATA_ID)
,E/SQLiteLog( 6273): (284) automatic index on sqlite_sq_B7561840(STAT_DATA_ID)
,I/art     ( 1690): Explicit concurrent mark sweep GC freed 18077(1040KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 14MB/23MB, paused 1.715ms total 148.752ms
,I/GCoreUlr( 1690): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,E/SQLiteLog( 6273): (284) automatic index on sqlite_sq_B76132C0(STAT_DATA_ID)
,E/SQLiteLog( 6273): (284) automatic index on sqlite_sq_B76150B8(STAT_DATA_ID)
,I/ActivityManager(  880): Killing 6341:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/art     (  880): Explicit concurrent mark sweep GC freed 26224(1246KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 20MB/30MB, paused 1.794ms total 130.226ms
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_6341/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 6370:com.google.android.configupdater/u0a54 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10054/pid_6370/cgroup.procs: No such file or directory
,W/GeofencerStateMachine( 1690): Ignoring removeGeofence because network location is disabled.
,I/ActivityManager(  880): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6557 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6577 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver: pid=6592 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6457:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10060/pid_6457/cgroup.procs: No such file or directory
,I/GservicesUpdateTask( 6524): Updating Gservices keys
,E/ctxmgr  ( 1690): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/ConfigService( 1690): onDestroy
,W/ctxmgr  ( 1690): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10016, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1690): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/ActivityManager(  880): Killing 6415:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/GCoreUlr( 1690): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6415/cgroup.procs: No such file or directory
,I/GCoreUlr( 1690): Unbound from all location providers
I/GCoreUlr( 1690): Place inference reporting - stopped
,I/GCoreUlr( 1690): DispatchingService.onDestroy()
I/GCoreUlr( 1690): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1690): Unbound from all location providers
I/GCoreUlr( 1690): Place inference reporting - stopped
,I/art     ( 4835): Explicit concurrent mark sweep GC freed 5884(294KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 7MB/10MB, paused 553us total 45.719ms
,I/GAv4    ( 6557): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6557):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6557):   adb logcat -s GAv4
,W/GAv4    ( 6557): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  880): Killing 6407:com.google.android.gm/u0a63 (adj 15): empty #7
,W/GAv4    ( 6557): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6557): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 6557): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,W/libprocessgroup(  880): failed to open /acct/uid_10063/pid_6407/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6648 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SundryService( 2504): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
,D/WaitableIntentService( 2504): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 2504): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 2504): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 2504): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6666 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6557): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 6648): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 6557): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6557): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6557): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6557): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6648): Created com.android.providers.calendar.CalendarAlarmManager@230dc202(com.android.providers.calendar.CalendarProvider2@2d846713)
,V/JNIHelp ( 6557): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PhoneMonitor( 6666): Register our PhoneStateListener
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:32000 mC
,V/SetupWizard( 6666): Connected to Gservices successfully
,I/ActivityManager(  880): Killing 5976:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/System  ( 6557): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6557): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_5976/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=6692 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GCM     ( 1690): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1690): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiService(  880): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@3d853a2d}
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6715 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Flag    ( 6557): Duration spec must be at least 2 characters long
,W/ResourcesManager( 6715): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6692): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6692): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6692): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6692):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6692):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6692): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6692): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6692): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  880): Killing 6273:android.process.acore/u0a7 (adj 15): empty #7
,W/GAv4    ( 6692): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6692): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_6273/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6742 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 6742): getAccountsCursor
D/ActivityThread( 6742): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 6692): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  880): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=6777 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/LibraryLoader( 6692): Time to load native libraries: 2 ms (timestamps 7423-7425)
I/LibraryLoader( 6692): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6692): Binding Chromium to main looper Looper (main, tid 1) {22a3490d}
,I/LibraryLoader( 6692): Expected native library version number "",actual native library version number ""
,I/chromium( 6692): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6692): Initializing chromium process, singleProcess=true
W/art     ( 6692): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6692): ApplicationContext is null in ApplicationStatus
,W/chromium( 6692): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6692): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6692): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6692): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6692): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6692): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6692): Local Branch: 
I/Adreno-EGL( 6692): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6692): Local Patches: NONE
I/Adreno-EGL( 6692): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6692): Requires BLUETOOTH permission
,I/art     (  880): Explicit concurrent mark sweep GC freed 16188(819KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.440ms total 116.589ms
,W/ActivityManager(  880): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 6777): EasService.onCreate
,I/NSApplication( 6692): Starting up...
,I/Exchange( 6777): RestartPingTask
,I/Gmail   ( 6742): Observing account changes for notifications
,I/CalendarProvider2( 6648): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6648): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/SyncAdapterService( 6692): Ignoring sync request for non-current account
,W/GAV2    ( 6742): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Exchange( 6777): RestartPingsTask did not start any pings.
,I/Exchange( 6777): PSS stopIfIdle
I/Exchange( 6777): PSS has no active accounts; stopping service.
,I/ActivityManager(  880): Killing 6577:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_6577/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 6524:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_6524/cgroup.procs: No such file or directory
I/Gmail   ( 6742): getAccountsCursor
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6836 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Exchange( 6777): onDestroy
,I/ActivityManager(  880): Killing 6592:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  313): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 26.837ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.061ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.873ms
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_6592/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 6648:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_6648/cgroup.procs: No such file or directory
,E/SQLiteLog( 6742): (283) recovered 2 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/ActivityManager(  880): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=6863 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 6742): notifyAccountChanged
,I/Gmail   ( 6742): getAccountsCursor
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6742): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6742): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6742): getAccountsCursor
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6886 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/MusicStore( 6863): Database version: 120
,I/Gmail   ( 6742): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6742): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6918 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6666:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_6666/cgroup.procs: No such file or directory
,W/ResourcesManager( 6918): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6863): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6863): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6863): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6863): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6863): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6863): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6863): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6863): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1aafb76c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6863): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6863): GMSCore installation verified
,I/ConfigStore( 6863): Config Database version: 1
I/Babel_SMS( 6918): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6918): MmsConfig.loadMmsSettings
I/Babel_SMS( 6918): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6918): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6918): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6918): MmsConfig.loadFromResources
,E/Babel_SMS( 6918): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6918): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6918): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6918): startup - clean
,I/MediaRouter( 6863): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/Babel   ( 6918): deleted: false for 0
,I/GHttpClientFactory( 6863): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6863): Using platform SSLCertificateSocketFactory
,I/NetworkMonitor( 6863): type=WIFI subType= reason=null isConnected=true
I/MusicLifecycle( 6863): Sync started
,I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6961 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/NetworkMonitor( 6863): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 6863): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6863): Using platform SSLCertificateSocketFactory
,W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6918): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6918): Unsupported mime video/mpeg2
,I/ActivityManager(  880): Killing 6715:com.motorola.context/u0a8 (adj 15): empty #7
,I/VideoCapabilities( 6918): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
,I/ContactLocale( 6961): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_6715/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6988 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6692:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_6692/cgroup.procs: No such file or directory
,I/vclib   ( 6918): onServiceConnected
W/Babel   ( 6918): Attempted to change video mute state without an active call.
,W/asset   ( 6988): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6988): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 6988): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6988): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 6918): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6918): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6918): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PackageBroadcastService( 1937): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1937): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1556): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@279d8f5a new=com.google.android.velvet.VelvetApplication@279d8f5a
,I/UpdateIcingCorporaServi( 6836): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/System  ( 6918): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6918): Installed default security provider GmsCore_OpenSSL
,I/Icing   ( 1937): updateResources: need to parse f{com.google.android.gms}
,I/art     (  880): Explicit concurrent mark sweep GC freed 13117(668KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.928ms total 152.021ms
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7024 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 7024): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 6836): UpdateCorporaTask done [took 183 ms] updated apps [took 183 ms] 
,I/ActivityManager(  880): Killing 6742:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10063/pid_6742/cgroup.procs: No such file or directory
,D/WifiService(  880): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@3d853a2d}
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,I/art     ( 4835): Explicit concurrent mark sweep GC freed 3345(137KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 401us total 26.755ms
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,W/BaseAppContext( 1937): Using Auth Proxy for data requests.
,I/ActivityManager(  880): Killing 6777:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10060/pid_6777/cgroup.procs: No such file or directory
,I/MusicSyncAdapter( 6863): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 6863): Periodic update
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7061 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=7079 uid=10053 gids={50053, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6886:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/MusicApiClient( 6863): Activity events list is null or empty. Skip reporting.
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_6886/cgroup.procs: No such file or directory
,I/MusicLifecycle( 6863): Sync ended
,I/ActivityManager(  880): Killing 6988:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_6988/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.cloudprint for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService: pid=7096 uid=10053 gids={50053, 9997, 3003, 1028} abi=armeabi-v7a
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 7079): Sync request not initiated by GCP app. Dropping
,I/ActivityManager(  880): Killing 6836:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_6836/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.docs.editors.sheets for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService: pid=7127 uid=10105 gids={50105, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Auth.Api.Credentials( 1937): [CredentialSyncAdapter] Unknown sync event.
,D/Finsky  ( 7061): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 1937): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7152 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 22.829ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 22.795ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 20.426ms
,W/ResourcesManager( 7152): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Icing   ( 1937): Loaded CLD2 Version V2.0 - 20141016
,D/Finsky  ( 7061): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/Icing   ( 1937): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,W/Settings( 7061): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7061): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CalendarProvider2( 7152): Created com.android.providers.calendar.CalendarAlarmManager@230dc202(com.android.providers.calendar.CalendarProvider2@2d846713)
,D/Finsky  ( 7061): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Ads     ( 7061): Skipping gmscore version check
D/Finsky  ( 7061): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  880): Killing 6557:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_6557/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7187 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6961:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_6961/cgroup.procs: No such file or directory
,D/Finsky  ( 7061): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7061): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ActivityThread( 7187): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
I/Gmail   ( 7187): getAccountsCursor
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4    ( 7127): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7127):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7127):   adb logcat -s GAv4
,I/ActivityManager(  880): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=7221 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAv4    ( 7127): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7127): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7127): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7127): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.312.11.30
,I/art     (  880): Explicit concurrent mark sweep GC freed 18811(792KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.800ms total 116.713ms
,W/ActivityManager(  880): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 7221): EasService.onCreate
,I/Gmail   ( 7187): Observing account changes for notifications
,I/Exchange( 7221): RestartPingTask
,W/GAV2    ( 7187): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Exchange( 7221): RestartPingsTask did not start any pings.
I/Exchange( 7221): PSS stopIfIdle
,I/Exchange( 7221): PSS has no active accounts; stopping service.
,I/CalendarSyncAdapter( 6074): Found no pending settings
,I/Gmail   ( 7187): getAccountsCursor
,I/Exchange( 7221): onDestroy
,I/ActivityManager(  880): Killing 7024:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7024/cgroup.procs: No such file or directory
,V/AlarmManager(  880): send {3d0f4a5e, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
D/Finsky  ( 7061): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  880): done {3d0f4a5e, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [9ms]
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 7152): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 7152): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=7274 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 7187): (283) recovered 3 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/ResourcesManager( 7274): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Killing 6863:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/Gmail   ( 7187): notifyAccountChanged
,I/Gmail   ( 7187): getAccountsCursor
,I/Gmail   ( 7187): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7187): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/PackageSettings(  880): Skipping PackageSetting{246de321 com.example.hello/10359} due to missing metadata
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_6863/cgroup.procs: No such file or directory
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Killing 7079:com.google.android.apps.cloudprint:sync/u0a53 (adj 15): empty #7
,I/Gmail   ( 7187): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7187): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  880): Killing 7096:com.google.android.apps.cloudprint/u0a53 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10053/pid_7079/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10053/pid_7096/cgroup.procs: No such file or directory
,W/ResourcesManager( 7127): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7127): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.download.MusicCommunicator: pid=7306 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/JNIHelp ( 7127): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7187): getAccountsCursor
,I/ProviderInstaller( 7127): Installed default security provider GmsCore_OpenSSL
,I/MusicStore( 7306): Database version: 120
,I/qtaguid ( 7061): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 7061): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 7061): untagSocket(37) failed with errno -22
,D/Finsky  ( 7061): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7306): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/ActivityManager(  880): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7331 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 7331): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7331): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7306): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7306): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7306): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7306): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7331): VM with version 2.1.0 has multidex support
I/MultiDex( 7331): install
I/MultiDex( 7331): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7331): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/JNIHelp ( 7306): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 7061): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 7061): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 7061): untagSocket(37) failed with errno -22
,W/ActivityThread( 7331): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7331): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b007e9d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7331): Installed default security provider GmsCore_OpenSSL
,W/ActivityThread( 7306): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7306): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1aafb76c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7306): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7306): GMSCore installation verified
,I/ConfigStore( 7306): Config Database version: 1
,D/ChimeraCfgMgr( 7331): Reading stored module config
,D/ChimeraCfgMgr( 7331): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/MediaRouter( 7306): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 7306): type=WIFI subType= reason=null isConnected=true
,D/CAR.SERVICE( 7331): Connecting to CarCallService...
,I/NetworkMonitor( 7306): type=WIFI subType= reason=null isConnected=true
,D/NativeLibraryUtils( 7331): Install completed successfully. count=14 extracted=0
,I/art     ( 7331): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7331): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7306): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/GHttpClientFactory( 7306): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7306): Using platform SSLCertificateSocketFactory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7306): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/cache
,D/LocationInitializer( 1937): Restart initialization of location
D/WearableService( 1690): callingUid 10016, callindPid: 1690
,D/CAR.SERVICE( 7331): com.google.android.projection.gearhead isn't installed.
,I/art     (  880): Explicit concurrent mark sweep GC freed 18011(1094KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.429ms total 116.803ms
D/AuthorizationBluetoothService( 1690): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/CAR.TEL.Service( 7331): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 7331): Creating a new PhoneAdapter instance
,W/ActivityManager(  880): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 7331): setListener: com.google.android.gms.car.dn@39755a10
W/ActivityManager(  880): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,E/MDM     ( 1690): [178] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CAR.TEL.PhoneAdapter( 7331): Returning an existing PhoneAdapter instance.
,D/CAR.TEL.Service( 7331): Starting CarCallService with initial phone null
,W/GCoreFlp( 1690): No location to return for getLastLocation()
W/FusedLocationProvider( 1690): location=null
,I/MusicLeanback( 7306): Stop autocaching.
,I/MusicLeanback( 7306): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 7306): Stop autocaching.
,D/CAR.SERVICE( 7331): Package validated; name: com.android.vending
,E/GmsUtils( 7306): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7306): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/Finsky  ( 7061): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7306): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/cache
,I/ActivityManager(  880): Killing 7221:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10060/pid_7221/cgroup.procs: No such file or directory
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 7061): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 7061): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 7061): untagSocket(37) failed with errno -22
,W/ResourcesManager( 7061): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7061): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7061): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 7061): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 7061): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  880): send {34087278, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,V/AlarmManager(  880): send {2cec6240, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED}
,V/AlarmManager(  880): done {34087278, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [25ms]
V/AlarmManager(  880): done {2cec6240, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED} [26ms]
D/DeviceConnectionService( 1690): client connected with version: 8296000
,D/Finsky  ( 7061): [835] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Killing 7127:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
,I/ActivityManager(  880): Killing 7152:com.android.providers.calendar/u0a5 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10105/pid_7127/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_7152/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 6918:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6918/cgroup.procs: No such file or directory
,W/ProcessCpuTracker(  880): Skipping unknown process pid 7407
,W/ProcessCpuTracker(  880): Skipping unknown process pid 7408
,W/ProcessCpuTracker(  880): Skipping unknown process pid 7410
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:33000 mC
,I/GAV2    ( 7187): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7415 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7415): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 7415): Created com.android.providers.calendar.CalendarAlarmManager@230dc202(com.android.providers.calendar.CalendarProvider2@2d846713)
,I/MusicLeanback( 7306): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 7306): Stop autocaching.
,E/GmsUtils( 7306): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7306): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/CAR.SERVICE( 7331): mConnectedToCar = false, abort
,E/ActivityThread( 7331): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2c8a03f8 that was originally bound here
E/ActivityThread( 7331): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2c8a03f8 that was originally bound here
E/ActivityThread( 7331): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 7331): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 7331): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 7331): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 7331): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7331): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7331): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7331): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 7331): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 7331): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 7331): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 7331): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 7331): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 7331): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 7331): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 7331): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 7331): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7331): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7331): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 7331): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7331): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7331): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 7331): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 7331): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1700ded3 that was originally bound here
E/ActivityThread( 7331): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1700ded3 that was originally bound here
E/ActivityThread( 7331): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 7331): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 7331): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 7331): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 7331): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7331): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 7331): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 7331): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 7331): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 7331): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 7331): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 7331): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 7331): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 7331): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 7331): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 7331): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7331): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7331): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 7331): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7331): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7331): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 7331): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ActivityManager(  880): Unbind failed: could not find connection for android.os.BinderProxy@38717dec
,I/CalendarProvider2( 7415): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 7415): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  880): Killing 7187:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10063/pid_7187/cgroup.procs: No such file or directory
,V/AlarmManager(  880): send {780b44a, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {780b44a, *walarm*:android.content.syncmanager.SYNC_ALARM} [5ms]
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=290, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311107, SEQNUM=4447, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-887, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  880): Waited long enough for: ServiceRecord{1c2d6b6a u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/ActivityManager(  880): Killing 7061:com.android.vending/u0a32 (adj 15): empty #7
,I/ActivityManager(  880): Killing 7331:com.google.android.gms:car/u0a16 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_7061/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_7331/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7468 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  880): send {23f77fbb, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
V/AlarmManager(  880): done {23f77fbb, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [45ms]
,D/Finsky  ( 7468): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7468): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7468): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7468): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7468): Skipping gmscore version check
,D/Finsky  ( 7468): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7468): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7468): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7468): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Finsky  ( 7468): [880] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7468): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  880): Killing 7306:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7306/cgroup.procs: No such file or directory
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
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
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7534 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ContactLocale( 7534): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/IcingInternalCorpora( 1937): getNumBytesRead when not calculated.
,I/ActivityManager(  880): Killing 7274:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_7274/cgroup.procs: No such file or directory
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  880): send {174a9eb4, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {35db26ee, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7569 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  880): done {174a9eb4, *alarm*:android.intent.action.TIME_TICK} [109ms]
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310334, SEQNUM=4460, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-906, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/GAv4    ( 7569): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7569):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7569):   adb logcat -s GAv4
,W/GAv4    ( 7569): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7569): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7569): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  880): done {35db26ee, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [333ms]
I/ActivityManager(  880): Killing 7415:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_7415/cgroup.procs: No such file or directory
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  880): send {780b44a, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {780b44a, *walarm*:android.content.syncmanager.SYNC_ALARM} [5ms]
,I/ActivityManager(  880): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7598 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,E/ActivityThread( 1937): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  880): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 573406, reason: UserStart
,I/ActivityManager(  880): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=7629 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.551ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.043ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.818ms
,I/Gmail   ( 7629): getAccountsCursor
,D/ActivityThread( 7629): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=7654 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  880): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 7629): Observing account changes for notifications
,I/GAv4    ( 7598): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7598):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7598):   adb logcat -s GAv4
,W/GAv4    ( 7598): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  880): Explicit concurrent mark sweep GC freed 20962(982KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.680ms total 123.729ms
,W/GAv4    ( 7598): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7598): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7598): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,I/Exchange( 7654): EasService.onCreate
,I/Exchange( 7654): RestartPingTask
,I/Exchange( 7654): RestartPingsTask did not start any pings.
I/Exchange( 7654): PSS stopIfIdle
I/Exchange( 7654): PSS has no active accounts; stopping service.
,W/GAV2    ( 7629): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/SQLiteLog( 7598): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
,W/Gmail   ( 7629): Sync started for account: account:61035162
,E/SQLiteLog( 7629): (283) recovered 4 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 7629): getAccountsCursor
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 7654): onDestroy
I/ActivityManager(  880): Killing 6074:com.google.android.calendar/u0a49 (adj 15): empty #7
,I/Gmail   ( 7629): notifyAccountChanged
,I/Gmail   ( 7629): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7629): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7629): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7629): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  880): failed to open /acct/uid_10049/pid_6074/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7598): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 7598): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7598): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7598): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7598): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Gmail   ( 7629): notifyAccountChanged
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 7598): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7598): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7598): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7629): getAccountsCursor
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7629): getAccountsCursor
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Killing 7468:com.android.vending/u0a32 (adj 15): empty #7
,I/Gmail   ( 7629): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 12263, normalSync: true
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_7468/cgroup.procs: No such file or directory
V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 7629): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7629): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7629): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7629): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7629): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1690): Explicit concurrent mark sweep GC freed 27461(1736KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 14MB/23MB, paused 1.145ms total 80.102ms
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Herrevad( 1690): mobile connection type with no cell id
,I/art     ( 7629): Explicit concurrent mark sweep GC freed 1433(96KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 10MB/14MB, paused 643us total 68.675ms
,I/Gmail   ( 7629): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 12823, normalSync: true
,I/Gmail   ( 7629): lowestBackward conversation id 0
,I/Gmail   ( 7629): notifyAccountChanged
,I/Gmail   ( 7629): getAccountsCursor
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7629): notifyAccountChanged
,W/Gmail   ( 7629): Sync complete for account: account:61035162
,I/Gmail   ( 7629): getAccountsCursor
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1937): Indexing 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A from com.google.android.gm
,I/Gmail   ( 7629): Backfilling search sequence table
,I/Icing   ( 1937): Indexing done 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A
,I/ActivityManager(  880): Killing 7534:android.process.acore/u0a7 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7534/cgroup.procs: No such file or directory
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/GAV2    ( 7629): Thread[GAThread,5,main]: No campaign data found.
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
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
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,D/CdsService( 2504): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/Qj7bIsgzeE6tj%2Bts%2FAYrhnb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mThzmxBd2dVoaQbjnU8RuZianToTIA1vp%2BhvYwJd0Pj9McpRqHy106lzW1hVPrighuOuoB4rP4Sqijkv3LOYnLY1rsFLW2gtgHQDZaZ4oMmmAGqK6KoTwQLwVe3HXyZtN0oB1LkPbLz6XkBLbkakMfsSCcHD5NZCbHTSWeeXrkT0QQTwMlbJNbO0G%2Bj9718Q23ue3MpBibcEYQHr6DH1DtEeWWkuK1oZAhf3QyjGt%2FPGhGPBTlDNdiX4bevijkSJ1cPER7K5KvCGXT3kx%2BZ3SETQ%3D%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/rp9Rq11qzK0oxJ1hGiR3cHb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89r
,D/CdsService( 2504): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/Qj7bIsgzeE6tj%2Bts%2FAYrhnb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mThzmxBd2dVoaQbjnU8RuZianToTIA1vp%2BhvYwJd0Pj9McpRqHy106lzW1hVPrighuOuoB4rP4Sqijkv3LOYnLY1rsFLW2gtgHQDZaZ4oMmmAGqK6KoTwQLwVe3HXyZtN0oB1LkPbLz6XkBLbkakMfsSCcHD5NZCbHTSWeeXrkT0QQTwMlbJNbO0G%2Bj9718Q23ue3MpBibcEYQHr6DH1DtEeWWkuK1oZAhf3QyjGt%2FPGhGPBTlDNdiX4bevijkSJ1cPER7K5KvCGXT3kx%2BZ3SETQ%3D%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/rp9Rq11qzK0oxJ1hGiR3cHb98SYvcz3La8G7Q%2FzZ
,I/OtaApp  ( 2504): [info] > OTAUpgradeSource.handleCheckWSResponse: check_for_update : 200 : {"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/Qj7bIsgzeE6tj%2Bts%2FAYrhnb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mThzmxBd2dVoaQbjnU8RuZianToTIA1vp%2BhvYwJd0Pj9McpRqHy106lzW1hVPrighuOuoB4rP4Sqijkv3LOYnLY1rsFLW2gtgHQDZaZ4oMmmAGqK6KoTwQLwVe3HXyZtN0oB1LkPbLz6XkBLbkakMfsSCcHD5NZCbHTSWeeXrkT0QQTwMlbJNbO0G%2Bj9718Q23ue3MpBibcEYQHr6DH1DtEeWWkuK1oZAhf3QyjGt%2FPGhGPBTlDNdiX4bevijkSJ1cPER7K5KvCGXT3kx%2BZ3SETQ%3D%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/rp9Rq11qzK0oxJ1hGiR3cHb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIj
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > AndroidPollingManager.handleIntent: com.motorola.blur.service.blur.upgrade_poll
,I/OtaApp  ( 2504): [info] > Next Polling is scheduled at 1439 mins from now
,I/OtaApp  ( 2504): [info] > CusSM.handleNewVersion: was notified of a new version : src Blur_Version.22.21.28.thea_reteu.reteuall.en.EU: dest Blur_Version.22.46.12.thea_reteu.reteuall.en.EU: current Blur_Version.22.21.28.thea_reteu.reteuall.en.EU: size 263329787: contentTimeStamp 1445419042000
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > PollingManagerService, registerApp(): cUsPollingService
,D/OtaApp  ( 2504): [debug] > PollingManagerService, registerApp(): shortest interval is 86399000
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2504): [info] > Device is NOT rooted. persist.qe=qe 0/0
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > Polling alarm set to expire at: 86928806 Current Time: 529824
,E/OtaApp  ( 2504): [error] > UpgradeSource.isUpgradeAcceptable succeeded 
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > prevDestVersion = Blur_Version.22.46.12.thea_reteu.reteuall.en.EU
,W/OtaApp  ( 2504): [warn] > CusSM.handleNewVersion: already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,E/OtaApp  ( 2504): [error] > CusSM.failNotify: notification failed from repository upgrade for reason already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK; additional information: polling initiated upgrade
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1450100725787, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/OtaApp  ( 2504): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1450100725795, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/OtaApp  ( 2504): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
D/OtaApp  ( 2504): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  NotifiedBlur_Version.22.21.28.thea_reteu.reteuall.en.EUBlur_Version.22.46.12.thea_reteu.reteuall.en.EURepository: upgrade; Location: null; AddOnInfo: polling initiated upgradehttps://motorola-global-en-uk.custhelp.com/app/answers/prod_answer_detail/a_id/1073741450100725807true
,D/OtaApp  ( 2504): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; src: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; dest: Blur_Version.22.46.12.thea_reteu.reteuall.en.EU; upgradeSource:upgrade; Repository: upgrade; Location: null; AddOnInfo: polling initiated upgrade; reportingTag: ; trackingId: 1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E; metaDataVersion: null; ro.carrier: reteu. time: 1450100725
,E/CdsService( 2504): [e] > Failed to parse int value from string null exception :java.lang.NumberFormatException: Invalid int: "null"
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2504): [d] > Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/CdsService( 2504): [d] > State Request getUrl(): url is https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072
,I/OtaApp  ( 2504): [info] > OTAUpgradeSource.handleCheckWSResponse: check_for_update handle new version returned false
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,I/CdsService( 2504): [i] > Received web service call for request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2504): [d] > appending web service request to serviceHandler
,D/OtaApp  ( 2504): [debug] > BotaFotaResolver.parse got the following check order (bota); assuming only bota is enabled
,D/OtaApp  ( 2504): [debug] > OTAUpgradeSource.handleCheckWSResponse: authoritative response from BOTA ERR_NOTFOUND
,D/OtaApp  ( 2504): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/OtaApp  ( 2504): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2504): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > CusSM.runStateMachine: server told to :wait
,D/CdsService( 2504): [d] > appending web service response to serviceHandler
,D/CdsService( 2504): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/check/ctx/ota/key/XT1072 from queue
,D/CdsService( 2504): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}
,D/CdsService( 2504): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}}
,D/OtaApp  ( 2504): [debug] > Inside handleStateResponse
D/OtaApp  ( 2504): [debug] > exec delete from status where _id=1
,D/OtaApp  ( 2504): [debug] > stopTimer, cancel()
,D/OtaApp  ( 2504): [debug] > handleStateResponse server told to : continue
,D/OtaApp  ( 2504): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
D/OtaApp  ( 2504): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  ResultBlur_Version.22.21.28.thea_reteu.reteuall.en.EUBlur_Version.22.46.12.thea_reteu.reteuall.en.EUalready working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OKhttps://motorola-global-en-uk.custhelp.com/app/answers/prod_answer_detail/a_id/1073741450100726482true
,D/OtaApp  ( 2504): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; src: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; dest: Blur_Version.22.46.12.thea_reteu.reteuall.en.EU; upgradeSource:upgrade; already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK; reportingTag: ; trackingId: 1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E; metaDataVersion: null; ro.carrier: reteu. time: 1450100725
,E/CdsService( 2504): [e] > Failed to parse int value from string null exception :java.lang.NumberFormatException: Invalid int: "null"
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2504): [d] > Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/CdsService( 2504): [d] > State Request getUrl(): url is https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072
,I/CdsService( 2504): [i] > Received web service call for request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2504): [d] > appending web service request to serviceHandler
,D/OtaApp  ( 2504): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2504): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2504): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2504): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2504): [debug] > CusSM.sendUpgradeStatus: already sending status
D/OtaApp  ( 2504): [debug] > CusSM.sendUpgradeStatus: already sending status
D/CdsService( 2504): [d] > appending web service response to serviceHandler
D/CdsService( 2504): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072 from queue
,D/OtaApp  ( 2504): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2504): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2504): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2504): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2504): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2504): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2504): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2504): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
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
,D/Volley  ( 2504): [294] BasicNetwork.logSlowRequests: HTTP response for request=<[ ] https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072 0xbbf0b9ca NORMAL 1> [lifetime=4385], [size=323], [rc=500], [retryCount=0]
,E/Volley  ( 2504): [294] BasicNetwork.performRequest: Unexpected response code 500 for https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072
,D/CdsService( 2504): [d] > failure response with status code :com.android.volley.ServerError
,D/Volley  ( 2504): [1] Request.finish: 4415 ms: [ ] https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072 0xbbf0b9ca NORMAL 1
,I/CdsService( 2504): [i] > 5XX series error , request will be backed off and will be retried
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,I/CdsService( 2504): [i] > Retry handler returned true; Retry web request after backoff time: 2000
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,D/Volley  ( 2504): [298] BasicNetwork.logSlowRequests: HTTP response for request=<[ ] https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072 0xbbf0b9ca NORMAL 1> [lifetime=4097], [size=331], [rc=200], [retryCount=0]
,D/CdsService( 2504): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}
D/Volley  ( 2504): [1] Request.finish: 4114 ms: [ ] https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072 0xbbf0b9ca NORMAL 1
,D/CdsService( 2504): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}}
D/OtaApp  ( 2504): [debug] > Inside handleStateResponse
D/OtaApp  ( 2504): [debug] > exec delete from status where _id=2
,D/OtaApp  ( 2504): [debug] > stopTimer, have stoped, do nothing
,D/OtaApp  ( 2504): [debug] > handleStateResponse server told to : continue
D/OtaApp  ( 2504): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2504): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2504): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2504): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2504): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2504): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2504): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2504): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
I/LaunchCheckinHandler(  880): cleanup(): cleared. Last call was 10554 ms ago
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2504): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2504): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 2504): [debug] > DownloadActivity, FormattedText
,D/CdsService( 2504): [d] > appending web service response to serviceHandler
,D/CdsService( 2504): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072 from queue
D/CdsService( 2504): [d] > No pending web request. shutdown webservice
,I/OtaApp  ( 2504): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2504): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2504): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2504): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2504): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,I/CdsService( 2504): [i] > Stopping webservice android service
,D/Checkin ( 2504): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  880): send {780b44a, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {780b44a, *walarm*:android.content.syncmanager.SYNC_ALARM} [2ms]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=267, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310758, SEQNUM=4487, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-982, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ClearcutLoggerApiImpl( 1937): disconnect managed GoogleApiClient
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {174a9eb4, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {44f94e3, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  880): done {44f94e3, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [11ms]
,V/AlarmManager(  880): done {174a9eb4, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {174a9eb4, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {2b061802, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  880): send {154d9672, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  880): done {2b061802, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [24ms]
,V/AlarmManager(  880): done {174a9eb4, *alarm*:android.intent.action.TIME_TICK} [51ms]
,V/AlarmManager(  880): done {154d9672, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [53ms]
,I/EventLogService( 1937): Aggregate from 1450100649776 (log), 1450099083387 (data)
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310637, SEQNUM=4496, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311235, SEQNUM=4498, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310058, SEQNUM=4500, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2118, POWER_SUPPLY_CHARGE_COUNTER=-2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310365, SEQNUM=4502, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310646, SEQNUM=4503, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {174a9eb4, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {780b44a, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {780b44a, *walarm*:android.content.syncmanager.SYNC_ALARM} [12ms]
,V/AlarmManager(  880): done {174a9eb4, *alarm*:android.intent.action.TIME_TICK} [44ms]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310940, SEQNUM=4507, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311218, SEQNUM=4512, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310637, SEQNUM=4514, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-46, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  880): send {174a9eb4, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {3729801f, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  880): done {174a9eb4, *alarm*:android.intent.action.TIME_TICK} [52ms]
,V/AlarmManager(  880): done {3729801f, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [93ms]
,I/LaunchCheckinHandler(  880): cleanup(): cleared. Last call was 813511 ms ago
I/ActivityManager(  880): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=7890 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GCM     ( 1937): Message from null null
E/GCM     ( 1937): Dropping message from null
,I/art     (  880): Explicit concurrent mark sweep GC freed 25993(1420KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 20MB/30MB, paused 1.495ms total 115.121ms
,W/ResourcesManager( 7890): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7890): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7890): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7890): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7890): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 7890): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7890): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/YouTube MDX( 7890): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7890): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/dex2oat ( 7943): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-2118966873.jar --oat-fd=27 --oat-location=/data/data/com.google.android.youtube/cache/ads-2118966873.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7943): dex2oat took 110.887ms (threads: 4)
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7890): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7890): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7890): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 7890): Found 10016
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7890): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  880): Killing 7569:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10055/pid_7569/cgroup.procs: No such file or directory
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310369, SEQNUM=4522, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-178, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  880): send {174a9eb4, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {35571f6, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8002 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  880): done {174a9eb4, *alarm*:android.intent.action.TIME_TICK} [93ms]
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310646, SEQNUM=4526, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-218, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/GAv4    ( 8002): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8002):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8002):   adb logcat -s GAv4
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,W/GAv4    ( 8002): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8002): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8002): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  880): done {35571f6, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [274ms]
I/ActivityManager(  880): Killing 7654:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10060/pid_7654/cgroup.procs: No such file or directory
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  880): send {174a9eb4, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {2b061802, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {2b061802, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [11ms]
,V/AlarmManager(  880): done {174a9eb4, *alarm*:android.intent.action.TIME_TICK} [50ms]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=257, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310910, SEQNUM=4529, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-314, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=257, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310611, SEQNUM=4530, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  880): send {174a9eb4, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {5312f4e, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  880): send {2221d064, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
V/AlarmManager(  880): send {273c62cd, *alarm*:com.google.android.gms/.common.download.DownloadAlarmReceiver}
V/AlarmManager(  880): send {1f94c512, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  880): done {174a9eb4, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/ProcessStatsService(  880): Prepared write state in 16ms
,I/ProcessStatsService(  880): Prepared write state in 11ms
,V/AlarmManager(  880): done {5312f4e, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [118ms]
,I/ProcessStatsService(  880): Prepared write state in 8ms
,I/ProcessStatsService(  880): Prepared write state in 8ms
,I/ProcessStatsService(  880): Prepared write state in 9ms
,V/AlarmManager(  880): done {2221d064, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [154ms]
,I/ProcessStatsService(  880): Prepared write state in 13ms
,I/ProcessStatsService(  880): Prepared write state in 7ms
,I/ProcessStatsService(  880): Prepared write state in 7ms
,V/AlarmManager(  880): done {273c62cd, *alarm*:com.google.android.gms/.common.download.DownloadAlarmReceiver} [188ms]
I/ProcessStatsService(  880): Prepared write state in 8ms
,V/AlarmManager(  880): done {1f94c512, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [200ms]
,I/ProcessStatsService(  880): Prepared write state in 8ms
,I/ProcessStatsService(  880): Prepared write state in 7ms
,I/ProcessStatsService(  880): Prepared write state in 8ms
,I/ProcessStatsService(  880): Prepared write state in 8ms
,I/ProcessStatsService(  880): Prepared write state in 8ms
,I/ProcessStatsService(  880): Prepared write state in 7ms
,I/ProcessStatsService(  880): Prepared write state in 8ms
,I/ProcessStatsService(  880): Prepared write state in 7ms
,I/ProcessStatsService(  880): Prepared write state in 7ms
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  880): Pruning old procstats: /data/system/procstats/state-2015-12-13-11-12-08.bin
,I/dex2oat ( 8070): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads625816225.jar --oat-fd=96 --oat-location=/data/data/com.google.android.gms/cache/ads625816225.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8070): dex2oat took 42.902ms (threads: 4)
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310979, SEQNUM=4536, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-70, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311222, SEQNUM=4538, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5311): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1800000ms),I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
D/AndroidRuntime( 8093): 
D/AndroidRuntime( 8093): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8093): CheckJNI is OFF
D/AndroidRuntime( 8093): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10362 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 5253:com.test.thalitest/u0a362 (adj 9): stop com.test.thalitest
W/PackageSettings(  880): Skipping PackageSetting{246de321 com.example.hello/10359} due to missing metadata
I/WindowState(  880): WIN DEATH: Window{3dee9cf8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  880): Client connection lost with reason: 4
I/ActivityManager(  880):   Force finishing activity ActivityRecord{3368252d u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  880): Spurious death for ProcessRecord{5359b18 5253:com.test.thalitest/u0a362}, curProc for 5253: null
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10362 user=0: pkg removed
I/ActivityManager(  880):   Force finishing activity ActivityRecord{3368252d u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  880): Duplicate finish request for ActivityRecord{3368252d u0 com.test.thalitest/.MainActivity t3 f}
I/art     ( 2906): Explicit concurrent mark sweep GC freed 15278(2MB) AllocSpace objects, 46(736KB) LOS objects, 40% free, 7MB/12MB, paused 810us total 44.877ms
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1690): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1408): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1408): run()
I/Decoder ( 1408): createOrResetDecoder
I/art     ( 1556): Explicit concurrent mark sweep GC freed 7708(550KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 497us total 107.327ms
I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8122 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     (  880): Explicit concurrent mark sweep GC freed 24459(1618KB) AllocSpace objects, 6(204KB) LOS objects, 33% free, 20MB/30MB, paused 1.780ms total 161.543ms
I/ConfigService( 1690): onCreate
I/art     ( 1937): Explicit concurrent mark sweep GC freed 16379(1173KB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 16MB/21MB, paused 1.077ms total 202.932ms
I/art     (  880): WaitForGcToComplete blocked for 138.623ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = user
D/VoicemailCleanupService( 8122): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1408): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1408): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1408): run()
I/StatsUtilsManager( 1408): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1408): shouldRecordStats() = Too Soon
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8149 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
I/ContactLocale( 8122): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  880): Explicit concurrent mark sweep GC freed 4041(205KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 3.540ms total 182.033ms
I/ActivityManager(  880): Killing 7598:com.google.android.apps.docs/u0a57 (adj 15): empty #7
W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_7598/cgroup.procs: No such file or directory
W/asset   ( 8149): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8149): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8149): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8149): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
D/AndroidRuntime( 8093): Shutting down VM
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8167 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/Launcher( 1556): Deferring update until onResume
W/ContextImpl( 8167): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1937): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1937): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1937): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1937): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1690): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1690): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 1937): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1937): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1937): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1937): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1937): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1937): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1937): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1937): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1937): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1937): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1937): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1937): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1937): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1937): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8193 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7629:com.google.android.gm/u0a63 (adj 15): empty #7
W/libprocessgroup(  880): failed to open /acct/uid_10063/pid_7629/cgroup.procs: No such file or directory
E/SQLiteLog( 1937): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Icing   ( 1937): doRemovePackageData com.test.thalitest
E/SQLiteLog( 1937): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/FileUtils( 1937): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
--------- beginning of crash
E/AndroidRuntime( 1937): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1937): Process: com.google.android.gms, PID: 1937
E/AndroidRuntime( 1937): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1937): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1937): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1937): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1937): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1937): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1937): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1937): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1937): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 1937): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1937): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1937): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1937): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1937): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Icing   ( 1937): Failed to open Apps corpus file.
E/Icing   ( 1937): Failed to open Apps corpus file.
E/GMPM-SVC( 1937): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SharedPreferencesImpl( 1937): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
I/Process ( 1937): Sending signal. PID: 1937 SIG: 9
E/DropBoxManagerService(  880): Can't write: system_app_crash
E/DropBoxManagerService(  880): java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  880): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  880): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  880): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  880): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  880): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  880): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  880): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  880): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  880): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  880): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  880): 	... 5 more
D/ConnectivityService(  880): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2d995a49)
D/WifiService(  880): Client connection lost with reason: 4
D/ConnectivityService(  880): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  880): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
I/ActivityManager(  880): Process com.google.android.gms (pid 1937) has died
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms

```
