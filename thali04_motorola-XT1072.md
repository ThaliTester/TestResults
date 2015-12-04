#### Test 52539314a265f91_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
D/AndroidRuntime( 4844): 
D/AndroidRuntime( 4844): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4844): CheckJNI is OFF
D/AndroidRuntime( 4844): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  887): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  887): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4863 uid=10350 gids={50350, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 4844): Shutting down VM
V/ActivityManager(  887): Display changed displayId=0
W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 4863): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 4863): Time to load native libraries: 2 ms (timestamps 7451-7453)
I/LibraryLoader( 4863): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4863): Binding Chromium to main looper Looper (main, tid 1) {38fe2909}
I/LibraryLoader( 4863): Expected native library version number "",actual native library version number ""
I/chromium( 4863): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4863): Initializing chromium process, singleProcess=true
W/art     ( 4863): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4863): ApplicationContext is null in ApplicationStatus
W/chromium( 4863): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 4863): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4863): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4863): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4863): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4863): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4863): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4863): Local Branch: 
I/Adreno-EGL( 4863): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4863): Local Patches: NONE
I/Adreno-EGL( 4863): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27f5aeb8:true
D/BluetoothAdapter( 4863): 202059: getState() :  mService = null. Returning STATE_OFF
W/ActivityManager(  887): Activity pause timeout for ActivityRecord{f7ebe5d u0 com.test.thalitest/.MainActivity t3}
I/art     (  887): Explicit concurrent mark sweep GC freed 19640(1025KB) AllocSpace objects, 2(192KB) LOS objects, 33% free, 19MB/29MB, paused 1.450ms total 125.778ms
W/art     ( 4863): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4863): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 4863): CordovaWebView is running on device made by: motorola
W/art     ( 4863): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4863): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 4863): Render dirty regions requested: true
D/Atlas   ( 4863): Validating map...
W/chromium( 4863): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 4863): Initialized EGL, version 1.4
D/OpenGLRenderer( 4863): Enabling debug mode 0
I/Keyboard.Facilitator( 1406): onFinishInput()
I/LaunchCheckinHandler(  887): Displayed com.test.thalitest/.MainActivity,cp,ca,951
I/ActivityManager(  887): Displayed com.test.thalitest/.MainActivity: +861ms (total +953ms)
W/IInputConnectionWrapper( 4863): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 4863): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4863): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4863): Cannot call determinedVisibility() - never saw a connection for the pid: 4863
,D/JsMessageQueue( 4863): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4863): JniHelper::setJavaVM(0xb87b9310), pthread_self() = -1196126760
D/JX-Cordova( 4863): jxcore cordova android initializing
,I/art     ( 4863): Background partial concurrent mark sweep GC freed 13326(876KB) AllocSpace objects, 3(3MB) LOS objects, 40% free, 15MB/25MB, paused 1.221ms total 101.190ms
,W/jxcore-log( 4863): Initializing JXcore engine
W/jxcore-log( 4863): JXcore engine is ready
,W/jxcore-log( 4863): Starting JXcore engine
,W/.test.thalitest( 4863): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10350 path="socket:[8383]" dev="sockfs" ino=8383 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 4863): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10350 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 4863): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10350 path="socket:[6494]" dev="sockfs" ino=6494 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 4863): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10350 path="socket:[21933]" dev="sockfs" ino=21933 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4863): Platform android
W/jxcore-log( 4863): 
W/jxcore-log( 4863): Process ARCH arm
W/jxcore-log( 4863): 
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4863): JXcore Cordova bridge is ready!
I/jxcore-log( 4863): 
W/jxcore-log( 4863): JXcore engine is started
,I/chromium( 4863): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4863): Toggling radios to true
I/jxcore-log( 4863): 
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  887): enable():  mBluetooth =null mBinding = false
,W/Settings( 1457): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  887): Message: 1
D/BluetoothManagerService(  887): MESSAGE_ENABLE: mBluetooth = null
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiService(  887): New client listening to asynchronous messages
D/WifiService(  887): setWifiEnabled: true pid=4863, uid=10350
E/WifiService(  887): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine(  887): setting operational mode to 1
,I/ActivityManager(  887): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=4921 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,W/Settings( 1457): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     (  325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 24.484ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.047ms
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
I/jxcore-log( 4863): Radios toggled
I/jxcore-log( 4863): 
I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 22.388ms
,W/Settings( 1457): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1457): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/ResourcesManager( 4921): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 4921): Adding HeadsetService
,D/AdapterServiceConfig( 4921): Adding A2dpService
,D/AdapterServiceConfig( 4921): Adding HidService
,D/AdapterServiceConfig( 4921): Adding HealthService
D/AdapterServiceConfig( 4921): Adding PanService
,D/AdapterServiceConfig( 4921): Adding GattService
D/AdapterServiceConfig( 4921): Adding BluetoothMapService
,D/BluetoothManagerService(  887): Message: 20
,D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2220807e:true
,D/BluetoothAdapterState( 4921): make
,I/bluedroid( 4921): init
I/BluetoothAdapterState( 4921): Entering OffState
,I/bte_conf( 4921): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 4921): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 4921): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,I/bte_conf( 4921): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 4921): get_profile_interface socket
I/bluedroid( 4921): get_profile_interface map_client
,I/GKI_LINUX( 4921): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 4921): Address is:44:80:EB:7B:5A:05
,D/BluetoothManagerService(  887): Bluetooth Adapter name changed to XT1072
,D/BluetoothManagerService(  887): Stored Bluetooth name: XT1072
D/BluetoothAdapterProperties( 4921): Name is: XT1072
,D/BluetoothManagerService(  887): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  887): Message: 40
D/BluetoothManagerService(  887): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 4921): config_hci_snoop_log
,D/BluetoothManagerService(  887): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  887): Broadcasting onBluetoothServiceUp() to 8 receivers.
,E/global frequency( 2550): no tags to log
,D/Checkin ( 2550): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2956): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2956): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/BluetoothAdapterState( 4921): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 4921): Setting state to 11
I/BluetoothAdapterState( 4921): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  887): Message: 60
D/BluetoothManagerService(  887): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  887): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 4921): make
,I/BluetoothBondStateMachine( 4921): StableState(): Entering Off State
,D/TCMD    (  463): NL - Read 1008 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/TCMD    (  463): NL - Read 1008 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
,D/QsoftapCmd(  299): Got softap fwreload command we are passing on
,D/SoftapController(  299): Softap fwReload - Ok
,I/ActivityManager(  887): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4966 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering(  887): InitialState.processMessage what=4
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
,D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,D/CommandListener(  299): Setting iface cfg
D/CommandListener(  299): Trying to bring down wlan0
,D/CommandListener(  299): Clearing all IP addresses on wlan0
,D/HeadsetService( 4921): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 4921): classInitNative: succeeds
D/BluetoothHeadset( 1507): Proxy object connected
,D/BluetoothHeadset( 1533): Proxy object connected
D/BluetoothHeadset(  887): Proxy object connected
,D/HeadsetStateMachine( 4921): make
,D/BSUtils ( 2550): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BluetoothAdapterState( 4921): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 4921): max_hf_connections = 1
I/bluedroid( 4921): get_profile_interface handsfree
,D/BluetoothHeadset( 1507): Proxy object connected
,D/BluetoothAdapterService( 4921): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38fe2909
,D/HeadsetStateMachine( 4921): Enter Disconnected: -2, size: 0
,D/BluetoothA2dp(  887): Proxy object connected
,D/A2dpService( 4921): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 4921): classInitNative: succeeds
I/bluedroid( 4921): get_profile_interface avrcp
,E/PhoneInterfaceManager( 1533): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,E/WifiStateMachine(  887): setWifiState: enabling
,E/RemoteController( 4921): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 4921): classInitNative: succeeds
D/A2dpStateMachine( 4921): make
E/WifiStateMachine(  887): Supplicant start successful
I/bluedroid( 4921): get_profile_interface a2dp
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiMonitor(  887): startMonitoring(wlan0) with mConnected = false
,I/GKI_LINUX( 4921): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
D/BluetoothAdapterService( 4921): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38fe2909
I/BluetoothHidServiceJni( 4921): classInitNative: succeeds
,D/A2dpStateMachine( 4921): Enter Disconnected: -2
,D/HidService( 4921): Received start request. Starting profile...
,I/bluedroid( 4921): get_profile_interface hidhost
D/BluetoothAdapterService( 4921): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38fe2909
,I/wpa_supplicant( 4974): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4974): Long line in configuration file truncated
I/wpa_supplicant( 4974): rfkill: Cannot open RFKILL control device
D/TCMD    (  463): NL - Read 1004 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/BluetoothHealthServiceJni( 4921): classInitNative: succeeds
,D/HealthService( 4921): Received start request. Starting profile...
,I/bluedroid( 4921): get_profile_interface health
D/BluetoothAdapterService( 4921): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38fe2909
I/BluetoothPanServiceJni( 4921): classInitNative(L105): succeeds
,D/PanService( 4921): Received start request. Starting profile...
D/BluetoothPanServiceJni( 4921): initializeNative(L110): pan
I/bluedroid( 4921): get_profile_interface pan
W/ResourcesManager( 4966): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothAdapterService( 4921): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38fe2909
,I/BtGatt.JNI( 4921): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 4921): handleDebugAction() action=null
,D/BtGatt.GattService( 4921): Received start request. Starting profile...
D/BtGatt.GattService( 4921): start()
I/bluedroid( 4921): get_profile_interface gatt
,D/BluetoothAdapterService( 4921): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38fe2909
D/BtGatt.AdvertiseManager( 4921): advertise manager created
,D/BluetoothAdapterService( 4921): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38fe2909
,D/BluetoothMapService( 4921): Received start request. Starting profile...
D/BluetoothMapService( 4921): start()
,D/BluetoothMapEmailSettingsLoader( 4921): Found 0 applications
D/BluetoothMapEmailAppObserver( 4921): createReceiver()
,D/BluetoothMapEmailAppObserver( 4921): initObservers()
D/BluetoothMapEmailAppObserver( 4921): getEnabledAccountItems()
,D/BluetoothAdapterService( 4921): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38fe2909
D/HeadsetStateMachine( 4921): Proxy object connected
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 4921): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 4921): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 4921): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 4921): enable
,I/GKI_LINUX( 4921): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 4921): init
,I/bt-btu  ( 4921): btu_task pending for preload complete event
,I/bt_vendor( 4921): bt-vendor : init
D/bt_userial_mct( 4921): userial_init
,I/bt_hwcfg( 4921): Starting hciattach daemon
I/bt_hwcfg( 4921): try to set false
,I/bt_hwcfg( 4921): Starting hciattach daemon
,I/bt_hwcfg( 4921): try to set true
,I/libmdmdetect( 4974): ESOC framework not supported
,E/Diag_Lib( 4974):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 4974): baseband property is set to [msm]
I/libmdmdetect( 4974): ESOC framework not supported
,E/wpa_supplicant( 4974):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 4974): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4974): card_info[i].card_state: 0x0
E/wpa_supplicant( 4974): card_info[i].error_code: 0x0
E/wpa_supplicant( 4974): SIM/USIM not ready
E/wpa_supplicant( 4974): Error while reading SIM card status
D/BSUtils ( 2550): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/qcom-bluetooth( 5001): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,E/wpa_supplicant( 4974): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4974): card_info[i].card_state: 0x0
E/wpa_supplicant( 4974): card_info[i].error_code: 0x0
E/wpa_supplicant( 4974): SIM/USIM not ready
I/wpa_supplicant( 4974): eap_proxy: Card not ready
,I/BSUtils ( 2550): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2550): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1533): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/qcom-bluetooth( 5009): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/ActivityManager(  887): Killing 4675:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/qcom-bluetooth( 5010): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 5012): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5013): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 5014): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,I/art     ( 1457): Explicit concurrent mark sweep GC freed 54123(2MB) AllocSpace objects, 33(1041KB) LOS objects, 39% free, 7MB/12MB, paused 990us total 86.392ms
,E/wpa_supplicant( 4974): Line 31: unknown global field 't'.
,E/wpa_supplicant( 4974): Line 31: Invalid configuration line 't'.
,I/wpa_supplicant( 4974): rfkill: Cannot open RFKILL control device
D/TCMD    (  463): NL - Read 1004 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,E/wpa_supplicant( 4974): baseband property is set to [msm]
I/libmdmdetect( 4974): ESOC framework not supported
,E/wpa_supplicant( 4974):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_4675/cgroup.procs: No such file or directory
E/wpa_supplicant( 4974): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4974): card_info[i].card_state: 0x0
E/wpa_supplicant( 4974): card_info[i].error_code: 0x0
E/wpa_supplicant( 4974): SIM/USIM not ready
E/wpa_supplicant( 4974): Error while reading SIM card status
,E/wpa_supplicant( 4974): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4974): card_info[i].card_state: 0x0
E/wpa_supplicant( 4974): card_info[i].error_code: 0x0
E/wpa_supplicant( 4974): SIM/USIM not ready
I/wpa_supplicant( 4974): eap_proxy: Card not ready
I/wpa_supplicant( 4974): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,E/WifiStateMachine(  887): setSuspendOptimizations: 2 true
E/WifiStateMachine(  887): mSuspendOptNeedsDisabled 0
,D/AuthorizationBluetoothService( 1620): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/WifiStateMachine(  887): Supplicant connection established
,E/WifiStateMachine(  887): setWifiState: enabled
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiConfigStore(  887): Loading config and enabling all networks 
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiConfigStore(  887):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  887):  got CRC SSID "NG7005g" -> 1656539502
,D/BSUtils ( 2550): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/WifiConfigStore(  887): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  887): Setting external_sim to 1
,D/WifiStateMachine(  887): Setting OUI to DA-A1-19
I/WifiNative-HAL(  887): startHal
E/wifi    (  887): getStaticLongField sWifiHalHandle 0xa2e3e89c
D/wifi    (  887): halHandle = 0x0, mVM = 0xb87b9310, mCls = 0x201066
I/WifiNative-HAL(  887): Could not start hal
,E/WifiStateMachine(  887): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,I/BSUtils ( 2550): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 4974): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/wpa_supplicant( 4974): wlan0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 4974): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,I/ActivityManager(  887): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=5020 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,E/native  (  887): do suspend true
,D/WifiP2pService(  887): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  887): SCAN_AVAILABLE : 3
D/RttService(  887): SCAN_AVAILABLE : 3
D/WifiScanningService(  887): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  887): startHal
,D/RttService(  887): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,E/wifi    (  887): getStaticLongField sWifiHalHandle 0xa49519cc
D/wifi    (  887): halHandle = 0x0, mVM = 0xb87b9310, mCls = 0x103e
I/WifiNative-HAL(  887): Could not start hal
E/WifiScanningService(  887): could not start HAL
,D/CommandListener(  299): Setting iface cfg
D/CommandListener(  299): Trying to bring up p2p0
,D/WifiMonitor(  887): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  887): P2pEnablingState
,E/WifiStateMachine(  887): set country code US
D/WifiP2pService(  887): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2p socket connection successful
D/WifiP2pService(  887): P2pEnabledState
,D/WifiP2pService(  887): sending p2p connection changed broadcast
E/WifiStateMachine(  887): set frequency band 2
,I/wpa_supplicant( 4974): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 4974): wlan0: Failed to initiate AP scan
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,D/WifiNative-HAL(  887): p2pGetDeviceAddress
,D/WifiNative-HAL(  887): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,D/WifiP2pService(  887): DeviceAddress: 44:80:eb:7b:5a:07
,D/WifiP2pService(  887): MCC mode enabled 0
,D/WifiP2pService(  887): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  887): sending p2p persistent groups changed broadcast
D/WifiP2pService(  887): InactiveState
D/WifiP2pService(  887): InactiveState{ when=-11ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-11ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-13ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-13ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
,E/WifiStateMachine(  887): setDetailed state send new extra info0x
,D/BSUtils ( 2550): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/SharedPreferencesImpl(  887): Couldn't create directory for SharedPreferences file shared_prefs/android_preferences.xml
,E/PhoneInterfaceManager( 1533): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 5020): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Killing 4702:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/Checkin ( 2956): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2956): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/MDMCTBK (  303): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  303): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): wifi_connect_to_supplicant, current pid is = 303
,D/MDMCTBK (  303): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  303): wifi_close_sockets: Exit
E/MDMCTBK (  303): Attach monitor thread
,I/MDMCTBK (  303): createWifiMonitorThread: Started the wifi monitor thread -1191564664
,D/MDMCTBK (  303): wifi_wait_on_socket: Enter monitor thread
,I/art     (  887): Explicit concurrent mark sweep GC freed 21662(1147KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 19MB/29MB, paused 1.619ms total 125.026ms
,D/BSUtils ( 2550): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2550): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/libprocessgroup(  887): failed to open /acct/uid_10057/pid_4702/cgroup.procs: No such file or directory
,I/BSUtils ( 2550): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/Checkin ( 2956): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/global frequency( 2550): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2550): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2550): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2550): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2550): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/TCMD    (  463): NL - Read 1004 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/Checkin ( 2956): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/global frequency( 2550): BcsDSCheckin.events found events 319
,D/Checkin ( 2550): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2550): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2550): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 1457): Explicit concurrent mark sweep GC freed 4135(172KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 688us total 27.104ms
,I/art     ( 2550): Explicit concurrent mark sweep GC freed 13822(936KB) AllocSpace objects, 2(31KB) LOS objects, 39% free, 11MB/18MB, paused 925us total 55.892ms
,D/MMApiWebService( 2550): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2550): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2550): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2550): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2550): unknown error code mapping for: 0
I/global frequency( 2550): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2550): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/MDMCTBK (  303): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
,D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  303): Event received = WPS-AP-AVAILABLE 
,I/WifiNative-HAL(  887): startHal
E/wifi    (  887): getStaticLongField sWifiHalHandle 0xa2e3e8fc
D/wifi    (  887): halHandle = 0x0, mVM = 0xb87b9310, mCls = 0x15b2
I/WifiNative-HAL(  887): Could not start hal
E/WifiStateMachine(  887): [1,449,216,326,284 ms] noteScanEnd no scan source
,E/WifiStateMachine(  887): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@26ba4271 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  887): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  887):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  887): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  887): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  887): will read network variables netId=0
,E/WifiStateMachine(  887): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  887): will read network variables netId=0
,I/wpa_supplicant( 4974): wlan0: Trying to associate with SSID 'NG700'
,D/WifiMonitor(  887): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 4974): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  303): Event received = Trying to associate with
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  303): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiConfigStore(  887): setLastSelectedConfiguration -1
,E/wpa_supplicant( 4974): PNO: In assoc process
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/qcom-bluetooth( 5047): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 44:80:eb:7b:5a:05 
,I/qcom-bluetooth( 5048): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 4921): bluetooth satus is on
D/bt_userial_mct( 4921): userial_open(port:0)
,I/bt_userial_vendor( 4921): Done intiailizing UART
,I/bt_userial_vendor( 4921): Done intiailizing UART
,I/bt_userial_mct( 4921): CMD=53, EVT=53, ACL_Out=54, ACL_In=54
I/bt_vendor( 4921): Bluetooth Firmware and smd is initialized
D/bt_userial_mct( 4921): Entering userial_read_thread()
,I/bt-btu  ( 4921): btu_task received preload complete event
D/TCMD    (  463): NL - Read 312 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 192 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 68 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
,D/TCMD    (  463): NL - Read 80 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 80 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 68 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
I/wpa_supplicant( 4974): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  303): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  303): Event received = Associated with c0:ff:d4
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  303): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info"NG700"
,D/Tethering(  887): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  303): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 4974): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  303): Event received = WPA: Key negotiation com
I/wpa_supplicant( 4974): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  303): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  303):  STA Connected !!
D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
E/MDMCTBK (  303): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2462, reply_len: 4, ret: 0
D/MDMCTBK (  303): get_freq !!, resp=2462
I/MDMCTBK (  303): get_freq !!, Strip data
I/MDMCTBK (  303): get_freq !!, band = 2, freq = 2462
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/        ( 4921): BTE_InitTraceLevels -- TRC_HCI
I/MDMCTBK (  303): get_property_value, Enter
I/        ( 4921): BTE_InitTraceLevels -- TRC_L2CAP
I/MDMCTBK (  303): get_property_value, Values read from property=0,0,0,0,0,0,0,0,0,1,1,0, length=23
I/        ( 4921): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 4921): BTE_InitTraceLevels -- TRC_AVDT
I/MDMCTBK (  303): get_property_value, Exit
I/        ( 4921): BTE_InitTraceLevels -- TRC_AVRC
I/MDMCTBK (  303): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/        ( 4921): BTE_InitTraceLevels -- TRC_A2D
I/MDMCTBK (  303): set_property_value, Enter
I/        ( 4921): BTE_InitTraceLevels -- TRC_BNEP
I/MDMCTBK (  303): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/        ( 4921): BTE_InitTraceLevels -- TRC_BTM
I/        ( 4921): BTE_InitTraceLevels -- TRC_GAP
I/        ( 4921): BTE_InitTraceLevels -- TRC_PAN
I/        ( 4921): BTE_InitTraceLevels -- TRC_SDP
I/        ( 4921): BTE_InitTraceLevels -- TRC_GATT
I/        ( 4921): BTE_InitTraceLevels -- TRC_SMP
I/        ( 4921): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 4921): BTE_InitTraceLevels -- TRC_BTIF
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler, Wifi Band changed, call setWifiCutback.
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 0, data=0
I/MDMCTBK (  303): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  303): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): get_property_value, Enter
I/MDMCTBK (  303): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  303): get_property_value, Exit
I/MDMCTBK (  303): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1191538712
I/MDMCTBK (  303): return from set_get_from_wpa_supplicant
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  303): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiP2pService(  887): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/MDMCTB,K (  303): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  303): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  303): , reply_len: 3, ret: 0
E/MDMCTBK (  303): MdmCutbackHndler, resp=OK
E/MDMCTBK (  303): 
D/MDMCTBK (  303): wifi_set_tx_pwr: Exit
D/WifiP2pService(  887): P2pEnabledStateupdate channel list
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  887): Network connection established
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/bt-btm  ( 4921): BTM_SecRegister:p_cb_info->p_le_callback == 0xa6dfad85 
E/bt-btm  ( 4921): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa6dfad85 
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/bt-btif ( 4921): Calling BTA_HhEnable
E/bt-btif ( 4921): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 4921): Address is:44:80:EB:7B:5A:05
D/BluetoothAdapterProperties( 4921): Name is: XT1072
,D/BluetoothAdapterProperties( 4921): Scan Mode:20
D/BluetoothAdapterProperties( 4921): Discoverable Timeout:120
E/WifiStateMachine(  887): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
D/BluetoothAdapterProperties( 4921): Adding bonded device:7C:F9:0E:37:96:AB
D/BluetoothAdapterProperties( 4921): Adding bonded device:58:2A:F7:ED:96:BE
,E/BluetoothRemoteDevices( 4921): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:37:96:AB, value is empty for type: 10
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/BluetoothManagerService(  887): Bluetooth Adapter name changed to XT1072
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/BluetoothManagerService(  887): Stored Bluetooth name: XT1072
E/BluetoothRemoteDevices( 4921): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,E/bt_mct  ( 4921): hci lib postload completed
,D/bte_conf( 4921): Device ID record 1 : primary
D/bte_conf( 4921):   vendorId            = 000f
D/bte_conf( 4921):   vendorIdSource      = 0001
D/bte_conf( 4921):   product             = 1200
D/bte_conf( 4921):   version             = 1436
D/bte_conf( 4921):   clientExecutableURL = 
D/bte_conf( 4921):   serviceDescription  = 
D/bte_conf( 4921):   documentationURL    = 
D/bte_conf( 4921): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 4921): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 4921): ScanMode =  20
D/BluetoothAdapterProperties( 4921): State =  11
D/BluetoothAdapterProperties( 4921): Setting state to 12
I/BluetoothAdapterState( 4921): Bluetooth adapter state changed: 11-> 12
D/BluetoothPanServiceJni( 4921): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService(  887): Message: 60
D/BluetoothManagerService(  887): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  887): Broadcasting onBluetoothStateChange(true) to 5 receivers.
I/BluetoothAdapterState( 4921): Entering On State
D/BluetoothHeadset( 1533): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 4921): Scan Mode:21
D/BluetoothAdapterProperties( 4921): Discoverable Timeout:120
D/BluetoothHeadset( 1507): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1507): onBluetoothStateChange: up=true
D/BluetoothHeadset(  887): onBluetoothStateChange: up=true
D/BluetoothA2dp(  887): onBluetoothStateChange: up=true
D/BluetoothManagerService(  887): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  887): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  887): Message: 40
D/BluetoothManagerService(  887): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/ConnectivityService(  887): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  887): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  887): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  887): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine(  887): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BluetoothMapService( 4921): onReceive
D/BluetoothMapService( 4921): STATE_ON
,D/BluetoothMapMasInstance( 4921): Map Service startRfcommSocketListener
,I/Telecom ( 1507): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/CommandListener(  299): Setting iface cfg
,D/BluetoothMapMasInstance( 4921): MAS initSocket()
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,E/WifiStateMachine(  887): Start Dhcp Watchdog 1
,W/BluetoothAdapter( 4921): getBluetoothService() called with no BluetoothManagerCallback
D/HeadsetStateMachine( 4921): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 4921): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 4921): mNumber:  mType: 128
D/HeadsetStateMachine( 4921): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 4921): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothMapMasInstance( 4921): Accepting socket connection...
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/ContextImpl( 4966): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend false
,E/wpa_supplicant( 4974): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  887): Unexpected BatchedScanResults :null
E/wpa_supplicant( 4974): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  887): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@5b21ff0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@5b21ff0 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27018fee:true
,D/LocalBluetoothProfileManager( 4966): Adding local A2DP profile
,D/BluetoothManagerService(  887): Message: 30
,D/LocalBluetoothProfileManager( 4966): Adding local HEADSET profile
,D/BluetoothManagerService(  887): Message: 30
,D/AuthorizationBluetoothService( 1620): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4921): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  887): Message: 30
,D/BluetoothManagerService(  887): Message: 30
,D/LocalBluetoothProfileManager( 4966): Adding local MAP profile
,D/BluetoothMap( 4966): Create BluetoothMap proxy object
D/BluetoothManagerService(  887): Message: 30
,D/BluetoothManagerService(  887): Message: 30
,D/LocalBluetoothProfileManager( 4966): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 4966): finishStartingService: stopping service
,D/BluetoothA2dp( 4966): Proxy object connected
,D/A2dpProfile( 4966): Bluetooth service connected
,D/BluetoothHeadset( 4966): Proxy object connected
,D/HeadsetProfile( 4966): Bluetooth service connected
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4921): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothInputDevice( 4966): Proxy object connected
,D/HidProfile( 4966): Bluetooth service connected
,I/BtOppRfcommListener( 4921): Accept thread started.
D/BluetoothPan( 4966): BluetoothPAN Proxy object connected
,D/PanProfile( 4966): Bluetooth service connected
,D/BluetoothMap( 4966): Proxy object connected
,D/MapProfile( 4966): Bluetooth service connected
,D/BluetoothMap( 4966): getConnectedDevices()
,D/BluetoothPbap( 4966): Proxy object connected
D/PbapServerProfile( 4966): Bluetooth service connected
,E/DHCPCD  ( 5074): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5074): version 5.5.6 starting
E/DHCPCD  ( 5074): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 5074): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 5074): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 5074): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 5074): wlan0: rebinding lease of 192.168.1.134
D/DHCPCD  ( 5074): wlan0: sending REQUEST (xid 0x53e496ac), next in 3.44 seconds
,V/AlarmManager(  887): send {5235302, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  887): done {5235302, *walarm*:com.google.android.intent.action.SEND_IDLE} [3ms]
,I/DHCPCD  ( 5074): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/DHCPCD  ( 5074): wlan0: leased 192.168.1.134 for 86400 seconds
,D/DHCPCD  ( 5074): wlan0: adding IP address 192.168.1.134/24
D/DHCPCD  ( 5074): wlan0: adding route to 192.168.1.0/24
,D/DHCPCD  ( 5074): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5074): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5074): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/TCMD    (  463): NL - Read 60 bytes from update socket.
D/TCMD    (  463): NL - ignore NL message, type = 20
D/TCMD    (  463): Listening for incoming client connection request
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4863): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 4863): 
I/jxcore-log( 4863): my name is : motorola-XT1072_PT2491
I/jxcore-log( 4863): 
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/jxcore-log( 4863): attempting to connect to test coordinator
I/jxcore-log( 4863): 
I/jxcore-log( 4863): check test folder
I/jxcore-log( 4863): 
I/jxcore-log( 4863): found test : ./testFindPeers.js
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): found test : ./testReConnect.js
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): found test : ./testSendData.js
I/jxcore-log( 4863): 
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  887): WifiStateMachine DHCP successful
E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  887): Calling ARP set with IP = 192.168.1.134
,I/jxcore-log( 4863): Test app app.js loaded
I/jxcore-log( 4863): 
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  887): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,D/ConnectivityService(  887): Adding iface wlan0 to network 100
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/chromium( 4863): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  887): ConnectedState Enter  mScreenOn=false scanperiod=20000
,E/ConnectivityService(  887): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  887): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  887): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  887): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  887): Setting Dns servers for network 100 to [/192.168.1.1]
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  887): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  887):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  887): Setting tx/rx TCP buffers to 131072,262144,3145728,4096,221184,3145728
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
,D/CSLegacyTypeTracker(  887): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  887): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1526): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1941): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1526): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1526): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/MDMCTBK (  303): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  303): NetlinkHandler, interfaceAdded
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
E/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  303): , Wifi = 1
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 1, data=0
I/MDMCTBK (  303): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  303): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): get_property_value, Enter
I/MDMCTBK (  303): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  303): get_property_value, Exit
I/MDMCTBK (  303): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1191538648
I/MDMCTBK (  303): return from set_get_from_wpa_supplicant
I/MDMCTBK (  303): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  303): set_property_value, Enter
D/MDMCTBK (  303): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  303): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  303): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  303): , reply_len: 3, ret: 0
E/MDMCTBK (  303): MdmCutbackHndler, resp=OK
E/MDMCTBK (  303): 
D/MDMCTBK (  303): wifi_set_tx_pwr: Exit
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
I/MDMCTBK (  303): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,I/MDMCTBK (  303): send SAR ctrl over QMI
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Dec 2015 08:05:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449216328708], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449216328685]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Validated
,D/ConnectivityService(  887): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  887): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524290
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1941): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1526): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1526): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1526): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1526): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1457): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2550): now: 198806 ,futureTime: 9223372036854775807
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2550): now: 198843 ,futureTime: 9223372036854775807
D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2550): now: 198858 ,futureTime: 9223372036854775807
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5143 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Central_PollingManager( 1457): now: 198889 ,futureTime: 86471933
D/Central_PollingManager( 1457): Polling alarm set to expire at: 86471933 Current Time: 198889
,D/OtaApp  ( 2550): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  887): send {dcd399c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,D/OtaApp  ( 2550): [debug] > PollingManagerService, now: 198910 ,futureTime: 21558665
D/OtaApp  ( 2550): [debug] > Polling alarm set to expire at: 21558665 Current Time: 198914
,D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2550): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2550): createDeviceIdOrLogin update_device
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2550): Not proxy app, so login/provision not allowed
D/MMApiWebService( 2550): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2550): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2550): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2550): createDeviceIdOrLogin update_device
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2550): generating token using payload instead of using session token
,D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2550): isRequestAllowed(): already have outstanding request ... ignoring request
,D/MMApiWebService( 2550): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/ Nonce  ( 2550):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2550): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2550): createDeviceIdOrLogin update_device
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2550): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2550): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2550): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2550): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2550): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,I/MMApiWSBase( 2550): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,D/OtaApp  ( 2550): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/art     (  887): Explicit concurrent mark sweep GC freed 30077(1558KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.519ms total 143.365ms
,D/MMApiWebService( 2550): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1457): Explicit concurrent mark sweep GC freed 3548(147KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 638us total 41.913ms
,I/MusicStore( 5143): Database version: 120
,I/MMApiWSBase( 2550): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,E/GpsLocationProvider(  887): No APN found to select.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5143): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/GoogleURLConnFactory( 1620): Using platform SSLCertificateSocketFactory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5143): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5143): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,W/ResourcesManager( 5143): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5143): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5143): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 5143): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5143): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d225af5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5143): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5143): GMSCore installation verified
,I/ConfigStore( 5143): Config Database version: 1
,E/Auth.Api.Credentials( 1941): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager(  887): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=5212 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MediaRouter( 5143): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5143): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5143): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5143): type=WIFI subType= reason=null isConnected=true
,D/MMApiWSBase( 2550): doRequest(): v1/gns/list/messages resp length: 1363
,D/CCE     ( 2550): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 2550): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5239 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 5143): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5143): Using platform SSLCertificateSocketFactory
,D/Checkin ( 2550): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 2550): handleGetNotificationsResponse(): got 0; more=false
,W/ResourcesManager( 5212): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5212): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ Nonce  ( 2550):  Nonce Reponse 
D/        ( 2550): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"e4599cd1-96be-4f75-ab77-f08f1e3acfac"}
D/MMApiWSBase( 2550): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2550):  Nonce Handle Reponse 
D/MMApiProvisionService( 2550): mOutstandingReq set to false
,V/JNIHelp ( 5212): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 5212): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5212): Installed default security provider GmsCore_OpenSSL
,V/Mms     ( 5239): mnc/mcc: 
,V/Mms     ( 5239): tag: int value: recipientLimit - 20
V/Mms     ( 5239): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 5239): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 5239): tag: int value: maxSubjectLength - 80
V/Mms     ( 5239): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 5239): tag: bool value: enableGroupMms - false
,V/Mms     ( 5239):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/MMApiProvisionService( 2550):  pTime 1449056434640 sExp 172742 cTime 1449216333187 tTime 1449229176640
D/MMApiProvisionService( 2550):  No login Required 
,W/ResourcesManager( 5239): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5279 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/jxcore-log( 4863): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 4863): 
,I/art     ( 1533): Explicit concurrent mark sweep GC freed 29830(1914KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 2.625ms total 102.361ms
,I/art     (  887): Explicit concurrent mark sweep GC freed 16247(715KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.619ms total 142.379ms
,W/art     ( 5212): Suspending all threads took: 51.045ms
,W/PhenotypeConfigurator( 1620): Server returned 404
,E/YouTube MDX( 5212): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/ResourcesManager( 5212): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5212): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PhoneMonitor( 5279): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 5279): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5279): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  887): Killing 4610:android.process.acore/u0a7 (adj 15): empty #7
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5212): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/dex2oat ( 5313): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1671698742.jar --oat-fd=27 --oat-location=/data/data/com.google.android.youtube/cache/ads1671698742.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_4610/cgroup.procs: No such file or directory
,I/CheckinService( 1941): Checkin interval check for package: unspecified last checkin: 1449182542336 min interval config: 0 actual interval: 33791417
,I/CheckinService( 1941): Checking schedule, now: 1449216333762 next: 1449182572318
I/CheckinService( 1941): active receiver: enabled
,W/DataUsage( 2550): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,I/dex2oat ( 5313): dex2oat took 155.544ms (threads: 4)
,I/CheckinService( 1941): Preparing to send checkin request
,I/EventLogService( 1941): Accumulating logs since 1449215947711
,I/iu.SyncManager( 1941): SYNC; picasa accounts
,D/NetworkLogImpl( 1941): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1941): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1941): num queued entries: 0
I/iu.UploadsManager( 1941): num updated entries: 0
I/iu.SyncManager( 1941): NEXT; no task
,D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=5337 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5212): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5212): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5212): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 5212): Found 10016
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5212): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/GCM     ( 1620): GCM config loaded
,I/art     ( 1620): Explicit concurrent mark sweep GC freed 35608(1947KB) AllocSpace objects, 6(119KB) LOS objects, 39% free, 11MB/19MB, paused 3.304ms total 133.104ms
,E/DataBuffer( 1620): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1e3c99b1)
,E/DataBuffer( 1620): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@26878e96)
E/DataBuffer( 1620): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@132d9a17)
E/DataBuffer( 1620): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1427ce04)
E/DataBuffer( 1620): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@10d01fed)
,W/DataUsage( 2550): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,E/SQLiteLog( 5212): (539) recovered 2 pages from /data/data/com.google.android.youtube/databases/keyValueByteStores-journal
,I/CheckinRequestBuilder( 1941): Checkin reason type: 8 attempt count: 1
,D/WifiService(  887): New client listening to asynchronous messages
,E/ActivityThread( 1941): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5402 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  887): Killing 4372:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_4372/cgroup.procs: No such file or directory
,W/ResourcesManager( 5402): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/VacuumService( 1620): Vacuum at: now=1449216334992 tag=VacuumService
,I/ActivityManager(  887): Killing 4966:com.android.settings/1000 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_1000/pid_4966/cgroup.procs: No such file or directory
,I/Babel_SMS( 5402): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5402): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5402): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5402): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5402): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5402): MmsConfig.loadFromResources
,E/Babel_SMS( 5402): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5402): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 5402): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5402): startup - clean
,I/Babel   ( 5402): deleted: false for 0
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5445 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 5402): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5402): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5402): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5402): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5402): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5402): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5402): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5402): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5402): onServiceConnected
,W/Babel   ( 5402): Attempted to change video mute state without an active call.
,I/Babel   ( 5402): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  887): Killing 5020:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10008/pid_5020/cgroup.procs: No such file or directory
,D/UdcCache:FPQuery( 1941): Bootstrapping UDC settings cache for all accounts
,D/GetConfigurationSnapshotOperation( 1620): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5445): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5445): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=293, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312818, SEQNUM=4433, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-21935, POWER_SUPPLY_CHARGE_COUNTER=-746, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5445): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5445): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,I/GAv4    ( 5445): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5445):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5445):   adb logcat -s GAv4
,W/GAv4    ( 5445): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,W/GAv4    ( 5445): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5445): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/PhenotypeFlagCommitter( 1620): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1620): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1620): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/ActivityManager(  887): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5503 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/WebViewFactory( 5445): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/art     ( 4745): Attempt to remove local handle scope entry from IRT, ignoring
,W/ResourcesManager( 5503): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5503): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/LibraryLoader( 5445): Time to load native libraries: 2 ms (timestamps 3759-3761)
I/LibraryLoader( 5445): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5445): Binding Chromium to main looper Looper (main, tid 1) {32123f82}
I/LibraryLoader( 5445): Expected native library version number "",actual native library version number ""
I/chromium( 5445): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/MultiDex( 5503): VM with version 2.1.0 has multidex support
I/MultiDex( 5503): install
I/MultiDex( 5503): VM has multidex support, MultiDex support library is disabled.
,I/BrowserStartupController( 5445): Initializing chromium process, singleProcess=true
W/art     ( 5445): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5445): ApplicationContext is null in ApplicationStatus
,W/chromium( 5445): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5445): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5445): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5445): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5445): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5445): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5445): Local Branch: 
I/Adreno-EGL( 5445): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5445): Local Patches: NONE
I/Adreno-EGL( 5445): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 5445): Requires BLUETOOTH permission
,I/MDMCTBK (  303): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  303): NetlinkHandler, interfaceAdded
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
E/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  303): , Wifi = 1
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  303): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  303): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): get_property_value, Enter
I/MDMCTBK (  303): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  303): get_property_value, Exit
I/MDMCTBK (  303): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1191538648
I/MDMCTBK (  303): return from set_get_from_wpa_supplicant
I/MDMCTBK (  303): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  303): set_property_value, Enter
D/MDMCTBK (  303): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
E/MDMCTBK (  303): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  303): , reply_len: 3, ret: 0
I/MDMCTBK (  303): set_property_value, Exit
E/MDMCTBK (  303): MdmCutbackHndler, resp=OK
E/MDMCTBK (  303): 
E/MDMCTBK (  303): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  303): wifi_set_tx_pwr: Exit
,I/art     (  887): Explicit concurrent mark sweep GC freed 23077(1065KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.384ms total 135.105ms
,I/NSApplication( 5445): Starting up...
,V/JNIHelp ( 5503): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5554 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 5143:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/ActivityThread( 5503): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5503): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6c2bdd2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5503): Installed default security provider GmsCore_OpenSSL
,I/art     (  325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 355us total 22.816ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 19.782ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 21.481ms
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_5143/cgroup.procs: No such file or directory
,I/art     ( 5503): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 5503): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,D/WVCdm   (  308): Instantiating CDM.
,I/WVCdm   (  308): CdmEngine::OpenSession
I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
D/NativeLibraryUtils( 5503): Install completed successfully. count=13 extracted=0
,W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  308): Service_Initialize: starts!
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  308): App is not loaded in QSEE
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
D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d12000
,E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d12000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb55a1960
D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb834d1b0, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb82198a8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb8364790, idLength=0xb54a1730
,D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  308): PrepareKeyRequest: nonce=1288256872
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8318ee8
D/DrmWidevineDash(  308): message_length=1591, signature=0xb82940a8, signature_length=3041531668
,I/GoogleURLConnFactory( 5503): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 5239:com.android.mms/u0a23 (adj 15): empty #7
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  308): CdmEngine::CloseSession
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  308): L3 Terminate.
,D/DrmWidevineDash(  308): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  308): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  308): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  308): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  308): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_5239/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2550): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 2550): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,V/AlarmManager(  887): done {dcd399c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [5757ms]
,E/SQLiteLog( 2550): (284) automatic index on registration(APP_ID)
,D/WaitableIntentService( 2550): ServiceHandler.handleMessage: mWaitCount=1
,I/PushService( 2550): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2550): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2550): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2550): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  887): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2550): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2550): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2550): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2550): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:182 vsyncs) (2:1126)
,D/OtaApp  ( 2550): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2550): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2550): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2550): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1406): onFinishInput()
,W/IInputConnectionWrapper( 4863): showStatusIcon on inactive InputConnection
,I/SundryService( 2550): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 2550): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
,D/SundryService( 2550): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 2550): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2550): unbindWebServices(): un-registering our AIDL callback...
,I/LaunchCheckinHandler(  887): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,183
,D/WearableService( 1710): callingUid 10016, callindPid: 1710
,E/MDM     ( 1710): [165] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GetCommittedConfigurationOperation( 1620): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/LocationInitializer( 1941): Restart initialization of location
,D/GCM     ( 1620): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1620): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1941): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/GCoreFlp( 1710): No location to return for getLastLocation()
W/FusedLocationProvider( 1620): location=null
,I/ActivityManager(  887): Killing 5279:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/dex2oat ( 5606): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=33 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_5279/cgroup.procs: No such file or directory
,I/dex2oat ( 5606): dex2oat took 63.928ms (threads: 4)
,I/Adreno-EGL( 5503): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5503): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5503): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5503): Local Branch: 
I/Adreno-EGL( 5503): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5503): Local Patches: NONE
I/Adreno-EGL( 5503): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/GetCommittedConfigurationOperation( 1620): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1620): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/Adreno-EGL( 5503): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5503): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5503): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5503): Local Branch: 
I/Adreno-EGL( 5503): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5503): Local Patches: NONE
I/Adreno-EGL( 5503): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/Uploader( 1620):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1620): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/Adreno-EGL( 5503): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5503): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5503): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5503): Local Branch: 
I/Adreno-EGL( 5503): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5503): Local Patches: NONE
I/Adreno-EGL( 5503): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 5503): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5503): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5503): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5503): Local Branch: 
I/Adreno-EGL( 5503): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5503): Local Patches: NONE
I/Adreno-EGL( 5503): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/GetCommittedConfigurationOperation( 1620): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/WVCdm   (  308): CdmEngine::OpenSession
I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  308): Service_Initialize: starts!
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,E/QSEECOMAPI: (  308): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  308): App is not loaded in QSEE
,D/GetCommittedConfigurationOperation( 1620): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d12000
E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d12000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb54a1960
,D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb834cf88, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb82198a8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb83647d0, idLength=0xb55a1730
,D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  308): PrepareKeyRequest: nonce=1695228505
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8318ee8
D/DrmWidevineDash(  308): message_length=1626, signature=0xb82940a8, signature_length=3042580244
,D/GetCommittedConfigurationOperation( 1620): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1620): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1620): no corresponding serverToken: com.google.android.gms.playlog.uploader
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
,D/GetCommittedConfigurationOperation( 1620): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1620): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/CheckinRequestBuilder( 1941): Classify the device as Phone.
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:33000 mC
,I/CheckinTask( 1941): Sending checkin request (9476 bytes)
,I/CheckinRequestBuilder( 1941): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1941): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 1941): Explicit concurrent mark sweep GC freed 31601(2MB) AllocSpace objects, 25(400KB) LOS objects, 39% free, 14MB/23MB, paused 1.645ms total 134.413ms
,D/TaskPersister(  887): removeObsoleteFile: deleting file=2_task.xml
,I/art     ( 1620): Explicit concurrent mark sweep GC freed 86610(4MB) AllocSpace objects, 24(440KB) LOS objects, 40% free, 12MB/21MB, paused 1.077ms total 85.394ms
,I/CheckinRequestBuilder( 1941): Classify the device as Phone.
,I/CheckinTask( 1941): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1941): Checking schedule, now: 1449216340703 next: 1449817477698
I/CheckinService( 1941): active receiver: disabled
,D/CheckinService( 1941): Recording last checkin time for package unspecified as 1449216340721
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5649 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 5649): Register our PhoneStateListener
,V/SetupWizard( 5649): Connected to Gservices successfully
,I/ActivityManager(  887): Killing 5212:com.google.android.youtube/u0a101 (adj 15): empty #7
,D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/libprocessgroup(  887): failed to open /acct/uid_10101/pid_5212/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1620): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/ActivityManager(  887): Killing 5554:com.android.chrome/u0a52 (adj 13): empty #7
,I/ActivityManager(  887): Killing 5445:com.google.android.apps.magazines/u0a81 (adj 15): empty #8
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_5554/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_5445/cgroup.procs: No such file or directory
,I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1533): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5694 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,V/GmsNetworkLocationProvi( 1710): DISABLE
,D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  887): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  887): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/GCoreNlp( 1710): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1544): Deferring update until onResume
,V/BackupManagerService(  887): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2cefed71
,I/art     (  887): Explicit concurrent mark sweep GC freed 27823(1298KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.634ms total 116.241ms
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5728 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5747 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/ResourcesManager( 5402): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5402): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5402): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 5402): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5402): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5770 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 5337:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 5747): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_5337/cgroup.procs: No such file or directory
,W/asset   ( 5770): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5770): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 5770): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5770): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5788 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 4745:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_4745/cgroup.procs: No such file or directory
,D/Finsky  ( 5788): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5788): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5788): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5788): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 5788): Skipping gmscore version check
,D/Finsky  ( 5788): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5788): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5788): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/Launcher( 1544): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3154b new=com.google.android.velvet.VelvetApplication@3154b
,I/UpdateIcingCorporaServi( 5694): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1941): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 5788): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5842 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 1941): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1941): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 5842): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5694): UpdateCorporaTask done [took 161 ms] updated apps [took 161 ms] 
,I/ActivityManager(  887): Killing 5649:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_5649/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 5503:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_5503/cgroup.procs: No such file or directory
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:33000 mC
,I/ActivityManager(  887): Killing 5728:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_5728/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 5402:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_5402/cgroup.procs: No such file or directory
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,W/SQLiteConnectionPool( 1941): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  887): send {3a8fe1a7, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  887): send {250dd487, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): done {3a8fe1a7, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [4ms]
,V/AlarmManager(  887): done {250dd487, *alarm*:android.intent.action.TIME_TICK} [46ms]
,D/AlarmManagerService(  887): Setting time of day to sec=1449216360
,W/AlarmManagerService(  887): Unable to set rtc to 1449216360: Invalid argument
,I/ActivityManager(  887): Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=5891 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 5891): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=5911 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 5770:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10027/pid_5770/cgroup.procs: No such file or directory
,E/SQLiteLog( 5911): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  887): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5934 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5934): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AnalyticsLogBase( 5911): PlayLogger.onLoggerConnected
,I/ActivityManager(  887): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5952 uid=10096 gids={50096, 9997} abi=armeabi-v7a
I/ActivityManager(  887): Killing 5788:com.android.vending/u0a32 (adj 15): empty #7
,I/art     (  325): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 22.217ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.720ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 20.359ms
,I/ActivityManager(  887): Killing 5694:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #8
,I/CalendarProvider2( 5934): Created com.android.providers.calendar.CalendarAlarmManager@15509ed3(com.android.providers.calendar.CalendarProvider2@dea1a10)
,W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_5788/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_5694/cgroup.procs: No such file or directory
,I/System.out( 5952): TimeService: Loaded Library 
D/TimeService( 5952): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449216361053
D/        ( 5952): TimeServiceNative: User Time to be set is 1449216361053
D/QC-time-services( 5952): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5952): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5952): Lib:time_genoff_operation: pargs->ts_val = 1449216361053
D/QC-time-services( 5952): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  331): Daemon: Connection accepted:time_genoff
D/QC-time-services(  331): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449216361053
D/QC-time-services(  331): Daemon:genoff_opr: Base = 2, val = 1449216361053, operation = 0
D/QC-time-services(  331): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/4/115 8:4:49
D/QC-time-services(  331): Daemon:Value read from RTC seconds = 1449216289000
D/QC-time-services(  331): Daemon:new time 1449216361053 
D/QC-time-services(  331): Daemon: delta 72053 genoff 72053 
D/QC-time-services(  331): Daemon:genoff_persistent_update: Writing genoff = 72053 to memory
D/QC-time-services(  331): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  331): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  331): Updating the TOD offset
D/QC-time-services(  331): Daemon:genoff_persistent_update: Writing genoff = 72053 to memory
,D/QC-time-services(  331): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  331): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  331): Daemon:Update to modem bit set
D/QC-time-services(  331): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  331): Daemon: Base = 2, Value being sent to MODEM = 18446743757744823669
,E/QC-time-services( 5952): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  331): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  331): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1941): Checkin interval check for package: unspecified last checkin: 1449216340721 min interval config: 0 actual interval: 20380
,I/ActivityManager(  887): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=5976 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 5976): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5976):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5976):   adb logcat -s GAv4
,W/GAv4    ( 5976): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5976): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5976): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  887): Killing 5747:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_5747/cgroup.procs: No such file or directory
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/CalendarProvider2( 5934): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5934): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,V/AlarmManager(  887): send {1efb04bc, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  887): done {1efb04bc, *walarm*:android.content.syncmanager.SYNC_ALARM} [5ms]
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,W/ContextImpl( 5911): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 5911): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/ActivityManager(  887): Killing 5842:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_5842/cgroup.procs: No such file or directory
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/ClearcutLoggerApiImpl( 1710): disconnect managed GoogleApiClient
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310370, SEQNUM=4466, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-878, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,V/AlarmManager(  887): send {10d1b0a8, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  887): done {10d1b0a8, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [8ms]
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1406): run()
I/Keyboard.Facilitator( 1406): flushDynamicLanguageModels()
,I/ConfigService( 1620): onCreate
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/ConfigService( 1620): onDestroy
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310863, SEQNUM=4470, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10917, POWER_SUPPLY_CHARGE_COUNTER=-1000, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect called
I/jxcore-log( 4863): 
I/jxcore-log( 4863): Coordinator is now connected to the server!
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4863): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): DBG, CoordinatorConnector command called
I/jxcore-log( 4863): 
I/jxcore-log( 4863): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":20,"addressList":[{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"58:3F:54:73:64
I/jxcore-log( 4863): Start now : testSendData.js
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 20
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): check server
I/jxcore-log( 4863): 
I/jxcore-log( 4863): serverPort is 43965
I/jxcore-log( 4863): 
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 4863): Stoping All
,I/        ( 4863): Stopping services
I/        ( 4863): Stop Bluetooth
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 4863): Start-My BT: 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 4863):  mInstanceString : {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2491","ra":"44:80:EB:7B:5A:05"}
,I/        ( 4863): All stuff available and enabled
I/        ( 4863): Stoping All
I/        ( 4863): Stopping services
I/        ( 4863): Stop Bluetooth
I/        ( 4863): Starting All
I/        ( 4863): Stopping services
I/        ( 4863): Starting services address: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2491","ra":"44:80:EB:7B:5A:05"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@2ad4002c
I/        ( 4863): Stopping services
I/        ( 4863): Starting services address: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2491","ra":"44:80:EB:7B:5A:05"}
,I/        ( 4863): Add local service :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2491","ra":"44:80:EB:7B:5A:05"}, length : 81
,D/WifiP2pService(  887): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@50a16b58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@50a16b58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service
D/WifiP2pService(  887): add a new client
,I/        ( 4863): peerDiscoveryTimer timeout value:9311
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4863): Stop Bluetooth
I/        ( 4863): StartBluetooth listener
,I/        ( 4863): StartBluetooth listener
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  887): discovery change broadcast true
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 4863): StartBroadcasting started ok
I/jxcore-log( 4863): 
I/jxcore-log( 4863): do fake peer & start
I/jxcore-log( 4863): 
I/jxcore-log( 4863): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:09:27.899Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:09:27.900Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:09:27.902Z SendDataConnector.js: do connect now
I/jxcore-log( 4863): 
,I/BTListenerThread( 4863): starting to listen
I/BTListenerThread( 4863): waiting to accept incoming Connection
,I/        ( 4863): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/BTConnectToThread( 4863): Starting to connect
W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 4863): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/jxcore-log( 4863): 2015-12-04T08:09:27.919Z SendDataTCPServer.js: TCP/IP server is bound to port: 43965
I/jxcore-log( 4863): 
D/BTIF_SOCK( 4921): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 4863): We already were running, thus doing nothing
I/        ( 4863): Added local service
I/        ( 4863): Cleared service requests
I/        ( 4863): Stopped peer discovery
I/        ( 4863): Started peer discovery
I/        ( 4863): Discovery state changed to Started.
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 0 c0
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 4921): process_service_search_attr_rsp
,E/bt-btif ( 4921): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4921): invalid rfc slot id: 5
,I/BTConnectToThread( 4863): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4863): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 4863): 2015-12-04T08:09:29.053Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:09:29.055Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:09:29.058Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4863): 
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-28
I/wpa_supplicant( 4974): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Note3-1
D/WifiP2pService(  887):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note3-1
D/WifiP2pService(  887):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-4ms what=147477 obj=Device: Android_50a5
D/WifiP2pService(  887):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-4ms what=147477 obj=Device: Android_50a5
D/WifiP2pService(  887):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4863): Found 2 peers.
I/SS      ( 4863): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 4863): Peer(2): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=7 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=7 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 4863): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4863): Added service request
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 4974): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  303): Event received = P2P: Reject scan trigger 
,I/        ( 4863): Started service discovery
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f726dc rs_disc_pending=0
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ea:50:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP ea:50:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT5544, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT5544, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 4863): 2015-12-04T08:09:34.058Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:09:34.059Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 0 
,I/jxcore-log( 4863): 2015-12-04T08:09:39.061Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:09:39.061Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:09:39.062Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:09:39.062Z SendDataConnector.js: do connect now
I/jxcore-log( 4863): 
,I/        ( 4863): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 4863): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 4863): Starting to connect
W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4921): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
I/wpa_supplicant( 4974): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 level=-48
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: XT1039_8c05
D/WifiP2pService(  887):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 33
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: XT1039_8c05
D/WifiP2pService(  887):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 33
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP f4:f1:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP f4:f1:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT8025, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT8025, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 fa
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 fa
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 4921): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 4921): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,E/bt-btif ( 4921): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4921): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 4921): Entering PendingCommandState State
,D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a2693d8:true
,D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@314eaa16:true
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,I/BluetoothBondStateMachine( 4921): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 4921): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/ActivityManager(  887): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=6061 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/BluetoothBondStateMachine( 4921): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
D/BluetoothAdapterService( 4921): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38fe2909
,D/BluetoothMetrics( 4921): btclass5a020c
,D/Checkin ( 4921): publish the event [tag = MOT_BT event name = PAIRING]
,I/BluetoothBondStateMachine( 4921): StableState(): Entering Off State
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:1
W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4863): Starting to Handshake
W/ResourcesManager( 6061): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
I/BTConnectToThread( 4863): MESSAGE_WRITE 81 bytes.
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/BTConnectToThread( 4863): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 4863): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 4863): HandshakeOk : samsung-SM-G900F_PT2753
I/HS      ( 4863): Hand Shake finished outgoing for : samsung-SM-G900F_PT2753
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 4863): Starting the connected thread incoming : false, samsung-SM-G900F_PT2753
,I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 4863): mHTTPPort  set to : 41069
,I/BtConnectorHelper( 4863): Request socket is using : 41069
I/BtToRequestSocket( 4863): Now accepting connections
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 7e:f9:
D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT1688, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT1688, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/art     (  887): Explicit concurrent mark sweep GC freed 19540(1089KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.405ms total 121.798ms
D/BluetoothManagerService(  887): Message: 20
,D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1548916d:true
,I/ActivityManager(  887): Killing 5952:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10096/pid_5952/cgroup.procs: No such file or directory
,I/BtConnectorHelper( 4863): Calling ConnectionStatusUpdate with port :41069
,I/jxcore-log( 4863): 2015-12-04T08:09:43.909Z SendDataConnector.js: CLIENT connected to 41069, error: null
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:09:43.910Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4863): 
,I/BtToRequestSocket( 4863): incoming data from: /127.0.0.1, port: 41069
,I/BtToRequestSocket( 4863): Set local streams
I/BtToRequestSocket( 4863): rin ended ---------------------------;
,I/jxcore-log( 4863): 2015-12-04T08:09:43.921Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:09:44.634Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:09:44.786Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:09:44.819Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:09:44.900Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:09:44.942Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:09:44.981Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:09:45.058Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:09:45.168Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:09:45.275Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 4863): 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 1 
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f726dc rs_disc_pending=0
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f726dc rs_disc_pending=0
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4921): dm_pm_timer expires
W/bt-btif ( 4921): dm_pm_timer expires 0
W/bt-btif ( 4921): proc dm_pm_timer expires
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-40
I/wpa_supplicant( 4974): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Android_50a5
D/WifiP2pService(  887):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_50a5
D/WifiP2pService(  887):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2828, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2828, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032 vendor_elems=1 level=-45
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  887):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService(  887):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService(  887):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  887):  WFD CtrlPort: 7236
D/WifiP2pService(  887):  WFD MaxThroughput: 50
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService(  887):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  887):  WFD CtrlPort: 7236
D/WifiP2pService(  887):  WFD MaxThroughput: 50
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f726dc rs_disc_pending=0
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 4863): 2015-12-04T08:09:55.275Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:09:55.276Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:09:55.282Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:09:55.282Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:09:55.289Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 4863): 
,I/BtToSocketBase( 4863): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 4863): Disconnect outgoing peer: samsung-SM-G900F_PT2753
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
I/BtToSocketBase( 4863): Close LocalOutputStream
I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
,I/BtToRequestSocket( 4863): Close server socket
,W/bt-btif ( 4921): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 fa
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 fa
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 2 
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=6107 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ee9d769:true
,I/BTConnectionReceiver( 6107): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6145 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/BluetoothClassifier( 6107): Bluetooth Device Name: S5-1
,I/ActivityManager(  887): Killing 5934:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10005/pid_5934/cgroup.procs: No such file or directory
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4863): 2015-12-04T08:10:00.288Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:10:00.288Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139265 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4863): Cleared service requests
I/        ( 4863): Started peer discovery
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService(  887):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  887):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4863): Found 10 peers.
I/SS      ( 4863): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4863): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4863): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 4863): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4863): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 4863): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 4863): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 4863): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4863): Peer(9): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 4863): Peer(10): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 4863): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4863): Added service request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 36
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 36
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 ee
,I/jxcore-log( 4863): 2015-12-04T08:10:05.290Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:10:05.290Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:10:05.291Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:10:05.291Z SendDataConnector.js: do connect now
I/jxcore-log( 4863): 
,I/        ( 4863): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/        ( 4863): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 4863): Starting to connect
W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4921): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 3 
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4863): Started service discovery
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 c0
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 4 c0
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP f4:f1:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP f4:f1:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT8025, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT8025, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ea:50:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP ea:50:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT5544, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT5544, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 36:fc:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 36:fc:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5431, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5431, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 3a:94:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 3a:94:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT5954, peerAddress: 38:94:96:B5:06:DC
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT5954, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT5363, peerAddress: 34:FC:EF:11:B1:66
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT5363, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT4577, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT4577, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 7e
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 7e
,I/ActivityManager(  887): Waited long enough for: ServiceRecord{17154e33 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 4 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139307 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4863): Cleared service requests
I/        ( 4863): Started peer discovery
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-41
I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032 vendor_elems=1 level=-45
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 c0
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 5 c0
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService(  887):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  887):  WFD CtrlPort: 7236
D/WifiP2pService(  887):  WFD MaxThroughput: 50
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService(  887):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  887):  WFD CtrlPort: 7236
D/WifiP2pService(  887):  WFD MaxThroughput: 50
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4863): Found 11 peers.
I/SS      ( 4863): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 4863): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4863): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4863): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 4863): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4863): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 4863): Peer(7): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 4863): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 4863): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4863): Peer(10): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 4863): Peer(11): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=139301 arg2=19 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139301 arg2=19 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 4863): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4863): Added service request
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139310 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4863): Started service discovery
,I/wpa_supplicant( 4974): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
,D/MDMCTBK (  303): Event received = P2P: Reject scan trigger 
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService(  887):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService(  887):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT5146, peerAddress: 34:FC:EF:11:AE:67
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT5146, WifiDirectName: , WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 92
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 5 
,W/bt-sdp  ( 4921): SDP - Rcvd conn cnf with error: 0x8  CID 0x43
E/bt-btif ( 4921): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4921): invalid rfc slot id: 7
,I/BTConnectToThread( 4863): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4863): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4863): 2015-12-04T08:10:26.591Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:10:26.594Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:10:26.594Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4863): 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4863): 2015-12-04T08:10:31.595Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:10:31.595Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4863): Cleared service requests
I/        ( 4863): Started peer discovery
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-2ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4863): Found 13 peers.
I/SS      ( 4863): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 4863): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 4863): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 4863): Peer(4): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4863): Peer(5): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4863): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 4863): Peer(7): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4863): Peer(8): G3s-1 a2:39:f7:70:12:80
I/SS      ( 4863): Peer(9): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 4863): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 4863): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4863): Peer(12): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 4863): Peer(13): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 4863): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4863): Added service request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 52
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 52
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139310 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 4974): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  303): Event received = P2P: Reject scan trigger 
,I/        ( 4863): Started service discovery
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 36:fc:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 36:fc:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5431, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5431, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 3a:94:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 3a:94:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT5954, peerAddress: 38:94:96:B5:06:DC
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT5954, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/jxcore-log( 4863): 2015-12-04T08:10:36.599Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:10:36.599Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:10:36.599Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:10:36.600Z SendDataConnector.js: do connect now
I/jxcore-log( 4863): 
,I/        ( 4863): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/        ( 4863): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 4863): Starting to connect
W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4921): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT1688, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT1688, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 6107): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6107): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 4921): process_service_search_attr_rsp
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:1
,W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 4863): Starting to Handshake
I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
I/BTConnectToThread( 4863): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/BTConnectToThread( 4863): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 4863): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 4863): HandshakeOk : samsung-SM-G900F_PT2753
I/HS      ( 4863): Hand Shake finished outgoing for : samsung-SM-G900F_PT2753
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4863): Starting the connected thread incoming : false, samsung-SM-G900F_PT2753
I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 4863): mHTTPPort  set to : 36923
I/BtConnectorHelper( 4863): Request socket is using : 36923
I/BtToRequestSocket( 4863): Now accepting connections
,I/BtConnectorHelper( 4863): Calling ConnectionStatusUpdate with port :36923
I/jxcore-log( 4863): 2015-12-04T08:10:40.940Z SendDataConnector.js: CLIENT connected to 36923, error: null
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:10:40.940Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4863): 
,I/BtToRequestSocket( 4863): incoming data from: /127.0.0.1, port: 36923
I/BtToRequestSocket( 4863): Set local streams
I/BtToRequestSocket( 4863): rin ended ---------------------------;
,I/jxcore-log( 4863): 2015-12-04T08:10:40.957Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 4863): 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2753, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2753, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f726dc rs_disc_pending=0
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,E/DataBuffer( 1620): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@336991c8)
,E/DataBuffer( 1620): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@170e3261)
,E/DataBuffer( 1620): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3c6b3186)
,E/DataBuffer( 1620): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@365f1a47)
,E/DataBuffer( 1620): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3a6a0274)
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT807, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT807, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 7e
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 7e
,W/bt-btif ( 4921): dm_pm_timer expires
W/bt-btif ( 4921): dm_pm_timer expires 0
W/bt-btif ( 4921): proc dm_pm_timer expires
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4863): 2015-12-04T08:10:51.027Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:10:51.028Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:10:51.028Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:10:51.029Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:10:51.029Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 4863): 
,I/BtToSocketBase( 4863): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 4863): Disconnect outgoing peer: samsung-SM-G900F_PT2753
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
I/BtToSocketBase( 4863): Close LocalOutputStream
I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
I/BtToRequestSocket( 4863): Close server socket
,W/bt-btif ( 4921): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4863): Cleared service requests
I/        ( 4863): Started peer discovery
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-41
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 c0
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 7 c0
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService(  887):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService(  887):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4863): Found 14 peers.
I/SS      ( 4863): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 4863): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 4863): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4863): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 4863): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4863): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 4863): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 4863): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 4863): Peer(9): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 4863): Peer(10): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4863): Peer(11): G3s-1 a2:39:f7:70:12:80
I/SS      ( 4863): Peer(12): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 4863): Peer(13): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4863): Peer(14): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 4863): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4863): Added service request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 0a
,I/wpa_supplicant( 4974): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 4974): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 4974): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 4974): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  303): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  303): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1
D/MDMCTBK (  303): Event received = P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5
D/MDMCTBK (  303): Event received = P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5
,D/WifiP2pService(  887): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 7 
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 6107): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6107): Bluetooth Device Name: S5-1
,I/jxcore-log( 4863): 2015-12-04T08:10:56.028Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:10:56.029Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 c0
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 8 c0
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4863): Started service discovery
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-39
I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032 vendor_elems=1 level=-45
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-4ms what=147477 obj=Device: Android_63cc
D/WifiP2pService(  887):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  887):  WFD CtrlPort: 7236
D/WifiP2pService(  887):  WFD MaxThroughput: 50
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-4ms what=147477 obj=Device: Android_63cc
D/WifiP2pService(  887):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  887):  WFD CtrlPort: 7236
D/WifiP2pService(  887):  WFD MaxThroughput: 50
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT5146, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT5146, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6390, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6390, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2753, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2753, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT807, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT807, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 36:fc:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 36:fc:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5431, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5431, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT5363, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT5363, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT4577, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT4577, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT1688, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT1688, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 3a:94:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 3a:94:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT5954, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT5954, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2368","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2368","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2368","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2368","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2368, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2368, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4863): 2015-12-04T08:11:01.030Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:01.030Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:01.031Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:01.035Z SendDataConnector.js: do connect now
I/jxcore-log( 4863): 
,I/        ( 4863): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/        ( 4863): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 4863): Starting to connect
W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4921): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 6107): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6107): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 4921): process_service_search_attr_rsp
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:1
W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4863): Starting to Handshake
,I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4863): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/BTConnectToThread( 4863): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 4863): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 4863): HandshakeOk : samsung-SM-G900F_PT2753
I/HS      ( 4863): Hand Shake finished outgoing for : samsung-SM-G900F_PT2753
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4863): Starting the connected thread incoming : false, samsung-SM-G900F_PT2753
I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 4863): mHTTPPort  set to : 47053
I/BtConnectorHelper( 4863): Request socket is using : 47053
I/BtToRequestSocket( 4863): Now accepting connections
,I/BtConnectorHelper( 4863): Calling ConnectionStatusUpdate with port :47053
I/jxcore-log( 4863): 2015-12-04T08:11:03.019Z SendDataConnector.js: CLIENT connected to 47053, error: null
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:11:03.019Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4863): 
,I/BtToRequestSocket( 4863): incoming data from: /127.0.0.1, port: 47053
I/BtToRequestSocket( 4863): Set local streams
I/BtToRequestSocket( 4863): rin ended ---------------------------;
,I/jxcore-log( 4863): 2015-12-04T08:11:03.032Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 4863): 
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 8 
,W/bt-btif ( 4921): dm_pm_timer expires
,W/bt-btif ( 4921): dm_pm_timer expires 0
W/bt-btif ( 4921): proc dm_pm_timer expires
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139307 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4863): Cleared service requests
I/        ( 4863): Started peer discovery
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 9 c0
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 9 c0
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 a2
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 a2
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService(  887):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService(  887):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4863): Found 11 peers.
I/SS      ( 4863): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 4863): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 4863): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4863): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 4863): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 4863): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4863): Peer(7): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 4863): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 4863): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 4863): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4863): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=36 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=36 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 4863): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4863): Added service request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 0a
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-30
I/wpa_supplicant( 4974): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-42
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
,D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=-3ms what=147477 obj=Device: Note3-1
D/WifiP2pService(  887):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-3ms what=147477 obj=Device: Note3-1
D/WifiP2pService(  887):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 ee
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139310 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4863): Started service discovery
,I/jxcore-log( 4863): 2015-12-04T08:11:13.091Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:11:13.092Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:11:13.092Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:13.102Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:13.102Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:11:13.103Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
,I/BtConnectorHelper( 4863): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 4863): Close LocalOutputStream
I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
I/BtToRequestSocket( 4863): Close server socket
I/jxcore-log( 4863): 2015-12-04T08:11:13.120Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 4863): 
I/jxcore-log( 4863): ---- round done--------
I/jxcore-log( 4863): 
I/jxcore-log( 4863): ---- gotta redo : 7C:F9:0E:34:8A:A0, try count now: 1
I/jxcore-log( 4863): 
I/jxcore-log( 4863): do fake peer & start
I/jxcore-log( 4863): 
I/jxcore-log( 4863): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:11:13.122Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:11:13.122Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:11:13.122Z SendDataConnector.js: do connect now
I/jxcore-log( 4863): 
,I/        ( 4863): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 4863): Connecting to null, at B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 2015-12-04T08:11:13.129Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 4863): 
,I/BTConnectToThread( 4863): Starting to connect
W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4921): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:34:8A:A0 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-41
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-2ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  887):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  887):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT4577, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT4577, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 36:fc:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 36:fc:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5431, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5431, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,W/bt-btif ( 4921): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f726dc rs_disc_pending=1
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ea
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 ea
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ea:50:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP ea:50:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT5544, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT5544, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2828, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2828, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 9 
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 9 
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f726dc rs_disc_pending=1
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 4921): process_service_search_attr_rsp
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f7289c rs_disc_pending=1
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 3a:94:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 3a:94:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT5954, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT5954, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/BluetoothBondStateMachine( 4921): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
E/bt-btif ( 4921): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4921): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 4921): Entering PendingCommandState State
,I/ActivityManager(  887): Killing 5976:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10055/pid_5976/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 4921): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 4921): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 4921): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 4921): StableState(): Entering Off State
,D/BluetoothMetrics( 4921): btclass5a020c
,D/Checkin ( 4921): publish the event [tag = MOT_BT event name = PAIRING]
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
,D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT5363, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT5363, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 6107): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6107): Bluetooth Device Name: S5-1
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2753, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2753, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 4921): invalid rfc slot id: 10
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectToThread( 4863): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/BTConnectionReceiver( 6107): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6107): Bluetooth Device Name: HTC Desire 820
,I/CONNEC  ( 4863): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 4863): 2015-12-04T08:11:22.435Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:11:22.436Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:11:22.436Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4863): 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT1688, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT1688, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 0a
,I/jxcore-log( 4863): 2015-12-04T08:11:27.436Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:27.436Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2368","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2368","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2368","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2368","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2368, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2368, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4863): 2015-12-04T08:11:32.438Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:32.441Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:32.443Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:32.443Z SendDataConnector.js: do connect now
I/jxcore-log( 4863): 
,I/        ( 4863): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 4863): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 4863): Starting to connect
W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4921): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/ActivityManager(  887): Waited long enough for: ServiceRecord{388c0aa1 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 10 c
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 10 c
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139307 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=139265 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139265 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4863): Cleared service requests
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4863): Started peer discovery
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 10
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 10
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 11 c
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 11 c
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 f4
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 f4
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [b4:ce:f6:ab:a4:6a]: 7, f, 610c
,I/BTConnectionReceiver( 6107): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6107): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 4921): process_service_search_attr_rsp
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:1
W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/BTConnectToThread( 4863): Starting to Handshake
,I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4863): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/BTConnectToThread( 4863): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 4863): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 4863): HandshakeOk : HTC-HTC Desire 820_PT3559
I/HS      ( 4863): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT3559
,I/BtConnectorHelper( 4863): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT3559
I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 4863): mHTTPPort  set to : 51009
I/BtConnectorHelper( 4863): Request socket is using : 51009
I/BtToRequestSocket( 4863): Now accepting connections
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72a5c rs_disc_pending=0
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 4863): Calling ConnectionStatusUpdate with port :51009
,I/jxcore-log( 4863): 2015-12-04T08:11:49.144Z SendDataConnector.js: CLIENT connected to 51009, error: null
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:11:49.145Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4863): 
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:255
W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4863): we got incoming connection
I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
I/BTListenerThread( 4863): waiting to accept incoming Connection
,I/BtToRequestSocket( 4863): incoming data from: /127.0.0.1, port: 51009
I/BtToRequestSocket( 4863): Set local streams
,I/BtToRequestSocket( 4863): rin ended ---------------------------;
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/jxcore-log( 4863): 2015-12-04T08:11:49.175Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 4863): 
,I/BTListenerThread( 4863): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 4863): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4863): MESSAGE_WRITE 81 bytes.
I/HS      ( 4863): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT3559
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
,I/BluetoothBondStateMachine( 4921): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 4921): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4921): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 4921): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 4921): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 4921): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 4921): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 4921): StableState(): Entering Off State
,D/BluetoothMetrics( 4921): btclass5a020c
,D/Checkin ( 4921): publish the event [tag = MOT_BT event name = PAIRING]
I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:255
W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4863): we got incoming connection
I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
I/BTListenerThread( 4863): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/BtConnectorHelper( 4863): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT3559
,I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BTConnectedThread
I/BtConnectorHelper( 4863): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4863): --DoOneRunRound started
,I/BtToRequestSocket( 4863): LocalHost address: localhost/127.0.0.1, port: 43965
,I/BtToRequestSocket( 4863): --DoOneRunRound ended
,I/jxcore-log( 4863): 2015-12-04T08:11:49.710Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4863): 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4863): 2015-12-04T08:11:49.858Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:49.865Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:49.971Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:49.976Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:49.984Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:49.991Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:49.997Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 4863): 
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72a5c rs_disc_pending=0
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4863): 2015-12-04T08:11:50.034Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:50.145Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 4863): 
,I/BTListenerThread( 4863): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 4863): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT476","ra":"08:EC:A9:50:75:41"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4863): MESSAGE_WRITE 81 bytes.
,I/HS      ( 4863): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT476
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4863): Starting the connected thread incoming : true, samsung-SM-A300FU_PT476
I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BTConnectedThread
I/BtConnectorHelper( 4863): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4863): --DoOneRunRound started
,I/BtToRequestSocket( 4863): LocalHost address: localhost/127.0.0.1, port: 43965
,I/jxcore-log( 4863): 2015-12-04T08:11:50.224Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4863): 
,I/BtToRequestSocket( 4863): --DoOneRunRound ended
,I/jxcore-log( 4863): 2015-12-04T08:11:50.242Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:50.372Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:50.488Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:50.538Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:50.599Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 4863): 
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 4863): 2015-12-04T08:11:50.716Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:50.755Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:50.759Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:50.816Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:50.840Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:50.905Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 4863): 
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: G3-1
D/WifiP2pService(  887):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3-1
D/WifiP2pService(  887):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4863): Found 12 peers.
I/SS      ( 4863): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 4863): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 4863): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4863): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4863): Peer(5): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 4863): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 4863): Peer(7): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4863): Peer(8): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 4863): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 4863): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 4863): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4863): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=42 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=42 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 4863): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4863): Added service request
,I/jxcore-log( 4863): 2015-12-04T08:11:51.044Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.227Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.233Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.250Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.285Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.288Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.294Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.300Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.304Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.309Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.317Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.346Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.354Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.358Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.367Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.378Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.383Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.389Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.395Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.402Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.423Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.434Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.446Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.462Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.468Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.474Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.479Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.489Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.496Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.527Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.534Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.564Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.600Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.607Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.613Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.621Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.631Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.664Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.671Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.704Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.713Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 4863): 
I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.822Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.838Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.852Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.861Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.872Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.912Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.934Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.945Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 4863): 
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139310 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 4974): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  303): Event received = P2P: Reject scan trigger 
,I/        ( 4863): Started service discovery
,I/jxcore-log( 4863): 2015-12-04T08:11:51.974Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:51.984Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.027Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 4863): 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/jxcore-log( 4863): 2015-12-04T08:11:52.130Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.174Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.181Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.215Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.318Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.327Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.365Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.494Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.500Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.523Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.602Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.608Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.614Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.621Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.659Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.694Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.702Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.734Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.813Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.819Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:11:52.823Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 4863): 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 4974): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/wpa_supplicant( 4974): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 4974): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
,D/MDMCTBK (  303): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=3a:94:96
D/MDMCTBK (  303): Event received = P2P-DEVICE-LOST p2p_dev_addr=3a:94:96
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  303): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 11
,D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 11
,W/bt-btif ( 4921): dm_pm_timer expires
,W/bt-btif ( 4921): dm_pm_timer expires 1
W/bt-btif ( 4921): proc dm_pm_timer expires
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP f4:f1:
,D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP f4:f1:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT8025, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT8025, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 ee
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6390, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6390, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT807, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT807, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT4577, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT4577, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f7289c rs_disc_pending=0
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ea:50:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP ea:50:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT5544, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT5544, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 4863): 2015-12-04T08:12:01.044Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:01.045Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:01.045Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:01.045Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:01.046Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 4863): 
,I/BtToSocketBase( 4863): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 4863): Disconnect outgoing peer: HTC-HTC Desire 820_PT3559
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
,I/BtToSocketBase( 4863): Close LocalOutputStream
I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
I/BtToRequestSocket( 4863): Close server socket
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f7289c rs_disc_pending=1
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4921): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f7289c rs_disc_pending=0
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72a5c rs_disc_pending=1
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4921): invalid rfc slot id: 4
,I/BtToSocketBase( 4863): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4863): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT3559
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
I/BtToSocketBase( 4863): Close LocalOutputStream
I/BtToSocketBase( 4863): Close localHostSocket
,I/BtToSocketBase( 4863): Close bt in
I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 4863): 2015-12-04T08:12:02.384Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4863): 
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f7289c rs_disc_pending=1
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4921): invalid rfc slot id: 12
,I/BtToSocketBase( 4863): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4863): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT476
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
I/BtToSocketBase( 4863): Close LocalOutputStream
,I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4863): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT476
I/BtToSocketBase( 4863): Close bt in
I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
,I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
,W/bt-rfcomm( 4921): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 4921): RFCOMM_DisconnectInd LCID:0x4e
,I/jxcore-log( 4863): 2015-12-04T08:12:02.801Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4863): 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2753, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2753, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72c1c rs_disc_pending=0
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4863): 2015-12-04T08:12:06.045Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:06.046Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 6107): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6107): Bluetooth Device Name: A3-1
,I/BTConnectionReceiver( 6107): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6107): Bluetooth Device Name: HTC Desire 820
,I/BluetoothBondStateMachine( 4921): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
,E/bt-btif ( 4921): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4921): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 4921): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 4921): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 4921): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 4921): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 4921): StableState(): Entering Off State
,D/BluetoothMetrics( 4921): btclass5a020c
,D/Checkin ( 4921): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:255
,W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4863): we got incoming connection
,I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
,I/BTListenerThread( 4863): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/BTListenerThread( 4863): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 4863): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4863): MESSAGE_WRITE 81 bytes.
I/HS      ( 4863): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT4577
,I/BtConnectorHelper( 4863): Starting the connected thread incoming : true, samsung-SM-G800F_PT4577
,I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BTConnectedThread
I/BtConnectorHelper( 4863): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 4863): --DoOneRunRound started
,I/BtToRequestSocket( 4863): LocalHost address: localhost/127.0.0.1, port: 43965
I/BtToRequestSocket( 4863): --DoOneRunRound ended
,I/jxcore-log( 4863): 2015-12-04T08:12:07.764Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.634Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.639Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.645Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.675Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.679Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.683Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.689Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.743Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.749Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.756Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.762Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.794Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.809Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.815Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.846Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.855Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.907Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:08.964Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.001Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.006Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.010Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.014Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.044Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.111Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.144Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.185Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.261Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.309Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.345Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.352Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.514Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.666Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.798Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 4863): 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4863): 2015-12-04T08:12:09.835Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:09.910Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:11.049Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:11.049Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:11.050Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:11.050Z SendDataConnector.js: do connect now
I/jxcore-log( 4863): 
,I/        ( 4863): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 4863): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 4863): Starting to connect
W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4921): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139307 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139265 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4863): Cleared service requests
,I/        ( 4863): Started peer discovery
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 12 c
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 12 c
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 12
,D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 12
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 13 c
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 13 c
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4863): Found 9 peers.
I/SS      ( 4863): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 4863): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4863): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 4863): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4863): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 4863): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 4863): Peer(7): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 4863): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4863): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=47 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=47 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 4863): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4863): Added service request
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139310 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 4974): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4863): Started service discovery
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,I/wpa_supplicant( 4974): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-53
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  887):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -53 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -53 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP f4:f1:
,D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP f4:f1:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT8025, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT8025, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT807, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT807, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 36:fc:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 36:fc:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5431, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5431, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT4577, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT4577, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  887): Waited long enough for: ServiceRecord{3f934c87 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2753, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2753, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:ff:f0 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}, typeCordovap2p._tcp.local.:
I/        ( 4863): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT5363, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT5363, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 0a
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72c1c rs_disc_pending=1
E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): invalid rfc slot id: 13
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 4921): onReceive
,I/BtToSocketBase( 4863): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4863): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT4577
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
I/BtToSocketBase( 4863): Close LocalOutputStream
I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BTConnectionReceiver( 6107): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6107): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 4863): 2015-12-04T08:12:23.057Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4863): 
,I/wpa_supplicant( 4974): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 4974): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 4974): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 4974): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/wpa_supplicant( 4974): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  303): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  303): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=82:01:84
D/MDMCTBK (  303): Event received = P2P-DEVICE-LOST p2p_dev_addr=82:01:84
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  303): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b
D/MDMCTBK (  303): Event received = P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b
,D/WifiP2pService(  887): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 13
,D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 13
,D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 68 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 4974): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  303):  STA Disconnected !!
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): get_property_value, Enter
I/MDMCTBK (  303): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  303): get_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  303): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  303): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  463): NL - Read 68 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
E/MDMCTBK (  303): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  303): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 4974): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
I/wpa_supplicant( 4974): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  303): Event received = CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  303): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  887): InitialState.processMessage what=4
,E/WifiStateMachine(  887): NETWORK_DISCONNECTION_EVENT in connected state BSSID=c0:ff:d4:d3:aa:48 RSSI=-127 freq=-1 was debouncing=false reason=0 ajst=0
,E/WifiStateMachine(  887): Missed CTRL-EVENT-DISCONNECTED, disconnect
E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  887): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
D/Tethering(  887):  0
,D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 4974): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  299): Clearing all IP addresses on wlan0
,D/TCMD    (  463): NL - Read 60 bytes from update socket.
,D/TCMD    (  463): NL - ignore NL message, type = 21
D/TCMD    (  463): Listening for incoming client connection request
,V/NativeCrypto( 1620): Read error: ssl=0xb8b31258: I/O error during system call, Connection timed out
,V/NativeCrypto( 1620): SSL shutdown failed: ssl=0xb8b31258: I/O error during system call, Broken pipe
,D/ConnectivityService(  887): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
,I/jxcore-log( 4863): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 4863): 
I/jxcore-log( 4863): The Coordinator has disconnected!
I/jxcore-log( 4863): 
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WifiMetrics(  887): connected time updated 418566
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6326 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ConnectivityService(  887): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  887): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Disconnected - quitting
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  887): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524292
I/ModemStatsDSDetect( 1526): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityManager.CallbackHandler( 1941): CM callback handler got msg 524292
E/ConnectivityService(  887): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/ModemStatsDSDetect( 1526): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1526): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1526): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1526): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1526): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): WifiStateMachine: Leaving Connected state
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  887): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/UdcCache:FPQuery( 1941): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6326): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6326): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6326): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6326): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6326): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6326): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6326): MmsConfig.loadFromResources
,E/Babel_SMS( 6326): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6326): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,V/AlarmManager(  887): send {250dd487, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {1df8de38, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,W/Settings( 6326): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/AlarmManager(  887): done {250dd487, *alarm*:android.intent.action.TIME_TICK} [35ms]
,I/Babel_Crash( 6326): startup - clean
,I/Babel   ( 6326): deleted: false for 0
,V/AlarmManager(  887): done {1df8de38, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [119ms]
,W/VideoCapabilities( 6326): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6326): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6326): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6326): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6326): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6326): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6326): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6326): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6326): onServiceConnected
W/Babel   ( 6326): Attempted to change video mute state without an active call.
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
I/jxcore-log( 4863): Error type "connect_error" when connecting to the test server
I/jxcore-log( 4863): 
,D/WifiService(  887): setWifiEnabled: false pid=4863, uid=10350
E/WifiService(  887): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings( 1457): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,E/wpa_supplicant( 4974): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  887): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 4974): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiScanningService(  887): SCAN_AVAILABLE : 1
,D/WifiScanningService(  887): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  887): SCAN_AVAILABLE : 1
D/WifiService(  887): setWifiEnabled: true pid=4863, uid=10350
E/WifiService(  887): Invoking mWifiStateMachine.setWifiEnabled
,D/RttService(  887): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  887): [1,449,216,747,924 ms] noteScanEnd no scan source
W/Settings( 1457): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiP2pService(  887): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): discovery change broadcast false
,D/WifiP2pService(  887): P2pDisablingState
D/WifiP2pService(  887): P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): p2p socket connection lost
D/WifiP2pService(  887): P2pDisabledState
,E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - enter - invokeEnterMethods
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 4974): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  299): Clearing all IP addresses on wlan0
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiController(  887): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 475ms
,W/Settings( 1457): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1457): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,E/WifiStateMachine(  887): stopping supplicant
,E/WifiStateMachine(  887): setWifiState: disabling
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/jxcore-log( 4863): Wifi toggled for connection repairment
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139265 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139265 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 4974): eap_proxy Deinitialzed
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 0
,I/        ( 4863): Discovery state changed to Stopped.
I/WB      ( 4863): Wifi is DISABLED !!
I/        ( 4863): Stoping All
I/        ( 4863): Stopping services
I/        ( 4863): Stopping services
,D/WifiP2pService(  887): P2pDisabledState{ when=-1ms what=139298 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139298 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4863): Stop Bluetooth
D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139307 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139307 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139268 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139268 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4863): Stop Bluetooth
I/BTListenerThread( 4863): Stopped
,I/BTConnectToThread( 4863): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 4921): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:15, channel:-1
,I/        ( 4863): Starting peer discovery failed, error code 2
I/        ( 4863): Clearing local services failed, error code 2
I/        ( 4863): Clearing service requests failed, error code 2
I/        ( 4863): Stopping peer discovery failed, error code 2
I/CONNEC  ( 4863): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 4863): 2015-12-04T08:12:27.987Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:27.987Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:27.987Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4863): 
,D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 4974): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  303): Event received = CTRL-EVENT-TERMINATING 
,D/MDMCTBK (  303):  Wpa Supplicant Exiting !!
D/MDMCTBK (  303): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  303): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  303): wifi_close_sockets: Exit
,E/WifiStateMachine(  887): Supplicant connection lost
,D/Checkin ( 2956): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,E/QC-QMI  (  422): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  422): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  422): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
E/QC-QMI  (  422): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
E/QC-QMI  (  422): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,E/WifiStateMachine(  887): setWifiState: disabled
W/Settings( 6326): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 1710): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Checkin ( 2956): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiController(  887): DEFERRED_TOGGLE handled
,E/WifiStateMachine(  887): setting operational mode to 1
,D/Checkin ( 2956): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  463): NL - Read 444 bytes from update socket.
D/TCMD    (  463): NL - ignore NL message, type = 17
D/TCMD    (  463): Listening for incoming client connection request
,D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/TCMD    (  463): NL - Read 444 bytes from update socket.
D/TCMD    (  463): NL - ignore NL message, type = 17
D/TCMD    (  463): Listening for incoming client connection request
,D/Checkin ( 2956): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  303): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  303): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
,D/TCMD    (  463): NL - Read 1008 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/Tethering(  887): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering(  887): InitialState.processMessage what=4
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
,D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  463): NL - Read 1008 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/QsoftapCmd(  299): Got softap fwreload command we are passing on
,D/SoftapController(  299): Softap fwReload - Ok
D/CommandListener(  299): Setting iface cfg
D/CommandListener(  299): Trying to bring down wlan0
,D/CommandListener(  299): Clearing all IP addresses on wlan0
,I/wpa_supplicant( 6391): Successfully initialized wpa_supplicant
E/wpa_supplicant( 6391): Line 13: unknown global field 'N'.
E/wpa_supplicant( 6391): Line 13: Invalid configuration line 'N'.
,I/wpa_supplicant( 6391): rfkill: Cannot open RFKILL control device
,D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/libmdmdetect( 6391): ESOC framework not supported
,E/Diag_Lib( 6391):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 6391): baseband property is set to [msm]
,I/libmdmdetect( 6391): ESOC framework not supported
,E/wpa_supplicant( 6391):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 6391): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 6391): card_info[i].card_state: 0x0
E/wpa_supplicant( 6391): card_info[i].error_code: 0x0
,E/wpa_supplicant( 6391): SIM/USIM not ready
E/wpa_supplicant( 6391): Error while reading SIM card status
,E/WifiStateMachine(  887): setWifiState: enabling
E/WifiStateMachine(  887): Supplicant start successful
,D/WifiMonitor(  887): startMonitoring(wlan0) with mConnected = false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/wpa_supplicant( 6391): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 6391): card_info[i].card_state: 0x0
E/wpa_supplicant( 6391): card_info[i].error_code: 0x0
E/wpa_supplicant( 6391): SIM/USIM not ready
I/wpa_supplicant( 6391): eap_proxy: Card not ready
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,E/wpa_supplicant( 6391): Line 31: unknown global field 'i'.
,E/wpa_supplicant( 6391): Line 31: Invalid configuration line 'i'.
I/wpa_supplicant( 6391): rfkill: Cannot open RFKILL control device
,D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,E/wpa_supplicant( 6391): baseband property is set to [msm]
,I/libmdmdetect( 6391): ESOC framework not supported
,E/wpa_supplicant( 6391):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 6391): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 6391): card_info[i].card_state: 0x0
E/wpa_supplicant( 6391): card_info[i].error_code: 0x0
E/wpa_supplicant( 6391): SIM/USIM not ready
E/wpa_supplicant( 6391): Error while reading SIM card status
,E/wpa_supplicant( 6391): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 6391): card_info[i].card_state: 0x0
E/wpa_supplicant( 6391): card_info[i].error_code: 0x0
E/wpa_supplicant( 6391): SIM/USIM not ready
I/wpa_supplicant( 6391): eap_proxy: Card not ready
,E/WifiStateMachine(  887): setSuspendOptimizations: 2 true
E/WifiStateMachine(  887): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  887): Supplicant connection established
E/WifiStateMachine(  887): setWifiState: enabled
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiConfigStore(  887): Loading config and enabling all networks 
,E/WifiConfigStore(  887):  got CRC SSID "NG700" -> 1501448721
I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
I/jxcore-log( 4863): Error type "connect_error" when connecting to the test server
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,E/WifiConfigStore(  887):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  887): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 6326): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  887): Setting external_sim to 1
D/WifiStateMachine(  887): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  887): startHal
E/wifi    (  887): getStaticLongField sWifiHalHandle 0xa2e3e89c
D/wifi    (  887): halHandle = 0x0, mVM = 0xb87b9310, mCls = 0x2014c2
I/WifiNative-HAL(  887): Could not start hal
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/wpa_supplicant( 6391): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/native  (  887): do suspend true
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  887): SCAN_AVAILABLE : 3
,D/RttService(  887): SCAN_AVAILABLE : 3
D/WifiScanningService(  887): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  887): startHal
E/wifi    (  887): getStaticLongField sWifiHalHandle 0xa49519cc
D/wifi    (  887): halHandle = 0x0, mVM = 0xb87b9310, mCls = 0x2014a6
I/WifiNative-HAL(  887): Could not start hal
E/WifiScanningService(  887): could not start HAL
D/RttService(  887): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  299): Setting iface cfg
,D/CommandListener(  299): Trying to bring up p2p0
,D/WifiMonitor(  887): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  887): P2pEnablingState
D/WifiP2pService(  887): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2p socket connection successful
D/WifiP2pService(  887): P2pEnabledState
I/wpa_supplicant( 6391): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,D/WifiP2pService(  887): sending p2p connection changed broadcast
I/WB      ( 4863): Wifi is now enabled !
I/        ( 4863): Stoping All
I/        ( 4863): Stopping services
I/        ( 4863): Stop Bluetooth
,I/        ( 4863): Starting All
I/        ( 4863): Stopping services
I/        ( 4863): Starting services address: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2491","ra":"44:80:EB:7B:5A:05"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@2ad4002c
I/        ( 4863): Stopping services
I/        ( 4863): Starting services address: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2491","ra":"44:80:EB:7B:5A:05"}
I/        ( 4863): Add local service :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2491","ra":"44:80:EB:7B:5A:05"}, length : 81
I/        ( 4863): peerDiscoveryTimer timeout value:6267
,I/        ( 4863): Stop Bluetooth
I/        ( 4863): StartBluetooth listener
I/        ( 4863): StartBluetooth listener
,D/WifiNative-HAL(  887): p2pGetDeviceAddress
D/WifiNative-HAL(  887): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
D/WifiP2pService(  887): DeviceAddress: 44:80:eb:7b:5a:07
,D/WifiP2pService(  887): MCC mode enabled 0
D/WifiP2pService(  887): mP2pAutoConnectSupport = 0
D/WifiP2pService(  887): sending p2p persistent groups changed broadcast
,E/WifiStateMachine(  887): set country code US
E/WifiStateMachine(  887): set frequency band 2
D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/wpa_supplicant( 6391): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiP2pService(  887): InactiveState
,D/WifiP2pService(  887): InactiveState{ when=-5ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-5ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-5ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-5ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=139292 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@50a16b58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139292 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@50a16b58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service
D/WifiP2pService(  887): add a new client
D/WifiP2pService(  887): InactiveState{ when=-2ms what=139307 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=139307 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=-2ms what=139268 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info0x
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  887): InactiveState{ when=-10ms what=139265 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-10ms what=139265 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
,D/WifiP2pService(  887): discovery change broadcast true
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/        ( 4863): Discovery state changed to Stopped.
I/        ( 4863): Added local service
,I/        ( 4863): Cleared service requests
I/        ( 4863): Stopped peer discovery
I/        ( 4863): Started peer discovery
D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 4863): Discovery state changed to Started.
I/BTListenerThread( 4863): starting to listen
I/BTListenerThread( 4863): waiting to accept incoming Connection
I/        ( 4863): Started peer discovery
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/MDMCTBK (  303): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  303): MdmCutbackHndler,wifi, new_state =1
,I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): wifi_connect_to_supplicant, current pid is = 303
D/MDMCTBK (  303): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  303): wifi_close_sockets: Exit
E/MDMCTBK (  303): Attach monitor thread
I/MDMCTBK (  303): createWifiMonitorThread: Started the wifi monitor thread -1191564664
D/MDMCTBK (  303): wifi_wait_on_socket: Enter monitor thread
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Central_PollingManager( 1457): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2550): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6430 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/Central_PollingManager( 1457): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/Central_PollingManager( 1457): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2550): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2550): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2550): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2550): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2550): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2550): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2550): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2550): [debug] > CusSM.onRadioDown
,D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/MusicStore( 6430): Database version: 120
,I/art     (  887): Explicit concurrent mark sweep GC freed 64185(3MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.515ms total 125.892ms
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6430): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6430): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6430): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6430): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6430): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6430): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 6430): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6430): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d225af5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6430): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6430): GMSCore installation verified
,I/ConfigStore( 6430): Config Database version: 1
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledStateupdate channel list
,I/MediaRouter( 6430): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6430): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6459 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6430): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6430): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 5911:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10049/pid_5911/cgroup.procs: No such file or directory
,V/Mms     ( 6459): mnc/mcc: 
V/Mms     ( 6459): tag: int value: recipientLimit - 20
V/Mms     ( 6459): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6459): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6459): tag: int value: maxSubjectLength - 80
V/Mms     ( 6459): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 6459): tag: bool value: enableGroupMms - false
V/Mms     ( 6459):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6485 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6145:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,D/PhoneMonitor( 6485): Register our PhoneStateListener
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_6145/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6485): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6485): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 1941): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1941): num queued entries: 0
I/iu.UploadsManager( 1941): num updated entries: 0
,D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.SyncManager( 1941): NEXT; no task
,I/ActivityManager(  887): Killing 6061:com.android.settings/1000 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_1000/pid_6061/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6504 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6522 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 6326): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  887): Killing 6107:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_6107/cgroup.procs: No such file or directory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6522): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6522): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6522): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6522): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6522):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6522):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6522): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6522): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6522): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6522): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6522): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6522): Time to load native libraries: 1 ms (timestamps 9531-9532)
,I/LibraryLoader( 6522): Expected native library version number "",actual native library version number ""
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): Error type "connect_error" when connecting to the test server
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,V/WebViewChromiumFactoryProvider( 6522): Binding Chromium to main looper Looper (main, tid 1) {1f781864}
I/LibraryLoader( 6522): Expected native library version number "",actual native library version number ""
,I/chromium( 6522): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6522): Initializing chromium process, singleProcess=true
,W/art     ( 6522): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6522): ApplicationContext is null in ApplicationStatus
,W/chromium( 6522): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6522): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6522): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6522): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6522): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6522): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6522): Local Branch: 
I/Adreno-EGL( 6522): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6522): Local Patches: NONE
I/Adreno-EGL( 6522): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6522): Requires BLUETOOTH permission
,I/NSApplication( 6522): Starting up...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6588 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 6430:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/art     (  325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 23.216ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 21.481ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.053ms
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_6430/cgroup.procs: No such file or directory
,D/WifiP2pService(  887): InactiveState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6610 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6459:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_6459/cgroup.procs: No such file or directory
,I/jxcore-log( 4863): 2015-12-04T08:12:32.987Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:32.988Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
,W/ResourcesManager( 6610): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6633 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6656 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 6504:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 6633): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  887): Killing 6485:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_6504/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_6485/cgroup.procs: No such file or directory
,I/MusicStore( 6656): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6656): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6656): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6656): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6656): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6656): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6656): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 6656): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6656): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d225af5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6656): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6656): GMSCore installation verified
,I/ConfigStore( 6656): Config Database version: 1
,I/MediaRouter( 6656): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6656): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6699 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6656): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     (  887): Explicit concurrent mark sweep GC freed 13495(715KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.527ms total 119.147ms
,I/GoogleURLConnFactory( 6656): Using platform SSLCertificateSocketFactory
,V/Mms     ( 6699): mnc/mcc: 
,V/Mms     ( 6699): tag: int value: recipientLimit - 20
V/Mms     ( 6699): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6699): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6699): tag: int value: maxSubjectLength - 80
,I/ActivityManager(  887): Killing 6326:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 6699): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6699): tag: bool value: enableGroupMms - false
V/Mms     ( 6699):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_6326/cgroup.procs: No such file or directory
,W/ResourcesManager( 6699): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6725 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6522:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 6725): Register our PhoneStateListener
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_6522/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6725): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6725): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  887): Killing 6588:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_6588/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6744 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 6391): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/WifiNative-HAL(  887): startHal
E/wifi    (  887): getStaticLongField sWifiHalHandle 0xa2e3e8fc
D/wifi    (  887): halHandle = 0x0, mVM = 0xb87b9310, mCls = 0x201a6a
I/WifiNative-HAL(  887): Could not start hal
E/WifiStateMachine(  887): [1,449,216,754,523 ms] noteScanEnd no scan source
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6761 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6610:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_6610/cgroup.procs: No such file or directory
,W/ResourcesManager( 6761): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6761): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6761): MmsConfig.loadMmsSettings
I/Babel_SMS( 6761): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6761): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6761): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6761): MmsConfig.loadFromResources
,E/Babel_SMS( 6761): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6761): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6761): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6761): startup - clean
,I/Babel   ( 6761): deleted: false for 0
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6788 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6761): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6761): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6761): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6761): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6761): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6761): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6761): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6761): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6761): onServiceConnected
,W/Babel   ( 6761): Attempted to change video mute state without an active call.
,I/Babel   ( 6761): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  887): Killing 6633:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_6633/cgroup.procs: No such file or directory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6788): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6788): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6788):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6788):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6788): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6788): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 6788): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6788): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6788): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6788): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6788): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6788): Time to load native libraries: 1 ms (timestamps 2702-2703)
,I/LibraryLoader( 6788): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6788): Binding Chromium to main looper Looper (main, tid 1) {1f781864}
,I/LibraryLoader( 6788): Expected native library version number "",actual native library version number ""
I/chromium( 6788): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6788): Initializing chromium process, singleProcess=true
,W/art     ( 6788): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6788): ApplicationContext is null in ApplicationStatus
,W/chromium( 6788): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6788): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6788): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6788): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6788): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6788): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6788): Local Branch: 
I/Adreno-EGL( 6788): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6788): Local Patches: NONE
I/Adreno-EGL( 6788): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6788): Requires BLUETOOTH permission
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/NSApplication( 6788): Starting up...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6862 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6656:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_6656/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6885 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6699:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_6699/cgroup.procs: No such file or directory
,W/ResourcesManager( 6885): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/wpa_supplicant( 6391): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 6391): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
I/wpa_supplicant( 6391): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6909 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2
D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=-5ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-5ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4863): Found 2 peers.
I/SS      ( 4863): Peer(1): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 4863): Peer(2): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=60 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=60 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 4863): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4863): Added service request
,I/art     (  325): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 29.011ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.929ms
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 3a
D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2437 3a
I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 329us total 20.315ms
,I/ActivityManager(  887): Killing 6744:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 6909): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  887): Killing 6725:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2550): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_6744/cgroup.procs: No such file or directory
I/wpa_supplicant( 6391): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_6725/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2550): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2550): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2550): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2550): onServiceConnected()
D/GetNotificationsWS( 2550): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2550): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6941 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 6391): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 6391): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  887): Killing 6761:com.google.android.talk/u0a70 (adj 15): empty #7
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_6761/cgroup.procs: No such file or directory
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311980, SEQNUM=4592, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12920, POWER_SUPPLY_CHARGE_COUNTER=-1621, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139310 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 6391): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
I/        ( 4863): Started service discovery
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): Error type "connect_error" when connecting to the test server
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 6391): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_2dc2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:ff:f0
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 7e
,D/MDMCTBK (  303): Event received = P2P-SERV-DISC-REQ 2412 7e
,I/jxcore-log( 4863): 2015-12-04T08:12:38.002Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:38.002Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:38.002Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:38.002Z SendDataConnector.js: do connect now
I/jxcore-log( 4863): 
,I/        ( 4863): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 4863): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 4863): Starting to connect
W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4921): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btif ( 4921): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:2, scn:-107089736
,W/bt-btif ( 4921): invalid rfc slot id: 17
,I/BTConnectToThread( 4863): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4863): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4863): 2015-12-04T08:12:38.032Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:38.032Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:38.032Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4863): 
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  303): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  303): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  303): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  303): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  303): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
,I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  303): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
,E/MDMCTBK (  303): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): Error type "connect_error" when connecting to the test server
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4863): 2015-12-04T08:12:43.050Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:43.050Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
,W/bt-sdp  ( 4921): SDP - Rcvd conn cnf with error: 0x8  CID 0x43
E/bt-btif ( 4921): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 4921): invalid rfc slot id: 15
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=6982 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BluetoothManagerService(  887): Message: 20
,D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10a0707c:true
,I/BTConnectionReceiver( 6982): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:255
W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 4863): we got incoming connection
I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
,I/BTListenerThread( 4863): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/BTListenerThread( 4863): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 4863): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4863): MESSAGE_WRITE 81 bytes.
,I/HS      ( 4863): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT4577
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 4863): Starting the connected thread incoming : true, samsung-SM-G800F_PT4577
I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BTConnectedThread
I/BtConnectorHelper( 4863): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 4863): --DoOneRunRound started
,I/BtToRequestSocket( 4863): LocalHost address: localhost/127.0.0.1, port: 43965
,I/jxcore-log( 4863): 2015-12-04T08:12:44.154Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4863): 
,I/BtToRequestSocket( 4863): --DoOneRunRound ended
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7023 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/BluetoothClassifier( 6982): Bluetooth Device Name: S5mini-1
,I/ActivityManager(  887): Killing 1941:com.google.android.gms/u0a16 (adj 15): empty #7
,D/ConnectivityService(  887): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@33f3c967)
D/WifiService(  887): Client connection lost with reason: 4
D/ConnectivityService(  887): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  887): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager(  887): Killing 6788:com.google.android.apps.magazines/u0a81 (adj 15): empty #8
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_6788/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_1941/cgroup.procs: No such file or directory
,I/jxcore-log( 4863): 2015-12-04T08:12:44.564Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:44.613Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:44.620Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:44.624Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:44.628Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:44.658Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 4863): 
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): Error type "connect_error" when connecting to the test server
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4863): 2015-12-04T08:12:48.066Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:48.066Z SendDataConnector.js: Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:48.066Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:48.067Z SendDataConnector.js: do connect now
I/jxcore-log( 4863): 
,I/        ( 4863): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/BTConnectToThread( 4863): Starting to connect
,W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4921): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 4863): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/MDMCTBK (  303): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  303): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  303): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  303): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  303): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  303): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  303): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
E/MDMCTBK (  303): MdmCutbackHndler,Airplane Mode Enabled !! =1
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72c1c rs_disc_pending=1
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 6982): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6982): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 4921): process_service_search_attr_rsp
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:1
,W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4863): Starting to Handshake
,I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4863): MESSAGE_WRITE 81 bytes.
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:255
W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4863): we got incoming connection
I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
I/BTListenerThread( 4863): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/BTConnectToThread( 4863): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 4863): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 4863): HandshakeOk : HTC-HTC Desire 820_PT3559
I/HS      ( 4863): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT3559
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4863): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT3559
I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 4863): mHTTPPort  set to : 34211
,I/BtConnectorHelper( 4863): Request socket is using : 34211
I/BtToRequestSocket( 4863): Now accepting connections
,I/BTListenerThread( 4863): got MESSAGE_READ 84 bytes.
,I/BTListenerThread( 4863): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4863): MESSAGE_WRITE 81 bytes.
I/HS      ( 4863): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT3559
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4863): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT3559
I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BTConnectedThread
I/BtConnectorHelper( 4863): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4863): --DoOneRunRound started
,I/BtToRequestSocket( 4863): LocalHost address: localhost/127.0.0.1, port: 43965
,I/jxcore-log( 4863): 2015-12-04T08:12:49.570Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4863): 
,I/BtToRequestSocket( 4863): --DoOneRunRound ended
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/BtConnectorHelper( 4863): Calling ConnectionStatusUpdate with port :34211
,I/jxcore-log( 4863): 2015-12-04T08:12:49.855Z SendDataConnector.js: CLIENT connected to 34211, error: null
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:49.855Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4863): 
,I/BtToRequestSocket( 4863): incoming data from: /127.0.0.1, port: 34211
I/BtToRequestSocket( 4863): Set local streams
I/BtToRequestSocket( 4863): rin ended ---------------------------;
,I/jxcore-log( 4863): 2015-12-04T08:12:49.872Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:50.182Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4863): 
,I/MDMCTBK (  303): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  303): NetlinkHandler, interfaceAdded
,I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
E/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  303): , Wifi = 0
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  303): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully,
I/MDMCTBK (  303): set_property_value, Exit
E/MDMCTBK (  303): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/jxcore-log( 4863): 2015-12-04T08:12:50.292Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:50.295Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4863): 
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f7289c rs_disc_pending=0
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4863): 2015-12-04T08:12:50.787Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:50.792Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:50.884Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 4863): 
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): Error type "connect_error" when connecting to the test server
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f7289c rs_disc_pending=0
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4921): invalid rfc slot id: 16
,I/BtToSocketBase( 4863): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4863): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT4577
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4863): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT4577
I/BtToSocketBase( 4863): Close LocalOutputStream
,I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
I/BtToSocketBase( 4863): Close bt out
,I/BtToSocketBase( 4863): Close bt socket
,I/BtToSocketBase( 4863): Close bt in
I/BtToSocketBase( 4863): Close bt out
,I/BtToSocketBase( 4863): Close bt socket
,I/jxcore-log( 4863): 2015-12-04T08:12:54.779Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4863): 
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f7289c rs_disc_pending=1
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 4921): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 4921): RFCOMM_DisconnectInd LCID:0x45
,W/bt-btif ( 4921): dm_pm_timer expires
W/bt-btif ( 4921): dm_pm_timer expires 0
W/bt-btif ( 4921): proc dm_pm_timer expires
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): Error type "connect_error" when connecting to the test server
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  303): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  303): NetlinkHandler, interfaceAdded
,I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
E/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  303): , Wifi = 0
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  303): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
E/MDMCTBK (  303): MdmCutbackHndler,Airplane Mode Enabled !! =1
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 6982): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6982): Bluetooth Device Name: S5mini-1
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4863): 2015-12-04T08:12:59.925Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:59.925Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:59.926Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:59.932Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:59.933Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:59.933Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
,I/BtConnectorHelper( 4863): Disconnect outgoing peer: B4:CE:F6:AB:A4:6A
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 4863): Close LocalOutputStream
I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
I/BtToRequestSocket( 4863): Close server socket
I/jxcore-log( 4863): 2015-12-04T08:12:59.952Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 4863): 
I/jxcore-log( 4863): ---- round done--------
I/jxcore-log( 4863): 
I/jxcore-log( 4863): ---- gotta redo : B4:CE:F6:AB:A4:6A, try count now: 1
I/jxcore-log( 4863): 
I/jxcore-log( 4863): do fake peer & start
I/jxcore-log( 4863): 
I/jxcore-log( 4863): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:59.955Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:12:59.956Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:12:59.956Z SendDataConnector.js: do connect now
I/jxcore-log( 4863): 
,I/        ( 4863): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 4863): Connecting to null, at 08:EC:A9:50:76:27
,I/jxcore-log( 4863): 2015-12-04T08:12:59.963Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 4863): 
,I/BTConnectToThread( 4863): Starting to connect
W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B4:CE:F6:AB:A4:6A done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 4921): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 4921): invalid rfc slot id: 18
,I/BtToSocketBase( 4863): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4863): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT3559
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
I/BtToSocketBase( 4863): Close LocalOutputStream
I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
,W/bt-btif ( 4921): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 4863): 2015-12-04T08:13:00.444Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4863): 
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f7289c rs_disc_pending=1
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): Error type "connect_error" when connecting to the test server
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 4921): process_service_search_attr_rsp
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f7289c rs_disc_pending=1
,W/bt-btif ( 4921): bta_dm_check_av:0
,I/BluetoothBondStateMachine( 4921): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,E/bt-btif ( 4921): check_cod: remote_cod = 0x5a020c
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 4921): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 4921): Entering PendingCommandState State
,I/ActivityManager(  887): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=7079 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 4921): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 4921): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 4921): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 4921): StableState(): Entering Off State
,I/ActivityManager(  887): Killing 6862:com.android.chrome/u0a52 (adj 15): empty #7
,D/BluetoothMetrics( 4921): btclass5a020c
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_6862/cgroup.procs: No such file or directory
,D/Checkin ( 4921): publish the event [tag = MOT_BT event name = PAIRING]
,W/ResourcesManager( 7079): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72ddc rs_disc_pending=1
W/bt-btif ( 4921): bta_dm_check_av:0
W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,I/art     (  887): Explicit concurrent mark sweep GC freed 14591(765KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.477ms total 114.253ms
,D/BluetoothManagerService(  887): Message: 20
,D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b2fa7bd:true
,I/ActivityManager(  887): Killing 6885:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_6885/cgroup.procs: No such file or directory
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 6982): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6982): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72ddc rs_disc_pending=0
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:1
,W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4863): Starting to Handshake
,I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4863): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/BTConnectToThread( 4863): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 4863): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 4863): HandshakeOk : samsung-SM-A300FU_PT2828
I/HS      ( 4863): Hand Shake finished outgoing for : samsung-SM-A300FU_PT2828
,I/BtConnectorHelper( 4863): Starting the connected thread incoming : false, samsung-SM-A300FU_PT2828
,I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 4863): mHTTPPort  set to : 57173
,I/BtConnectorHelper( 4863): Request socket is using : 57173
I/BtToRequestSocket( 4863): Now accepting connections
,I/BtConnectorHelper( 4863): Calling ConnectionStatusUpdate with port :57173
,I/jxcore-log( 4863): 2015-12-04T08:13:06.210Z SendDataConnector.js: CLIENT connected to 57173, error: null
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:13:06.210Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4863): 
,I/BtToRequestSocket( 4863): incoming data from: /127.0.0.1, port: 57173
,I/BtToRequestSocket( 4863): Set local streams
I/BtToRequestSocket( 4863): rin ended ---------------------------;
,I/jxcore-log( 4863): 2015-12-04T08:13:06.225Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 4863): 
,D/        ( 4921): PORT_WriteDataCO: tx queue is full,tx.queue_size:10308,tx.queue.count:11,available:24706
,I/jxcore-log( 4863): 2015-12-04T08:13:06.794Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:06.832Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 4863): 
,D/        ( 4921): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 4863): 2015-12-04T08:13:06.913Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:06.952Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 4863): 
,D/        ( 4921): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/jxcore-log( 4863): 2015-12-04T08:13:07.001Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:07.052Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:07.099Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:07.142Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:07.262Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:07.274Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:07.275Z SendDataConnector.js: got all data for this round
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:07.283Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:07.284Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
I/BtConnectorHelper( 4863): Disconnect outgoing peer: 08:EC:A9:50:76:27
I/BtToSocketBase( 4863): Stop ReceivingThread
,I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 4863): Close LocalOutputStream
,I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
I/BtToRequestSocket( 4863): Close server socket
I/jxcore-log( 4863): 2015-12-04T08:13:07.302Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 4863): 
I/jxcore-log( 4863): ---- round done--------
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): do fake peer & start
I/jxcore-log( 4863): 
I/jxcore-log( 4863): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:13:07.307Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:13:07.307Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:13:07.307Z SendDataConnector.js: do connect now
I/jxcore-log( 4863): 
,I/        ( 4863): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 4863): Connecting to null, at 34:FC:EF:11:B1:66
I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 4863): Starting to connect
W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4921): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72ddc rs_disc_pending=1
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): Error type "connect_error" when connecting to the test server
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72f9c rs_disc_pending=1
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 4921): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 4921): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 4921): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4921): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 4921): Entering PendingCommandState State
,W/bt-btif ( 4921): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [08:ec:a9:50:75:41]: 6, f, 410d
,I/BTConnectionReceiver( 6982): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6982): Bluetooth Device Name: A3-1
,I/BluetoothBondStateMachine( 4921): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 4921): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 4921): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 4921): StableState(): Entering Off State
,D/BluetoothMetrics( 4921): btclass5a020c
,D/Checkin ( 4921): publish the event [tag = MOT_BT event name = PAIRING]
,E/bt-btm  ( 4921): peer should have initiated security process by now (SM4 to SM4)
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:255
,W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 4863): we got incoming connection
I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
,I/BTListenerThread( 4863): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/BTListenerThread( 4863): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 4863): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT476","ra":"08:EC:A9:50:75:41"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4863): MESSAGE_WRITE 81 bytes.
,I/HS      ( 4863): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT476
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4863): Starting the connected thread incoming : true, samsung-SM-A300FU_PT476
,I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BTConnectedThread
I/BtConnectorHelper( 4863): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4863): --DoOneRunRound started
,I/BtToRequestSocket( 4863): LocalHost address: localhost/127.0.0.1, port: 43965
,I/BtToRequestSocket( 4863): --DoOneRunRound ended
,I/jxcore-log( 4863): 2015-12-04T08:13:10.610Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4863): 
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:1
,W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4863): Starting to Handshake
I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4863): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72f9c rs_disc_pending=0
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4863): 2015-12-04T08:13:11.058Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:11.062Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:11.255Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4863): 
,I/BTConnectToThread( 4863): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 4863): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 4863): HandshakeOk : LGE-Nexus 5_PT5363
I/HS      ( 4863): Hand Shake finished outgoing for : LGE-Nexus 5_PT5363
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4863): Starting the connected thread incoming : false, LGE-Nexus 5_PT5363
I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 4863): mHTTPPort  set to : 36098
I/BtConnectorHelper( 4863): Request socket is using : 36098
I/BtToRequestSocket( 4863): Now accepting connections
,I/jxcore-log( 4863): 2015-12-04T08:13:11.492Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4863): 
,I/BtConnectorHelper( 4863): Calling ConnectionStatusUpdate with port :36098
,I/jxcore-log( 4863): 2015-12-04T08:13:11.571Z SendDataConnector.js: CLIENT connected to 36098, error: null
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:13:11.571Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4863): 
,I/BtToRequestSocket( 4863): incoming data from: /127.0.0.1, port: 36098
,I/BtToRequestSocket( 4863): Set local streams
I/BtToRequestSocket( 4863): rin ended ---------------------------;
,I/jxcore-log( 4863): 2015-12-04T08:13:11.585Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:11.586Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 4863): 
,D/        ( 4921): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12696
,I/jxcore-log( 4863): 2015-12-04T08:13:12.077Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:12.671Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
I/jxcore-log( 4863): Error type "connect_error" when connecting to the test server
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/        ( 4921): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19038
,I/jxcore-log( 4863): 2015-12-04T08:13:13.281Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 4863): 
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 6982): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6982): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72f9c rs_disc_pending=1
W/bt-btif ( 4921): bta_dm_check_av:0
W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4863): 2015-12-04T08:13:13.698Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 4863): 
,D/        ( 4921): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9138
,I/jxcore-log( 4863): 2015-12-04T08:13:13.749Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:13.800Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:13.844Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:13.885Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:13.941Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:13.945Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 4863): 
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72f9c rs_disc_pending=0
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311167, SEQNUM=4622, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12319, POWER_SUPPLY_CHARGE_COUNTER=-1739, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): Error type "connect_error" when connecting to the test server
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 4921): dm_pm_timer expires
,W/bt-btif ( 4921): dm_pm_timer expires 1
W/bt-btif ( 4921): proc dm_pm_timer expires
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 4921): invalid rfc slot id: 20
,I/BtToSocketBase( 4863): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4863): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT476
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
I/BtToSocketBase( 4863): Close LocalOutputStream
I/BtToSocketBase( 4863): Close localHostSocket
,I/BtToSocketBase( 4863): Close bt in
,I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 4863): 2015-12-04T08:13:21.367Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4863): 
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,I/BTConnectionReceiver( 6982): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6982): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:255
,W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4863): we got incoming connection
,I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
I/BTListenerThread( 4863): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/BTListenerThread( 4863): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 4863): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4863): MESSAGE_WRITE 81 bytes.
,I/HS      ( 4863): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT4577
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4863): Starting the connected thread incoming : true, samsung-SM-G800F_PT4577
I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BTConnectedThread
I/BtConnectorHelper( 4863): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4863): --DoOneRunRound started
,I/BtToRequestSocket( 4863): LocalHost address: localhost/127.0.0.1, port: 43965
I/BtToRequestSocket( 4863): --DoOneRunRound ended
,I/jxcore-log( 4863): 2015-12-04T08:13:22.197Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4863): 
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72f9c rs_disc_pending=1
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 4921): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
,W/bt-rfcomm( 4921): RFCOMM_DisconnectInd LCID:0x4f
,I/jxcore-log( 4863): 2015-12-04T08:13:22.621Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:22.656Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:22.662Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:22.666Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:22.765Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): Error type "connect_error" when connecting to the test server
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4863): 2015-12-04T08:13:23.001Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 4863): 
,I/wpa_supplicant( 6391): wlan0: Trying to associate with SSID 'NG700'
E/wpa_supplicant( 6391): DSDS: eapol_sm_notify_config config->sim_num = 1
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 0 c
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  303): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  303): Event received = Trying to associate with
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  303): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  887): [1,449,216,803,422 ms] noteScanEnd no scan source
,D/WifiMonitor(  887): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  887): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@26ba4271 sup_state=SCANNING debouncing=false
,E/WifiConfigStore(  887):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TCMD    (  463): NL - Read 312 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 88 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 68 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
I/wpa_supplicant( 6391): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  303): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  303): Event received = Associated with c0:ff:d4
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  303): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  463): NL - Read 80 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 80 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 68 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info"NG700"
,E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Tethering(  887): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 6391): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  303): Event received = WPA: Key negotiation com
I/wpa_supplicant( 6391): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  303): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  303):  STA Connected !!
D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,E/MDMCTBK (  303): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2462, reply_len: 4, ret: 0
,D/MDMCTBK (  303): get_freq !!, resp=2462
I/MDMCTBK (  303): get_freq !!, Strip data
,I/MDMCTBK (  303): get_freq !!, band = 2, freq = 2462
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): get_property_value, Enter
I/MDMCTBK (  303): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  303): get_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
,I/MDMCTBK (  303): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
,I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
,I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  303): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  303): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
,I/MDMCTBK (  303): get_property_value, Enter
I/MDMCTBK (  303): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  303): get_property_value, Exit
I/MDMCTBK (  303): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1191538712
,I/MDMCTBK (  303): return from set_get_from_wpa_supplicant
I/MDMCTBK (  303): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
,E/MDMCTBK (  303): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  303): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 6391): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false,
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/MDMCTBK (  303): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  303): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  303): , reply_len: 3, ret: 0
E/MDMCTBK (  303): MdmCutbackHndler, resp=OK
E/MDMCTBK (  303): 
D/MDMCTBK (  303): wifi_set_tx_pwr: Exit,
,E/WifiStateMachine(  887): Network connection established
,E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  887): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  887): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  887): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  887): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  299): Setting iface cfg
,E/WifiStateMachine(  887): Start Dhcp Watchdog 2
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend false
,E/wpa_supplicant( 6391): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  887): Unexpected BatchedScanResults :null
E/wpa_supplicant( 6391): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  887): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3f194ae0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3f194ae0 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6391): P2P-FIND-STOPPED 
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  303): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  887): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): discovery change broadcast false
,I/jxcore-log( 4863): 2015-12-04T08:13:24.038Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:13:24.039Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:13:24.039Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:13:24.039Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:13:24.040Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 4863): 
I/BtToSocketBase( 4863): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 4863): Disconnect outgoing peer: LGE-Nexus 5_PT5363
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
I/BtToSocketBase( 4863): Close LocalOutputStream
I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
I/BtToSocketBase( 4863): Close bt out
D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
I/BtToSocketBase( 4863): Close bt socket
I/BtToRequestSocket( 4863): Close server socket
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiP2pService(  887): P2P_FIND is deffered
I/        ( 4863): Discovery state changed to Stopped.
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/DHCPCD  ( 7209): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 7209): version 5.5.6 starting
,E/DHCPCD  ( 7209): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 7209): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 7209): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 7209): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 7209): wlan0: rebinding lease of 192.168.1.134
D/DHCPCD  ( 7209): wlan0: sending REQUEST (xid 0xfc693137), next in 3.90 seconds
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72f9c rs_disc_pending=1
W/bt-btif ( 4921): bta_dm_check_av:0
W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4921): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  303): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,E/WifiStateMachine(  887): [1,449,216,805,518 ms] noteScanEnd no scan source
,D/WifiP2pService(  887): InactiveState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  887): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ObtainingIpState@1877552c sup_state=COMPLETED debouncing=false
,I/DHCPCD  ( 7209): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/DHCPCD  ( 7209): wlan0: leased 192.168.1.134 for 86400 seconds
,D/DHCPCD  ( 7209): wlan0: adding IP address 192.168.1.134/24
D/DHCPCD  ( 7209): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 7209): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 7209): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  463): NL - Read 60 bytes from update socket.
,D/TCMD    (  463): NL - ignore NL message, type = 20
D/TCMD    (  463): Listening for incoming client connection request
,D/DHCPCD  ( 7209): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 6982): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6982): Bluetooth Device Name: A3-1
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6391): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  887): WifiStateMachine DHCP successful
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  887): Calling ARP set with IP = 192.168.1.134
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  887): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  887): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  887): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  887): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  887): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  887): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  887): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  887): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  887): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  887):    accepting network in place of null
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/CSLegacyTypeTracker(  887): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  887): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/ModemStatsDSDetect( 1526): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
I/ModemStatsDSDetect( 1526): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1526): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72f9c rs_disc_pending=1
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 6391): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-30
,I/wpa_supplicant( 6391): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-42
I/wpa_supplicant( 6391): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-55
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  303): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  303): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -55 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -55 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/ConnectivityService(  887): Failed to find a new network - expiring NetTransition Wakelock
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP b6:ce:
,D/MDMCTBK (  303): Event received = P2P-SERV-DISC-RESP b6:ce:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/        ( 4863): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}, typeCordovap2p._tcp.local.:
,I/        ( 4863): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3559, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 4863): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3559, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,--------- beginning of crash
F/libc    ( 6391): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 6391 (wpa_supplicant)
,I/libc    ( 6391): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4863): Cleared service requests
,I/        ( 4863): Starting peer discovery failed, error code 0
,E/QC-QMI  (  422): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  422): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 22
,E/QC-QMI  (  422): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 23
E/QC-QMI  (  422): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 24
E/QC-QMI  (  422): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 25
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 6982): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6982): Bluetooth Device Name: Nexus 5
,I/ActivityManager(  887): Waited long enough for: ServiceRecord{1d3402b9 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524295
,I/jxcore-log( 4863): 2015-12-04T08:13:29.046Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:29.046Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): DBG, CoordinatorConnector connect called
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): Coordinator is now connected to the server!
I/jxcore-log( 4863): 
,I/chromium( 4863): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Dec 2015 08:13:29 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449216809208], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449216809179]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Validated
,D/ConnectivityService(  887): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  887): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524290
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1526): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1526): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1526): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1526): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2550): now: 676342 ,futureTime: 9223372036854775807
D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): now: 676343 ,futureTime: 9223372036854775807
D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): now: 676343 ,futureTime: 9223372036854775807
D/OtaApp  ( 2550): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1457): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7301 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Central_PollingManager( 1457): now: 676406 ,futureTime: 86471933
D/Central_PollingManager( 1457): Polling alarm set to expire at: 86471933 Current Time: 676406
,D/OtaApp  ( 2550): [debug] > PollingManagerService, now: 676406 ,futureTime: 21558665
,D/OtaApp  ( 2550): [debug] > Polling alarm set to expire at: 21558665 Current Time: 676408
,D/OtaApp  ( 2550): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2550): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2550): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2550): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,D/OtaApp  ( 2550): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/CCE     ( 2550): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2550): createDeviceIdOrLogin update_device
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2550): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2550): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2550): createDeviceIdOrLogin update_device
D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2550): set mOutstandingReq to true.
I/ Nonce  ( 2550):  Nonce getNonce 
,I/ Nonce  ( 2550):  Nonce Request 
I/ Nonce  ( 2550):  Nonce execute Request 
,D/MMApiWebService( 2550): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2550): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2550): createDeviceIdOrLogin update_device
D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2550): Not proxy app, so login/provision not allowed
,I/MusicStore( 7301): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7301): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 2550): Explicit concurrent mark sweep GC freed 44287(2MB) AllocSpace objects, 7(158KB) LOS objects, 40% free, 11MB/19MB, paused 1.132ms total 74.669ms
,D/MMApiWebService( 2550): generating token using payload instead of using session token
,D/ Nonce  ( 2550):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2550): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7301): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7301): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7301): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7301): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7301): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 7301): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7301): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d225af5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7301): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7301): GMSCore installation verified
,I/ConfigStore( 7301): Config Database version: 1
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/MediaRouter( 7301): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7301): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7301): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7301): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7341 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7301): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7301): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=7359 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7359): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7359): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7359): VM with version 2.1.0 has multidex support
I/MultiDex( 7359): install
I/MultiDex( 7359): VM has multidex support, MultiDex support library is disabled.
,I/art     (  887): Explicit concurrent mark sweep GC freed 31953(1596KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.548ms total 125.869ms
,V/Mms     ( 7341): mnc/mcc: 
,V/Mms     ( 7341): tag: int value: recipientLimit - 20
V/Mms     ( 7341): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7341): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7341): tag: int value: maxSubjectLength - 80
V/Mms     ( 7341): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7341): tag: bool value: enableGroupMms - false
,V/Mms     ( 7341):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7341): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7391 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,V/JNIHelp ( 7359): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ActivityManager(  887): Killing 6909:android.process.acore/u0a7 (adj 15): empty #7
,W/ActivityThread( 7359): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7359): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30282fe8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7359): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_6909/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 6941:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/PhoneMonitor( 7391): Register our PhoneStateListener
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_6941/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7391): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7391): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ Nonce  ( 2550):  Nonce Reponse 
D/        ( 2550): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"54d49ccc-93dc-4038-93c8-de6b42a91572"}
D/MMApiWSBase( 2550): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2550):  Nonce Handle Reponse 
D/MMApiProvisionService( 2550): mOutstandingReq set to false
,I/ActivityManager(  887): Killing 7023:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,D/NativeLibraryUtils( 7359): Install completed successfully. count=13 extracted=0
,I/art     ( 1457): Explicit concurrent mark sweep GC freed 6572(335KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/12MB, paused 793us total 31.852ms
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_7023/cgroup.procs: No such file or directory
,D/MMApiProvisionService( 2550):  pTime 1449056434640 sExp 172742 cTime 1449216810746 tTime 1449229176640
D/MMApiProvisionService( 2550):  No login Required 
,I/art     ( 1620): Explicit concurrent mark sweep GC freed 7459(434KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 11MB/15MB, paused 573us total 47.733ms
,I/CheckinService( 7359): Checkin interval check for package: unspecified last checkin: 1449216340721 min interval config: 0 actual interval: 470066
,I/CheckinService( 7359): Disabling old GoogleServicesFramework version
,I/CheckinService( 7359): Checking schedule, now: 1449216810837 next: 1449216370698
,I/CheckinService( 7359): active receiver: enabled
,I/CheckinService( 7359): Preparing to send checkin request
,I/EventLogService( 7359): Accumulating logs since 1449216334184
,I/iu.SyncManager( 7359): SYNC; picasa accounts
,D/NetworkLogImpl( 7359): Loaded NetworkSpeedPredictor
,I/iu.Environment( 7359): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/art     ( 7359): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/art     ( 7359): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/iu.UploadsManager( 7359): num queued entries: 0
,I/iu.UploadsManager( 7359): num updated entries: 0
I/iu.SyncManager( 7359): NEXT; no task
,D/ChimeraCfgMgr( 7359): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 7359): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7436 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/DataUsage( 2550): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,I/CheckinRequestBuilder( 7359): Checkin reason type: 8 attempt count: 1
,D/WifiService(  887): New client listening to asynchronous messages
,E/ActivityThread( 7359): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  887): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7466 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7486 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 27.776ms
,W/ResourcesManager( 7466): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7466): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 23.231ms
,W/ResourcesManager( 7486): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.538ms
,I/MultiDex( 7466): VM with version 2.1.0 has multidex support
,I/MultiDex( 7466): install
I/MultiDex( 7466): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7466): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 7466): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7466): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6c2bdd2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7466): Installed default security provider GmsCore_OpenSSL
,I/art     ( 7466): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 7466): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/Babel_SMS( 7486): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7486): MmsConfig.loadMmsSettings
I/Babel_SMS( 7486): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7486): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7486): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7486): MmsConfig.loadFromResources
,E/Babel_SMS( 7486): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7486): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/WVCdm   (  308): Instantiating CDM.
,I/WVCdm   (  308): CdmEngine::OpenSession
I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
,W/Settings( 7486): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/Babel_Crash( 7486): startup - clean
D/NativeLibraryUtils( 7466): Install completed successfully. count=13 extracted=0
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  308): Service_Initialize: starts!
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,I/Babel   ( 7486): deleted: false for 0
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d10000
E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d10000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb55a1960
D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb834cf88, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb82198a8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb83647b0, idLength=0xbe8172b0
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: ends! returns 0
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
D/WVCdm   (  308): PrepareKeyRequest: nonce=2379403975
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8318ee8
D/DrmWidevineDash(  308): message_length=1591, signature=0xb82940a8, signature_length=3196154516
,I/art     (  887): Explicit concurrent mark sweep GC freed 10379(502KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.875ms total 124.143ms
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7522 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  308): CdmEngine::CloseSession
,D/DrmWidevineDash(  308): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  308): L3 Terminate.
D/DrmWidevineDash(  308): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  308): Service_Uninitialize: starts!
D/QSEECOMAPI: (  308): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  308): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  308): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,W/VideoCapabilities( 7486): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7486): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7486): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7486): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7486): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7486): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7486): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7486): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7486): onServiceConnected
,W/Babel   ( 7486): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7522): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7522): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7522): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7522):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7522):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7522): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7522): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,W/GAv4    ( 7522): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7486): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  887): Killing 7079:com.android.settings/1000 (adj 15): empty #7
,W/GAv4    ( 7522): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7522): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 7550): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  887): failed to open /acct/uid_1000/pid_7079/cgroup.procs: No such file or directory
,I/dex2oat ( 7550): dex2oat took 69.792ms (threads: 4)
,I/Adreno-EGL( 7466): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7466): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7466): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7466): Local Branch: 
I/Adreno-EGL( 7466): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7466): Local Patches: NONE
I/Adreno-EGL( 7466): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7466): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7466): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7466): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7466): Local Branch: 
I/Adreno-EGL( 7466): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7466): Local Patches: NONE
I/Adreno-EGL( 7466): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 7522): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7522): Time to load native libraries: 1 ms (timestamps 9583-9584)
I/LibraryLoader( 7522): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7522): Binding Chromium to main looper Looper (main, tid 1) {32123f82}
,I/LibraryLoader( 7522): Expected native library version number "",actual native library version number ""
I/chromium( 7522): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7522): Initializing chromium process, singleProcess=true
,W/art     ( 7522): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7522): ApplicationContext is null in ApplicationStatus
,I/BtToSocketBase( 4863): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4863): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT4577
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
I/BtToSocketBase( 4863): Close LocalOutputStream
I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
W/bt-btif ( 4921): invalid rfc slot id: 23
I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 4863): 2015-12-04T08:13:32.669Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4863): 
W/chromium( 7522): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7522): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7522): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7522): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7522): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7522): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7522): Local Branch: 
I/Adreno-EGL( 7522): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7522): Local Patches: NONE
I/Adreno-EGL( 7522): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7466): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7466): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7466): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7466): Local Branch: 
I/Adreno-EGL( 7466): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7466): Local Patches: NONE
I/Adreno-EGL( 7466): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7522): Requires BLUETOOTH permission
I/NSApplication( 7522): Starting up...
,I/Adreno-EGL( 7466): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7466): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7466): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7466): Local Branch: 
I/Adreno-EGL( 7466): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7466): Local Patches: NONE
I/Adreno-EGL( 7466): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7591 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6982:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/WVCdm   (  308): CdmEngine::OpenSession
I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  308): Service_Initialize: starts!
,D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_6982/cgroup.procs: No such file or directory
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d10000
E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d10000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
,D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb4ffb960
D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb835a1d8, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb82198a8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb83647d0, idLength=0xbe8172b0
,D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  308): PrepareKeyRequest: nonce=2973198626
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8318ee8
D/DrmWidevineDash(  308): message_length=1626, signature=0xb82940a8, signature_length=3196154516
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7612 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7301:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_7301/cgroup.procs: No such file or directory
,W/ResourcesManager( 7612): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  308): CdmEngine::CloseSession
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  308): L3 Terminate.
D/DrmWidevineDash(  308): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  308): Service_Uninitialize: starts!
D/QSEECOMAPI: (  308): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  308): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  308): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [08:ec:a9:50:75:41]: 6, f, 6109
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7636 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/CheckinRequestBuilder( 7359): Classify the device as Phone.
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:255
,W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4863): we got incoming connection
I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
I/BTListenerThread( 4863): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/ActivityManager(  887): Killing 7391:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ActivityManager(  887): Killing 7341:com.android.mms/u0a23 (adj 15): empty #8
,I/ContactLocale( 7636): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/BTListenerThread( 4863): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 4863): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT476","ra":"08:EC:A9:50:75:41"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 4863): MESSAGE_WRITE 81 bytes.
I/HS      ( 4863): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT476
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 4863): Starting the connected thread incoming : true, samsung-SM-A300FU_PT476
I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 4863): Creating BTConnectedThread
I/BtConnectorHelper( 4863): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4863): --DoOneRunRound started
,I/BtToRequestSocket( 4863): LocalHost address: localhost/127.0.0.1, port: 43965
,I/BtToRequestSocket( 4863): --DoOneRunRound ended
,I/jxcore-log( 4863): 2015-12-04T08:13:33.560Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4863): 
,D/EmailService.MarketingOptInSetter( 2550): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_7391/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_7341/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2550): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2550): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2550): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2550): onServiceConnected()
,D/GetNotificationsWS( 2550): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2550): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2550): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2550): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2550): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2550): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  887): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2550): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2550): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2550): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2550): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/WearableService( 1710): callingUid 10016, callindPid: 1710
,E/MDM     ( 1710): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/OtaApp  ( 2550): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2550): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2550): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2550): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 4863): Cleared service requests
I/        ( 4863): Starting peer discovery failed, error code 0
,W/InstanceID/Rpc( 7359): Found 10016
,D/GCM     ( 1620): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/LocationInitializer( 7359): Restart initialization of location
,D/AuthorizationBluetoothService( 1620): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 7359): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/art     ( 1620): Explicit concurrent mark sweep GC freed 7639(458KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 11MB/15MB, paused 691us total 55.662ms
,W/GCoreFlp( 1710): No location to return for getLastLocation()
,W/FusedLocationProvider( 1620): location=null
,E/MDM     ( 1710): [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1620): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/LocationInitializer( 7359): Restart initialization of location
,D/AuthorizationBluetoothService( 1620): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 7359): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=7690 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,W/GCoreFlp( 1710): No location to return for getLastLocation()
,W/FusedLocationProvider( 1620): location=null
,I/CheckinTask( 7359): Sending checkin request (9446 bytes)
,I/jxcore-log( 4863): 2015-12-04T08:13:34.047Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:34.048Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:34.048Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:13:34.049Z SendDataConnector.js: do connect now
I/jxcore-log( 4863): 
I/        ( 4863): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
I/        ( 4863): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 4863): Starting to connect
,W/BluetoothAdapter( 4863): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 4921): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e9dd71c:true
,I/BTConnectionReceiver( 7690): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7719 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/BluetoothClassifier( 7690): Bluetooth Device Name: A3-1
,I/ActivityManager(  887): Killing 7591:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  887): Killing 7522:com.google.android.apps.magazines/u0a81 (adj 15): empty #8
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_7591/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_7522/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 7359): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 7359): Failed to find provider info for com.google.android.wearable.settings
,I/jxcore-log( 4863): 2015-12-04T08:13:34.705Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4863): 
,I/CheckinRequestBuilder( 7359): Classify the device as Phone.
,I/CheckinTask( 7359): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 7359): Checking schedule, now: 1449216814731 next: 1449817951722
,I/CheckinService( 7359): active receiver: disabled
,D/CheckinService( 7359): Recording last checkin time for package unspecified as 1449216814750
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7755 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  887): Explicit concurrent mark sweep GC freed 12775(623KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.454ms total 118.882ms
,D/PhoneMonitor( 7755): Register our PhoneStateListener
,V/SetupWizard( 7755): Connected to Gservices successfully
,I/ActivityManager(  887): Killing 7612:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_7612/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 7359): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 7359): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1620): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/bt-rfcomm( 4921): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
,W/bt-rfcomm( 4921): RFCOMM_DisconnectInd LCID:0x41
,I/jxcore-log( 4863): 2015-12-04T08:13:36.016Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:36.021Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:36.101Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:36.117Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 4863): 
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 4863): 2015-12-04T08:13:36.220Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 4863): 
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [34:fc:ef:11:b1:66]: 7, 1d, 7d3
,I/BTConnectionReceiver( 7690): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7690): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72f9c rs_disc_pending=1
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 4921): process_service_search_attr_rsp
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:1
,W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4863): Starting to Handshake
,I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4863): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=285, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310759, SEQNUM=4658, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5308, POWER_SUPPLY_CHARGE_COUNTER=-1814, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72f9c rs_disc_pending=1
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 4863): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 4863): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 4863): HandshakeOk : LGE-Nexus 5_PT5363
I/HS      ( 4863): Hand Shake finished outgoing for : LGE-Nexus 5_PT5363
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4863): Starting the connected thread incoming : false, LGE-Nexus 5_PT5363
,I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4863): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 4863): mHTTPPort  set to : 37862
,I/BtConnectorHelper( 4863): Request socket is using : 37862
I/BtToRequestSocket( 4863): Now accepting connections
,I/BtConnectorHelper( 4863): Calling ConnectionStatusUpdate with port :37862
,I/jxcore-log( 4863): 2015-12-04T08:13:38.049Z SendDataConnector.js: CLIENT connected to 37862, error: null
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:13:38.050Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4863): 
,I/BtToRequestSocket( 4863): incoming data from: /127.0.0.1, port: 37862
,I/BtToRequestSocket( 4863): Set local streams
I/BtToRequestSocket( 4863): rin ended ---------------------------;
,I/jxcore-log( 4863): 2015-12-04T08:13:38.066Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 4863): 
,I/ActivityManager(  887): Killing 7636:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_7636/cgroup.procs: No such file or directory
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 7690): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7690): Bluetooth Device Name: S5mini-1
,I/ActivityManager(  887): Killing 7486:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_7486/cgroup.procs: No such file or directory
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7818 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  887): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  887): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@36fe431a
,V/GmsNetworkLocationProvi( 1710): DISABLE
,I/GCoreNlp( 1710): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 7818): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Launcher( 1544): Deferring update until onResume
,I/Babel_SMS( 7818): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7818): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7818): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7818): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7818): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7818): MmsConfig.loadFromResources
,E/Babel_SMS( 7818): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7818): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7818): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7818): startup - clean
,I/Babel   ( 7818): deleted: false for 0
,I/ActivityManager(  887): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7851 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/ProcessCpuTracker(  887): Skipping unknown process pid 7815
W/ProcessCpuTracker(  887): Skipping unknown process pid 7816
,W/ProcessCpuTracker(  887): Skipping unknown process pid 7836
W/ProcessCpuTracker(  887): Skipping unknown process pid 7848
,W/VideoCapabilities( 7818): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7818): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7818): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7818): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7818): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7818): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7818): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7818): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7878 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ContactLocale( 7851): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/vclib   ( 7818): onServiceConnected
,W/Babel   ( 7818): Attempted to change video mute state without an active call.
W/asset   ( 7878): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7878): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 7818): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7818): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7818): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7897 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  325): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 21.307ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 19.208ms
,W/System  ( 7818): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7818): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  887): Killing 7436:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.219ms
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_7436/cgroup.procs: No such file or directory
,D/Finsky  ( 7897): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7897): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7897): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7897): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7897): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7897): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7897): Skipping gmscore version check
,D/Finsky  ( 7897): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/UpdateIcingCorporaServi( 7690): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1544): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3154b new=com.google.android.velvet.VelvetApplication@3154b
,D/Finsky  ( 7897): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 7359): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7950 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 7359): Null package name or gms related package.  Ignoreing.
,W/ResourcesManager( 7950): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7690): UpdateCorporaTask done [took 124 ms] updated apps [took 124 ms] 
,I/ActivityManager(  887): Killing 7719:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/Icing   ( 7359): Storage manager: low false usage 1.69MB avail 2.69GB capacity 4.12GB
,W/Icing   ( 7359): Received bad json for section weights override -- ignoring.
,W/Icing   ( 7359): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 7359): Received bad json for section weights override -- ignoring.
W/Icing   ( 7359): Received bad json for corpus context scoring override -- ignoring.
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_7719/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 7755:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_7755/cgroup.procs: No such file or directory
,I/Icing   ( 7359): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 7359): Internal init done: storage state 0
,I/Icing   ( 7359): Post-init done
,I/Icing   ( 7359): updateResources: need to parse f{com.google.android.gms}
,W/bt-btif ( 4921): dm_pm_timer expires
,W/bt-btif ( 4921): dm_pm_timer expires 1
W/bt-btif ( 4921): proc dm_pm_timer expires
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 7690): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7690): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 4921): new conn_srvc id:26, app_id:255
,W/bt-btif ( 4921): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4921): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4863): we got incoming connection
,I/BTHandshakeSocketThread( 4863): Creating BTHandshakeSocketThread
I/BTListenerThread( 4863): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread started
,I/BTListenerThread( 4863): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 4863): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4863): MESSAGE_WRITE 81 bytes.
,I/HS      ( 4863): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT4577
I/BTHandshakeSocketThread( 4863): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4863): Starting the connected thread incoming : true, samsung-SM-G800F_PT4577
,I/BtToSocketBase( 4863): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 4863): Creating BTConnectedThread
I/BtConnectorHelper( 4863): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4863): --DoOneRunRound started
,I/BtToRequestSocket( 4863): LocalHost address: localhost/127.0.0.1, port: 43965
,I/jxcore-log( 4863): 2015-12-04T08:13:43.835Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4863): 
,I/BtToRequestSocket( 4863): --DoOneRunRound ended
,I/jxcore-log( 4863): 2015-12-04T08:13:44.270Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:44.310Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:44.315Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:44.319Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:44.324Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 4863): 
,W/bt-btif ( 4921): invalid rfc slot id: 24
,I/BtToSocketBase( 4863): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4863): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT476
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
I/BtToSocketBase( 4863): Close LocalOutputStream
I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 4863): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT476
I/BtToSocketBase( 4863): Close bt in
I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
,I/BtToSocketBase( 4863): Close bt out
,I/BtToSocketBase( 4863): Close bt socket
,I/jxcore-log( 4863): 2015-12-04T08:13:44.367Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:44.368Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 4863): 
,W/bt-rfcomm( 4921): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 4921): RFCOMM_DisconnectInd LCID:0x44
,I/ActivityManager(  887): Killing 7466:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_7466/cgroup.procs: No such file or directory
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager(  887): Killing 7818:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_7818/cgroup.procs: No such file or directory
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72f9c rs_disc_pending=0
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72f9c rs_disc_pending=0
W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4863): 2015-12-04T08:13:48.123Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:48.123Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:48.128Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:48.131Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:48.134Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 4863): 
,I/BtToSocketBase( 4863): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 4863): Disconnect outgoing peer: LGE-Nexus 5_PT5363
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
,I/BtToSocketBase( 4863): Close LocalOutputStream
I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
I/BtToRequestSocket( 4863): Close server socket
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72f9c rs_disc_pending=1
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4921): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 7690): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7690): Bluetooth Device Name: A3-1
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,I/CheckinService( 7359): Done disabling old GoogleServicesFramework version
,W/SQLiteConnectionPool( 7359): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 7690): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7690): Bluetooth Device Name: Nexus 5
,I/art     (  887): Explicit concurrent mark sweep GC freed 19290(945KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.464ms total 127.324ms
,I/jxcore-log( 4863): 2015-12-04T08:13:53.131Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:53.132Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4863): 
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72c1c rs_disc_pending=0
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4921): invalid rfc slot id: 25
,I/BtToSocketBase( 4863): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4863): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT4577
I/BtToSocketBase( 4863): Stop ReceivingThread
I/BtToSocketBase( 4863): Stop SendingThread
I/BtToSocketBase( 4863): Close local in
I/BtToSocketBase( 4863): Close LocalOutputStream
,I/BtToSocketBase( 4863): Close localHostSocket
I/BtToSocketBase( 4863): Close bt in
,I/BtToSocketBase( 4863): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 4863): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4863): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT4577
I/BtToSocketBase( 4863): Close bt in
I/BtToSocketBase( 4863): Close bt out
I/BtToSocketBase( 4863): Close bt socket
,I/BtToSocketBase( 4863): Close bt out
,I/BtToSocketBase( 4863): Close bt socket
,I/jxcore-log( 4863): 2015-12-04T08:13:55.151Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4863): 
,W/bt-rfcomm( 4921): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 4921): RFCOMM_DisconnectInd LCID:0x47
,E/WifiStateMachine(  887): Connection lost, restart supplicant
,E/WifiStateMachine(  887): setWifiState: disabled
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  887): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiConfigStore(  887): failed to set BSSID: any
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  299): Clearing all IP addresses on wlan0
,D/TCMD    (  463): NL - Read 60 bytes from update socket.
,D/TCMD    (  463): NL - ignore NL message, type = 21
D/TCMD    (  463): Listening for incoming client connection request
,W/Settings( 1710): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/NativeCrypto( 1620): Read error: ssl=0xb8b9a308: I/O error during system call, Connection timed out
,V/NativeCrypto( 1620): SSL shutdown failed: ssl=0xb8b9a308: I/O error during system call, Broken pipe
,D/ConnectivityService(  887): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10016
,I/jxcore-log( 4863): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 4863): 
I/jxcore-log( 4863): The Coordinator has disconnected!
I/jxcore-log( 4863): 
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info<unknown ssid>
,I/LaunchCheckinHandler(  887): cleanup(): cleared. Last call was 15435 ms ago
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8063 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  887): connected time updated 449854
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  887): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  887): Unexpected BatchedScanResults :null
E/WifiStateMachine(  887): [1,449,216,837,657 ms] noteScanEnd no scan source
,D/WifiP2pService(  887): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pDisablingState
D/WifiP2pService(  887): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): p2p socket connection lost
D/WifiP2pService(  887): P2pDisabledState
,D/WifiScanningService(  887): SCAN_AVAILABLE : 1
,D/RttService(  887): SCAN_AVAILABLE : 1
D/WifiScanningService(  887): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  887): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/WB      ( 4863): Wifi is DISABLED !!
I/        ( 4863): Stoping All
I/        ( 4863): Stopping services
I/        ( 4863): Stopping services
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pDisabledState{ when=-1ms what=139298 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139298 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139307 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139307 arg2=69 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/UdcCache:FPQuery( 7359): Bootstrapping UDC settings cache for all accounts
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  887): NetworkAgent: NetworkAgent channel lost
,D/WifiP2pService(  887): P2pDisabledState{ when=-1ms what=139268 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139268 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4863): Stop Bluetooth
,I/        ( 4863): Stop Bluetooth
I/BTListenerThread( 4863): Stopped
I/SS      ( 4863): We got empty peers list
I/        ( 4863): Clearing local services failed, error code 2
I/        ( 4863): Clearing service requests failed, error code 2
I/        ( 4863): Stopping peer discovery failed, error code 2
,D/ConnectivityService(  887): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  887): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Disconnected - quitting
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  887): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  887): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/ModemStatsDSDetect( 1526): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524292
I/ModemStatsDSDetect( 1526): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1526): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1526): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1526): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1526): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/ResourcesManager( 8063): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4-SVC( 7359): Google Analytics 8.3.01 is starting up.
,I/Babel_SMS( 8063): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8063): MmsConfig.loadMmsSettings
I/Babel_SMS( 8063): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8063): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8063): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8063): MmsConfig.loadFromResources
,E/Babel_SMS( 8063): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8063): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/Tethering(  887): InitialState.processMessage what=4
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  463): NL - Read 68 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,W/Settings( 8063): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 8063): startup - clean
,I/Babel   ( 8063): deleted: false for 0
,D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
,D/TCMD    (  463): Listening for incoming client connection request
,W/VideoCapabilities( 8063): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8063): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8063): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8063): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8063): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8063): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8063): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8063): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  887): Killing 7878:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,D/TCMD    (  463): NL - Read 444 bytes from update socket.
,D/TCMD    (  463): NL - ignore NL message, type = 17
D/TCMD    (  463): Listening for incoming client connection request
,I/jxcore-log( 4863): 2015-12-04T08:13:58.134Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4863): 
,I/jxcore-log( 4863): 2015-12-04T08:13:58.134Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:13:58.134Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4863): 
I/jxcore-log( 4863): 2015-12-04T08:13:58.134Z SendDataConnector.js: do connect now
I/jxcore-log( 4863): 
D/AndroidRuntime( 4863): Shutting down VM
,D/TCMD    (  463): NL - Read 1004 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
,D/TCMD    (  463): Listening for incoming client connection request
,D/TCMD    (  463): NL - Read 444 bytes from update socket.
,D/TCMD    (  463): NL - ignore NL message, type = 17
D/TCMD    (  463): Listening for incoming client connection request
,W/libprocessgroup(  887): failed to open /acct/uid_10027/pid_7878/cgroup.procs: No such file or directory
,I/vclib   ( 8063): onServiceConnected
W/Babel   ( 8063): Attempted to change video mute state without an active call.
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 7690): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7690): Bluetooth Device Name: S5mini-1
,I/MDMCTBK (  303): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  303): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1457): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/OtaApp  ( 2550): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8114 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1457): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1457): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2550): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2550): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2550): Registering with Alarm Manager to restart CCE
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2550): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2550): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2550): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2550): [debug] > CusSM.onRadioDown
,I/MusicStore( 8114): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8114): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8114): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8114): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8114): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8114): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8114): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 8114): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8114): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d225af5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8114): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8114): GMSCore installation verified
,I/ConfigStore( 8114): Config Database version: 1
,I/MediaRouter( 8114): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8114): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8154 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8114): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8114): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 7897:com.android.vending/u0a32 (adj 15): empty #7
,V/Mms     ( 8154): mnc/mcc: 
,V/Mms     ( 8154): tag: int value: recipientLimit - 20
,V/Mms     ( 8154): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8154): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8154): tag: int value: maxSubjectLength - 80
V/Mms     ( 8154): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8154): tag: bool value: enableGroupMms - false
V/Mms     ( 8154):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_7897/cgroup.procs: No such file or directory
,W/ResourcesManager( 8154): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8181 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7851:android.process.acore/u0a7 (adj 15): empty #7
,D/PhoneMonitor( 8181): Register our PhoneStateListener
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_7851/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 8181): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8181): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 7359): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 7359): num queued entries: 0
,I/iu.UploadsManager( 7359): num updated entries: 0
,I/iu.SyncManager( 7359): NEXT; no task
,D/ChimeraCfgMgr( 7359): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  887): Killing 7950:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_7950/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8200 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8218 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 8063): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  887): Killing 7690:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_7690/cgroup.procs: No such file or directory
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8218): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8218): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 8218): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8218):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8218):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8218): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8218): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8218): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8218): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8218): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 8218): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8218): Time to load native libraries: 2 ms (timestamps 9423-9425)
,I/LibraryLoader( 8218): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8218): Binding Chromium to main looper Looper (main, tid 1) {1f781864}
,I/LibraryLoader( 8218): Expected native library version number "",actual native library version number ""
I/chromium( 8218): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8218): Initializing chromium process, singleProcess=true
,W/art     ( 8218): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8218): ApplicationContext is null in ApplicationStatus
,W/chromium( 8218): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8218): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 8218): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 8218): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8218): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8218): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8218): Local Branch: 
I/Adreno-EGL( 8218): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8218): Local Patches: NONE
I/Adreno-EGL( 8218): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 8218): Requires BLUETOOTH permission
,I/NSApplication( 8218): Starting up...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8274 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8114:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/WifiP2pService(  887): P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_8114/cgroup.procs: No such file or directory
,I/art     (  887): Explicit concurrent mark sweep GC freed 26004(1339KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.443ms total 126.863ms
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  887): ApnList is empty for checkDunConfigured()
,D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
D/Tethering(  887): sendTetherStateChangedBroadcast 1, 0, 0
,D/TCMD    (  463): NL - Read 1008 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/Tethering(  887): InitialState.processMessage what=4
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  463): NL - Read 1008 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/QsoftapCmd(  299): Got softap fwreload command we are passing on
,D/SoftapController(  299): Softap fwReload - Ok
,D/CommandListener(  299): Setting iface cfg
D/CommandListener(  299): Trying to bring down wlan0
,D/CommandListener(  299): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  887): setWifiState: enabling
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  887): Supplicant start successful
D/WifiMonitor(  887): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 8308): Successfully initialized wpa_supplicant
I/wpa_supplicant( 8308): Long line in configuration file truncated
I/wpa_supplicant( 8308): rfkill: Cannot open RFKILL control device
D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
,D/TCMD    (  463): Listening for incoming client connection request
,I/libmdmdetect( 8308): ESOC framework not supported
,E/Diag_Lib( 8308):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 8308): baseband property is set to [msm]
I/libmdmdetect( 8308): ESOC framework not supported
,E/wpa_supplicant( 8308):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8308): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8308): card_info[i].card_state: 0x0
E/wpa_supplicant( 8308): card_info[i].error_code: 0x0
E/wpa_supplicant( 8308): SIM/USIM not ready
E/wpa_supplicant( 8308): Error while reading SIM card status
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8311 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/wpa_supplicant( 8308): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8308): card_info[i].card_state: 0x0
E/wpa_supplicant( 8308): card_info[i].error_code: 0x0
E/wpa_supplicant( 8308): SIM/USIM not ready
I/wpa_supplicant( 8308): eap_proxy: Card not ready
I/ActivityManager(  887): Killing 8154:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_8154/cgroup.procs: No such file or directory
,W/ResourcesManager( 8311): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/wpa_supplicant( 8308): Long line in configuration file truncated
,I/wpa_supplicant( 8308): rfkill: Cannot open RFKILL control device
D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,E/wpa_supplicant( 8308): baseband property is set to [msm]
I/libmdmdetect( 8308): ESOC framework not supported
,E/wpa_supplicant( 8308):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8308): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8308): card_info[i].card_state: 0x0
E/wpa_supplicant( 8308): card_info[i].error_code: 0x0
E/wpa_supplicant( 8308): SIM/USIM not ready
E/wpa_supplicant( 8308): Error while reading SIM card status
,E/wpa_supplicant( 8308): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8308): card_info[i].card_state: 0x0
E/wpa_supplicant( 8308): card_info[i].error_code: 0x0
E/wpa_supplicant( 8308): SIM/USIM not ready
I/wpa_supplicant( 8308): eap_proxy: Card not ready
,E/WifiStateMachine(  887): Supplicant connection established
E/WifiStateMachine(  887): setWifiState: enabled
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/WifiConfigStore(  887): Loading config and enabling all networks 
,E/WifiConfigStore(  887):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  887):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  887): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  887): Setting external_sim to 1
W/Settings( 8063): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  887): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  887): startHal
E/wifi    (  887): getStaticLongField sWifiHalHandle 0xa2e3e89c
D/wifi    (  887): halHandle = 0x0, mVM = 0xb87b9310, mCls = 0x19ea
I/WifiNative-HAL(  887): Could not start hal
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/wpa_supplicant( 8308): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/native  (  887): do suspend true
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  299): Setting iface cfg
D/CommandListener(  299): Trying to bring up p2p0
D/WifiScanningService(  887): SCAN_AVAILABLE : 3
,D/WifiScanningService(  887): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiNative-HAL(  887): startHal
D/RttService(  887): SCAN_AVAILABLE : 3
D/RttService(  887): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor(  887): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  887): P2pEnablingState
D/WifiP2pService(  887): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2p socket connection successful
D/WifiP2pService(  887): P2pEnabledState
D/WifiP2pService(  887): sending p2p connection changed broadcast
,I/wpa_supplicant( 8308): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,E/wifi    (  887): getStaticLongField sWifiHalHandle 0xa49519cc
D/wifi    (  887): halHandle = 0x0, mVM = 0xb87b9310, mCls = 0x19e2
I/WifiNative-HAL(  887): Could not start hal
E/WifiScanningService(  887): could not start HAL
E/WifiStateMachine(  887): set country code US
,D/WifiNative-HAL(  887): p2pGetDeviceAddress
E/WifiStateMachine(  887): set frequency band 2
D/WifiNative-HAL(  887): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
D/WifiP2pService(  887): DeviceAddress: 44:80:eb:7b:5a:07
,I/wpa_supplicant( 8308): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiP2pService(  887): MCC mode enabled 0
I/MDMCTBK (  303): NetlinkHandler, wifiStateChanged 1
D/WifiP2pService(  887): mP2pAutoConnectSupport = 0
I/MDMCTBK (  303): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): wifi_connect_to_supplicant, current pid is = 303
D/MDMCTBK (  303): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  303): wifi_close_sockets: Exit
D/WifiP2pService(  887): sending p2p persistent groups changed broadcast
D/WifiP2pService(  887): InactiveState
E/MDMCTBK (  303): Attach monitor thread
,D/MDMCTBK (  303): wifi_ctrl_recv: Exiting
D/MDMCTBK (  303): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  303): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  303): wifi_close_sockets: Exit
I/MDMCTBK (  303): createWifiMonitorThread: Started the wifi monitor thread -1191538248
D/WifiP2pService(  887): InactiveState{ when=-6ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-7ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-7ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-7ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info0x
D/MDMCTBK (  303): wifi_wait_on_socket: Enter monitor thread
E/MDMCTBK (  303): Error: monitor connection not available
D/MDMCTBK (  303): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  303): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  303): wifi_close_sockets: Exit
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=8335 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8181:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,D/EmailService.MarketingOptInSetter( 2550): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/ActivityManager(  887): Killing 8200:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_8181/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_8200/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2550): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2550): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2550): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2550): onServiceConnected()
,D/GetNotificationsWS( 2550): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2550): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8359 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  325): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.613ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 19.574ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 420us total 21.058ms
,I/ContactLocale( 8335): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/MusicStore( 8359): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8359): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8359): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8359): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8359): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8359): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,V/JNIHelp ( 8359): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 8359): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8359): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d225af5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8359): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8359): GMSCore installation verified
,I/ConfigStore( 8359): Config Database version: 1
,I/MediaRouter( 8359): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8359): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8391 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8359): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8359): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 8063:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 8391): mnc/mcc: 
,V/Mms     ( 8391): tag: int value: recipientLimit - 20
,V/Mms     ( 8391): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 8391): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8391): tag: int value: maxSubjectLength - 80
V/Mms     ( 8391): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8391): tag: bool value: enableGroupMms - false
V/Mms     ( 8391):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledStateupdate channel list
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_8063/cgroup.procs: No such file or directory
,W/ResourcesManager( 8391): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8417 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8218:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 8417): Register our PhoneStateListener
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_8218/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 8417): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8417): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ChimeraCfgMgr( 7359): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  887): Killing 8274:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_8274/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8436 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8453 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8311:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_8311/cgroup.procs: No such file or directory
,W/ResourcesManager( 8453): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8453): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8453): MmsConfig.loadMmsSettings
I/Babel_SMS( 8453): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8453): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8453): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8453): MmsConfig.loadFromResources
,E/Babel_SMS( 8453): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8453): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,V/AlarmManager(  887): send {250dd487, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {1df8de38, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/wpa_supplicant( 8308): CTRL_IFACE: Detach monitor /data/misc/cutback/wpa_ctrl_303-6\x00 that cannot receive messages
,D/TCMD    (  463): NL - Read 56 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,E/WifiStateMachine(  887): [1,449,216,845,190 ms] noteScanEnd no scan source
,E/WifiStateMachine(  887): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@26ba4271 sup_state=SCANNING debouncing=false
E/WifiStateMachine(  887): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  887):  rewrite network history for "NG700"WPA_PSK
,V/AlarmManager(  887): done {250dd487, *alarm*:android.intent.action.TIME_TICK} [43ms]
,E/WifiStateMachine(  887): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  887): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,W/Settings( 8453): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8453): startup - clean
,I/Babel   ( 8453): deleted: false for 0
,E/WifiConfigStore(  887): will read network variables netId=0
,E/WifiStateMachine(  887): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  887): will read network variables netId=0
,I/wpa_supplicant( 8308): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  887): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 8308): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiConfigStore(  887): setLastSelectedConfiguration -1
,E/wpa_supplicant( 8308): PNO: In assoc process
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  887): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8490 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TCMD    (  463): NL - Read 312 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 192 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
,D/TCMD    (  463): Listening for incoming client connection request
,D/TCMD    (  463): NL - Read 68 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 1004 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/wpa_supplicant( 8308): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/TCMD    (  463): NL - Read 80 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 80 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
D/TCMD    (  463): NL - Read 68 bytes from update socket.
D/TCMD    (  463): NL - message type is RTM_NEWLINK
,D/TCMD    (  463): Listening for incoming client connection request
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info"NG700"
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
,D/Tethering(  887): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 8308): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 8308): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/TCMD    (  463): NL - Read 1004 bytes from update socket.
,D/TCMD    (  463): NL - message type is RTM_NEWLINK
D/TCMD    (  463): Listening for incoming client connection request
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  887): Network connection established
,E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  887): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  887): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  887): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  887): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 2
E/WifiStateMachine(  887): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  299): Setting iface cfg
,E/WifiStateMachine(  887): Start Dhcp Watchdog 3
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  887): do suspend false
,E/wpa_supplicant( 8308): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  887): Unexpected BatchedScanResults :null
E/wpa_supplicant( 8308): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  887): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3f194ae0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3f194ae0 target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 8453): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8453): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8453): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8453): Unsupported profile 4 for video/mp4v-es
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/VideoCapabilities( 8453): Unrecognized profile 2130706433 for video/avc
W/ContextImpl( 8490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/VideoCapabilities( 8453): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/VideoCapabilities( 8453): Unrecognized profile 2130706433 for video/avc
,I/GAv4    ( 8490): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8490):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8490):   adb logcat -s GAv4
,W/VideoCapabilities( 8453): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,I/vclib   ( 8453): onServiceConnected
,W/Babel   ( 8453): Attempted to change video mute state without an active call.
,W/ContextImpl( 8490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 8490): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 8453): connection state changed from UNKNOWN to DISCONNECTED
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,I/ActivityManager(  887): Killing 8335:android.process.acore/u0a7 (adj 15): empty #7
,W/ContextImpl( 8490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8490): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8490): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/DHCPCD  ( 8519): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 8519): version 5.5.6 starting
,E/DHCPCD  ( 8519): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 8519): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 8519): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_8335/cgroup.procs: No such file or directory
,W/ProcessCpuTracker(  887): Skipping unknown process pid 8526
,D/DHCPCD  ( 8519): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 8519): wlan0: rebinding lease of 192.168.1.134
D/DHCPCD  ( 8519): wlan0: sending REQUEST (xid 0xb0d60742), next in 4.50 seconds
,I/WebViewFactory( 8490): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8490): Time to load native libraries: 2 ms (timestamps 2884-2886)
I/LibraryLoader( 8490): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8490): Binding Chromium to main looper Looper (main, tid 1) {1f781864}
,I/LibraryLoader( 8490): Expected native library version number "",actual native library version number ""
,I/chromium( 8490): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8490): Initializing chromium process, singleProcess=true
,W/art     ( 8490): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8490): ApplicationContext is null in ApplicationStatus
,W/chromium( 8490): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8490): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 8490): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 8490): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8490): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8490): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8490): Local Branch: 
I/Adreno-EGL( 8490): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8490): Local Patches: NONE
I/Adreno-EGL( 8490): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 8490): Starting up...
,W/AudioManagerAndroid( 8490): Requires BLUETOOTH permission
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8567 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8359:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_8359/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8586 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8391:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_8391/cgroup.procs: No such file or directory
,W/ResourcesManager( 8586): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  887): Explicit concurrent mark sweep GC freed 37032(1868KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.678ms total 116.382ms
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=8606 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8417:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 8606): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_8417/cgroup.procs: No such file or directory
,V/AlarmManager(  887): done {1df8de38, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [1665ms]
,I/ActivityManager(  887): Killing 8453:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_8453/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8645 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 8645): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8645): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8645): MmsConfig.loadMmsSettings
I/Babel_SMS( 8645): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8645): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8645): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 8645): MmsConfig.loadFromResources
E/Babel_SMS( 8645): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8645): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8645): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8645): startup - clean
,I/Babel   ( 8645): deleted: false for 0
,W/VideoCapabilities( 8645): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8645): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 8645): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8645): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8645): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8645): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8645): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8645): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  887): Killing 8490:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_8490/cgroup.procs: No such file or directory
,I/vclib   ( 8645): onServiceConnected
,W/Babel   ( 8645): Attempted to change video mute state without an active call.
E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DHCPCD  ( 8519): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/DHCPCD  ( 8519): wlan0: leased 192.168.1.134 for 86400 seconds
,D/DHCPCD  ( 8519): wlan0: adding IP address 192.168.1.134/24
,D/DHCPCD  ( 8519): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 8519): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 8519): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/DHCPCD  ( 8519): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/TCMD    (  463): NL - Read 60 bytes from update socket.
D/TCMD    (  463): NL - ignore NL message, type = 20
D/TCMD    (  463): Listening for incoming client connection request
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  887): WifiStateMachine DHCP successful
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  887): Calling ARP set with IP = 192.168.1.134
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  887): Adding iface wlan0 to network 102
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  887): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  887): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  887): Adding Route [fe80::/64 -> :: wlan0] to network 102
,E/WifiStateMachine(  887): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  887): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
D/ConnectivityService(  887): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,D/ConnectivityService(  887): Setting Dns servers for network 102 to [/192.168.1.1]
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  887): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  887):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/CSLegacyTypeTracker(  887): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1526): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1526): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1526): onReceive() - done, currentInetCondition=0
,D/ConnectivityService(  887): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4680:ebff:fe7b:5a06/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Dec 2015 08:14:08 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449216848715], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449216848696]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Validated
D/ConnectivityService(  887): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  887): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
,D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524290
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1526): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1526): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1526): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1526): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): now: 718535 ,futureTime: 9223372036854775807
D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): now: 718535 ,futureTime: 9223372036854775807
D/PollingManager( 2550): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2550): now: 718536 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1457): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2550): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  887): MasterInitialState.processMessage what=3
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8734 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Central_PollingManager( 1457): now: 718614 ,futureTime: 86471933
D/Central_PollingManager( 1457): Polling alarm set to expire at: 86471933 Current Time: 718614
,D/OtaApp  ( 2550): [debug] > PollingManagerService, now: 718616 ,futureTime: 21558665
,D/OtaApp  ( 2550): [debug] > Polling alarm set to expire at: 21558665 Current Time: 718616
,D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2550): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2550): createDeviceIdOrLogin update_device
D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2550): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2550): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2550): createDeviceIdOrLogin update_device
D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2550): set mOutstandingReq to true.
I/ Nonce  ( 2550):  Nonce getNonce 
,I/ Nonce  ( 2550):  Nonce Request 
I/ Nonce  ( 2550):  Nonce execute Request 
,D/MMApiWebService( 2550): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2550): isDeviceProvisioned: deviceId = 2072049230914535424
,I/MusicStore( 8734): Database version: 120
,D/CCE     ( 2550): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2550): createDeviceIdOrLogin update_device
D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2550): Not proxy app, so login/provision not allowed
D/OtaApp  ( 2550): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2550): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2550): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2550): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2550): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2550): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWebService( 2550): generating token using payload instead of using session token
,D/ Nonce  ( 2550):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8734): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/MMApiWSBase( 2550): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8734): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8734): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8734): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8734): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8734): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 8734): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8734): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d225af5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8734): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8734): GMSCore installation verified
,I/ConfigStore( 8734): Config Database version: 1
,I/MediaRouter( 8734): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8734): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 8734): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 8734): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8775 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  325): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.916ms
,I/GHttpClientFactory( 8734): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8734): Using platform SSLCertificateSocketFactory
I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.358ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 20.365ms
,I/ActivityManager(  887): Killing 7359:com.google.android.gms/u0a16 (adj 15): empty #7
,V/Mms     ( 8775): mnc/mcc: 
V/Mms     ( 8775): tag: int value: recipientLimit - 20
V/Mms     ( 8775): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8775): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8775): tag: int value: maxSubjectLength - 80
V/Mms     ( 8775): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8775): tag: bool value: enableGroupMms - false
V/Mms     ( 8775):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/WifiService(  887): Client connection lost with reason: 4
,I/art     ( 1620): Explicit concurrent mark sweep GC freed 8385(479KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 11MB/15MB, paused 1.557ms total 74.685ms
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_7359/cgroup.procs: No such file or directory
,I/art     (  887): Explicit concurrent mark sweep GC freed 18983(933KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.513ms total 115.038ms
,I/ActivityManager(  887): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=8804 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8775): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8822 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,W/ResourcesManager( 8804): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8804): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Killing 8567:com.android.chrome/u0a52 (adj 15): empty #7
,D/PhoneMonitor( 8822): Register our PhoneStateListener
,I/MultiDex( 8804): VM with version 2.1.0 has multidex support
,I/MultiDex( 8804): install
I/MultiDex( 8804): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_8567/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 8822): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8822): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  887): Killing 8586:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_8586/cgroup.procs: No such file or directory
,I/ Nonce  ( 2550):  Nonce Reponse 
D/        ( 2550): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"b7a442f5-ada1-4c4e-b979-16e063a0c292"}
D/MMApiWSBase( 2550): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2550):  Nonce Handle Reponse 
D/MMApiProvisionService( 2550): mOutstandingReq set to false
,V/JNIHelp ( 8804): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/art     ( 1457): Explicit concurrent mark sweep GC freed 4996(232KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 7MB/12MB, paused 618us total 30.511ms
,W/ActivityThread( 8804): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8804): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30282fe8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8804): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  887): Killing 8606:android.process.acore/u0a7 (adj 15): empty #7
,D/MMApiProvisionService( 2550):  pTime 1449056434640 sExp 172742 cTime 1449216852914 tTime 1449229176640
,D/MMApiProvisionService( 2550):  No login Required 
,D/NativeLibraryUtils( 8804): Install completed successfully. count=13 extracted=0
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_8606/cgroup.procs: No such file or directory
,I/CheckinService( 8804): Checkin interval check for package: unspecified last checkin: 1449216814750 min interval config: 0 actual interval: 38398
,I/CheckinService( 8804): Disabling old GoogleServicesFramework version
,I/CheckinService( 8804): Checking schedule, now: 1449216853181 next: 1449216844722
I/CheckinService( 8804): active receiver: enabled
,I/CheckinService( 8804): Preparing to send checkin request
,I/EventLogService( 8804): Accumulating logs since 1449216811166
,I/iu.SyncManager( 8804): SYNC; picasa accounts
,D/NetworkLogImpl( 8804): Loaded NetworkSpeedPredictor
,I/iu.Environment( 8804): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/art     ( 8804): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/iu.UploadsManager( 8804): num queued entries: 0
,I/art     ( 8804): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/iu.UploadsManager( 8804): num updated entries: 0
,I/iu.SyncManager( 8804): NEXT; no task
,D/ChimeraCfgMgr( 8804): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 8804): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/DataUsage( 2550): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2550): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8871 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 8645): connection state changed from UNKNOWN to CONNECTED
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8871): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/CheckinRequestBuilder( 8804): Checkin reason type: 8 attempt count: 1
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8871): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/WifiService(  887): New client listening to asynchronous messages
,E/ActivityThread( 8804): Failed to find provider info for com.google.android.wearable.settings
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8871): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
I/GAv4    ( 8871): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8871):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8871):   adb logcat -s GAv4
,W/ContextImpl( 8871): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8871): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8871): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8871): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  887): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8925 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8925): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8925): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8925): VM with version 2.1.0 has multidex support
I/MultiDex( 8925): install
I/MultiDex( 8925): VM has multidex support, MultiDex support library is disabled.
,I/WebViewFactory( 8871): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8871): Time to load native libraries: 1 ms (timestamps 801-802)
,I/LibraryLoader( 8871): Expected native library version number "",actual native library version number ""
,V/JNIHelp ( 8925): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,V/WebViewChromiumFactoryProvider( 8871): Binding Chromium to main looper Looper (main, tid 1) {32123f82}
,I/LibraryLoader( 8871): Expected native library version number "",actual native library version number ""
I/chromium( 8871): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8871): Initializing chromium process, singleProcess=true
,W/art     ( 8871): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8871): ApplicationContext is null in ApplicationStatus
,W/chromium( 8871): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 8871): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8871): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 8871): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8871): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8871): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8871): Local Branch: 
I/Adreno-EGL( 8871): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8871): Local Patches: NONE
I/Adreno-EGL( 8871): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityThread( 8925): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8925): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6c2bdd2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8925): Installed default security provider GmsCore_OpenSSL
,I/art     ( 8925): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 8925): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,W/AudioManagerAndroid( 8871): Requires BLUETOOTH permission
,I/NSApplication( 8871): Starting up...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8964 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 8925): Install completed successfully. count=13 extracted=0
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
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e68000
E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e68000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb4ffb960
D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb835a610, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb82198a8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb8364790, idLength=0xb55a1730
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
D/WVCdm   (  308): PrepareKeyRequest: nonce=2645619249
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8318ee8
D/DrmWidevineDash(  308): message_length=1591, signature=0xb82940a8, signature_length=3042580244
,I/art     (  887): Explicit concurrent mark sweep GC freed 10691(516KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.565ms total 111.649ms
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8991 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8734:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  308): CdmEngine::CloseSession
,D/DrmWidevineDash(  308): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  308): L3 Terminate.
D/DrmWidevineDash(  308): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  308): Service_Uninitialize: starts!
D/QSEECOMAPI: (  308): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  308): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  308): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_8734/cgroup.procs: No such file or directory
,W/ResourcesManager( 8991): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/dex2oat ( 9011): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9021 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/dex2oat ( 9011): dex2oat took 61.527ms (threads: 4)
,I/ActivityManager(  887): Killing 8775:com.android.mms/u0a23 (adj 15): empty #7
,I/Adreno-EGL( 8925): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8925): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8925): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8925): Local Branch: 
I/Adreno-EGL( 8925): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8925): Local Patches: NONE
I/Adreno-EGL( 8925): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8925): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8925): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8925): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8925): Local Branch: 
I/Adreno-EGL( 8925): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8925): Local Patches: NONE
I/Adreno-EGL( 8925): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/EmailService.MarketingOptInSetter( 2550): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/ActivityManager(  887): Killing 8822:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_8775/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_8822/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2550): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2550): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2550): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2550): onServiceConnected()
D/GetNotificationsWS( 2550): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2550): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2550): started with background data enabled, making sure notification mechanism is enabled
D/OtaApp  ( 2550): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2550): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2550): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  887): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1457): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2550): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2550): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2550): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2550): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/WearableService( 1710): callingUid 10016, callindPid: 1710
,E/MDM     ( 1710): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/Adreno-EGL( 8925): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8925): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8925): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8925): Local Branch: 
I/Adreno-EGL( 8925): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8925): Local Patches: NONE
I/Adreno-EGL( 8925): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/OtaApp  ( 2550): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2550): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2550): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2550): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2550): publish the event [tag = MOT_OTA event name = LOG]
,I/Adreno-EGL( 8925): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8925): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8925): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8925): Local Branch: 
I/Adreno-EGL( 8925): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8925): Local Patches: NONE
I/Adreno-EGL( 8925): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/InstanceID/Rpc( 8804): Found 10016
,D/GCM     ( 1620): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/LocationInitializer( 8804): Restart initialization of location
,D/AuthorizationBluetoothService( 1620): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 8804): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/GCoreFlp( 1710): No location to return for getLastLocation()
,W/FusedLocationProvider( 1620): location=null
,I/WVCdm   (  308): CdmEngine::OpenSession
I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/ContactLocale( 9021): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  308): Service_Initialize: starts!
,D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,E/MDM     ( 1710): [158] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e68000
E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e68000
,D/GCM     ( 1620): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1620): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 8804): Restart initialization of location
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb55a1960
D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb835a6e8, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb82198a8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb83647d0, idLength=0xb4ffb730
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/WVCdm   (  308): PrepareKeyRequest: nonce=1170236991
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8318ee8
,D/DrmWidevineDash(  308): message_length=1626, signature=0xb82940a8, signature_length=3036657428
,V/GmsCoreStatsServiceLauncher( 8804): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/art     ( 1620): Explicit concurrent mark sweep GC freed 8980(540KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 11MB/15MB, paused 840us total 68.631ms
,W/GCoreFlp( 1710): No location to return for getLastLocation()
W/FusedLocationProvider( 1620): location=null
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  308): CdmEngine::CloseSession
,D/DrmWidevineDash(  308): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  308): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  308): L3 Terminate.
D/DrmWidevineDash(  308): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  308): Service_Uninitialize: starts!
D/QSEECOMAPI: (  308): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  308): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  308): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 8804): Classify the device as Phone.
,I/CheckinTask( 8804): Sending checkin request (9428 bytes)
,I/CheckinRequestBuilder( 8804): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 8804): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 8804): Classify the device as Phone.
,I/CheckinTask( 8804): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 8804): Checking schedule, now: 1449216857066 next: 1449817994044
I/CheckinService( 8804): active receiver: disabled
,D/CheckinService( 8804): Recording last checkin time for package unspecified as 1449216857079
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=9087 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 9087): Register our PhoneStateListener
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=292, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311473, SEQNUM=4771, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-16125, POWER_SUPPLY_CHARGE_COUNTER=-1967, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,V/SetupWizard( 9087): Connected to Gservices successfully
,I/ActivityManager(  887): Killing 8871:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_8871/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,D/ChimeraCfgMgr( 8804): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 8804): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,D/GCM     ( 1620): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  887): Killing 8991:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  887): Killing 8964:com.android.chrome/u0a52 (adj 15): empty #8
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_8991/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_8964/cgroup.procs: No such file or directory
,I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=9111 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  887): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  887): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@35d3d60
,V/GmsNetworkLocationProvi( 1710): DISABLE
,I/GCoreNlp( 1710): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1544): Deferring update until onResume
,I/art     (  887): Explicit concurrent mark sweep GC freed 19877(970KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.538ms total 116.486ms
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=9152 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=9171 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 22.016ms
,I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.098ms
,W/ResourcesManager( 8645): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8645): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/asset   ( 9171): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 9171): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 9171): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9171): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 20.092ms
,V/JNIHelp ( 8645): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=9199 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/System  ( 8645): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8645): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  887): Killing 8436:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_8436/cgroup.procs: No such file or directory
,D/Finsky  ( 9199): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 9199): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 9199): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 9199): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 9199): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 9199): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 9199): Skipping gmscore version check
,D/Finsky  ( 9199): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/Launcher( 1544): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3154b new=com.google.android.velvet.VelvetApplication@3154b
,I/UpdateIcingCorporaServi( 9111): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/Finsky  ( 9199): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 8804): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=9246 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 8804): Null package name or gms related package.  Ignoreing.
,W/ResourcesManager( 9246): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 9111): UpdateCorporaTask done [took 142 ms] updated apps [took 142 ms] 
,I/ActivityManager(  887): Killing 9087:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/Icing   ( 8804): Storage manager: low false usage 1.69MB avail 2.69GB capacity 4.12GB
,W/Icing   ( 8804): Received bad json for section weights override -- ignoring.
,W/Icing   ( 8804): Received bad json for corpus context scoring override -- ignoring.
,W/Icing   ( 8804): Received bad json for section weights override -- ignoring.
W/Icing   ( 8804): Received bad json for corpus context scoring override -- ignoring.
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_9087/cgroup.procs: No such file or directory
,I/Icing   ( 8804): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  887): Killing 8925:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_8925/cgroup.procs: No such file or directory
,I/Icing   ( 8804): Internal init done: storage state 0
,I/Icing   ( 8804): Post-init done
,I/Icing   ( 8804): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  887): Killing 9152:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_9152/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 8645:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_8645/cgroup.procs: No such file or directory
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:32000 mC
,I/CheckinService( 8804): Done disabling old GoogleServicesFramework version
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,W/SQLiteConnectionPool( 8804): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311837, SEQNUM=4781, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5308, POWER_SUPPLY_CHARGE_COUNTER=-2036, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312032, SEQNUM=4783, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11818, POWER_SUPPLY_CHARGE_COUNTER=-2092, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  887): send {250dd487, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {3dd30bab, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/LaunchCheckinHandler(  887): cleanup(): cleared. Last call was 36614 ms ago
I/ActivityManager(  887): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=9284 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  887): done {250dd487, *alarm*:android.intent.action.TIME_TICK} [95ms]
,I/GAv4    ( 9284): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9284):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9284):   adb logcat -s GAv4
,W/GAv4    ( 9284): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9284): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9284): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  887): done {3dd30bab, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [195ms]
I/ActivityManager(  887): Killing 9171:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10027/pid_9171/cgroup.procs: No such file or directory
,I/MDMCTBK (  303): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  303): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  303): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
,I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  303): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
,I/MDMCTBK (  303): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback, No Wifi
,I/MDMCTBK (  303): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
E/MDMCTBK (  303): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  303): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  303): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  303): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  303): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  303): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  303): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  303): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
E/MDMCTBK (  303): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  303): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  303): NetlinkHandler, interfaceAdded
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
E/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  303): , Wifi = 0
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  303): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
E/MDMCTBK (  303): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  303): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  303): NetlinkHandler, interfaceAdded
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
,I/MDMCTBK (  303): checkDefaultInst, pid match
E/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  303): , Wifi = 0
I/MDMCTBK (  303): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
,I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
,I/MDMCTBK (  303): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  303): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  303): set_property_value, Enter
I/MDMCTBK (  303): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  303): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  303): set_property_value, Exit
E/MDMCTBK (  303): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  887): send {3f0efa66, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  887): done {3f0efa66, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [13ms]
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
,I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
,I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
,I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/ClearcutLoggerApiImpl( 1620): disconnect managed GoogleApiClient
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [34:fc:ef:11:b1:66]: 6, f, 410d
,D/BluetoothManagerService(  887): Message: 20
,D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ca6bda1:true
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: Nexus 5
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: Nexus 5
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [34:fc:ef:11:b1:66]: 7, 1d, 7d3
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: Nexus 5
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 4921): info:x10
D/        ( 4921): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4921): tBTM_SEC_DEV:0xa6f72f9c rs_disc_pending=1
,W/bt-btif ( 4921): bta_dm_check_av:0
,W/bt-btif ( 4921): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: Nexus 5
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [80:01:84:8a:b3:68]: 6, f, 6109
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311302, SEQNUM=4793, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-2741, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4921): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  887): User[0] Flushing usage stats to disk
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 6109
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: S5-1
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: S5-1
,I/art     ( 4921): Explicit concurrent mark sweep GC freed 68868(2MB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 7MB/13MB, paused 1.053ms total 78.899ms
,I/art     (  887): Explicit concurrent mark sweep GC freed 14879(821KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 20MB/30MB, paused 1.471ms total 117.145ms
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: S5-1
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: S5-1
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: S5-1
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: S5-1
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: S5-1
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: S5-1
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 4921): info:x10
,D/        ( 4921): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: S5-1
,D/btif_config_util( 4921): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4921): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4921): onReceive
,I/BTConnectionReceiver( 9111): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9111): Bluetooth Device Name: S5-1
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310934, SEQNUM=4799, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-3597, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  887): send {250dd487, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {3f9ee84c, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  887): done {3f9ee84c, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [18ms]
,V/AlarmManager(  887): done {250dd487, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311505, SEQNUM=4800, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-61, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 4921): Disconnected process message: 10, size: 0
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  887): send {3f0efa66, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  887): send {250dd487, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {f4ce5d3, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,I/ProcessStatsService(  887): Prepared write state in 10ms
,V/AlarmManager(  887): send {1bdf15aa, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
V/AlarmManager(  887): send {212359b, *walarm*:com.google.android.intent.action.MCS_HEARTBEAT}
V/AlarmManager(  887): send {3ef83d38, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
V/AlarmManager(  887): send {3a95111, *alarm*:com.google.android.gms/.common.download.DownloadAlarmReceiver}
,V/AlarmManager(  887): done {3f0efa66, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [51ms]
,I/ProcessStatsService(  887): Prepared write state in 12ms
,V/AlarmManager(  887): done {f4ce5d3, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [82ms]
,V/AlarmManager(  887): done {250dd487, *alarm*:android.intent.action.TIME_TICK} [104ms]
,V/AlarmManager(  887): done {1bdf15aa, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [119ms]
,V/AlarmManager(  887): done {212359b, *walarm*:com.google.android.intent.action.MCS_HEARTBEAT} [132ms]
,V/AlarmManager(  887): done {3ef83d38, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [142ms]
,V/AlarmManager(  887): done {3a95111, *alarm*:com.google.android.gms/.common.download.DownloadAlarmReceiver} [151ms]
,I/EventLogService( 8804): Aggregate from 1449216853479 (log), 1449215947711 (data)
,D/UdcCache:FPQuery( 8804): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1620): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4-SVC( 8804): Google Analytics 8.3.01 is starting up.
,I/ProcessStatsService(  887): Pruning old procstats: /data/system/procstats/state-2015-12-03-04-07-15.bin
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 9421): 
D/AndroidRuntime( 9421): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 9421): CheckJNI is OFF
D/AndroidRuntime( 9421): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  887): Force stopping com.test.thalitest appid=10350 user=-1: uninstall pkg
I/ActivityManager(  887): Killing 4863:com.test.thalitest/u0a350 (adj 9): stop com.test.thalitest
W/PackageSettings(  887): Skipping PackageSetting{249c1606 com.example.hello/10343} due to missing metadata
I/WindowState(  887): WIN DEATH: Window{8e35e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  887): Client connection lost with reason: 4
I/ActivityManager(  887):   Force finishing activity ActivityRecord{f7ebe5d u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  887): Spurious death for ProcessRecord{21a5880 4863:com.test.thalitest/u0a350}, curProc for 4863: null
I/ActivityManager(  887): Force stopping com.test.thalitest appid=10350 user=0: pkg removed
I/art     ( 2956): Explicit concurrent mark sweep GC freed 26615(3MB) AllocSpace objects, 33(528KB) LOS objects, 39% free, 7MB/12MB, paused 890us total 49.713ms
W/GeofencerStateMachine( 1710): Ignoring removeGeofence because network location is disabled.
I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
D/VoicemailCleanupService( 9021): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator( 1406): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1406): run()
I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=9451 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 1544): Explicit concurrent mark sweep GC freed 8351(582KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 476us total 114.871ms
I/Decoder ( 1406): createOrResetDecoder
I/ConfigService( 1620): onCreate
I/art     (  887): Explicit concurrent mark sweep GC freed 18621(1248KB) AllocSpace objects, 6(179KB) LOS objects, 33% free, 20MB/30MB, paused 1.848ms total 171.911ms
I/art     (  887): WaitForGcToComplete blocked for 80.641ms for cause Explicit
W/asset   ( 9451): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 9451): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 9451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9451): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = contacts
D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  887): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = user
I/ActivityManager(  887): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=9476 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1406): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1406): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1406): run()
I/StatsUtilsManager( 1406): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1406): shouldRecordStats() = Too Soon
D/TaskPersister(  887): removeObsoleteFile: deleting file=3_task.xml
I/ActivityManager(  887): Killing 9199:com.android.vending/u0a32 (adj 15): empty #7
I/art     (  887): Explicit concurrent mark sweep GC freed 4897(277KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 7.533ms total 212.126ms
W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_9199/cgroup.procs: No such file or directory
W/ContextImpl( 9476): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=9495 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 9246:com.google.android.apps.plus/u0a90 (adj 15): empty #7
D/AndroidRuntime( 9421): Shutting down VM
I/Launcher( 1544): Deferring update until onResume
W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_9246/cgroup.procs: No such file or directory
D/Finsky  ( 9495): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/Finsky  ( 9495): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 9495): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 9495): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/Ads     ( 9495): Skipping gmscore version check
D/Finsky  ( 9495): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 9495): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 9495): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/Launcher( 1544): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3154b new=com.google.android.velvet.VelvetApplication@3154b
E/SQLiteLog( 1544): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
D/PackageBroadcastService( 8804): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/UpdateIcingCorporaServi( 9111): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/ChimeraCfgMgr( 8804): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 8804): Loading module APK com.google.android.play.games
D/AccountUtils( 8804): Clearing selected account for com.test.thalitest
D/Finsky  ( 9495): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/SQLiteLog( 9111): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/LocationSettingsChecker( 8804): Removing dialog suppression flag for package com.test.thalitest
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
