#### Test 506502789252e15_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,V/AlarmManager(  881): send {1ef76342, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {284a33ba, *walarm*:com.google.android.intent.action.SEND_IDLE}
V/AlarmManager(  881): done {284a33ba, *walarm*:com.google.android.intent.action.SEND_IDLE} [14ms]
V/AlarmManager(  881): done {1ef76342, *alarm*:android.intent.action.TIME_TICK} [42ms]
--------- beginning of main
D/AndroidRuntime( 5125): 
D/AndroidRuntime( 5125): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5125): CheckJNI is OFF
D/AndroidRuntime( 5125): Calling main entry com.android.commands.am.Am
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5144 uid=10372 gids={50372, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5125): Shutting down VM
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
E/global frequency( 2518): no tags to log
D/Checkin ( 2518): publish the event [tag = MOT_CHECKIN event name = LOG]
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/BSUtils ( 2518): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/BSUtils ( 2518): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2518): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 51718(2MB) AllocSpace objects, 34(1115KB) LOS objects, 39% free, 7MB/12MB, paused 5.399ms total 50.826ms
,D/BSUtils ( 2518): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/WebViewFactory( 5144): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/BSUtils ( 2518): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2518): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2518): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/LibraryLoader( 5144): Time to load native libraries: 4 ms (timestamps 6397-6401)
I/LibraryLoader( 5144): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5144): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
,I/LibraryLoader( 5144): Expected native library version number "",actual native library version number ""
,I/chromium( 5144): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/BrowserStartupController( 5144): Initializing chromium process, singleProcess=true
,W/art     ( 5144): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5144): ApplicationContext is null in ApplicationStatus
,D/BSUtils ( 2518): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,W/chromium( 5144): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,I/BSUtils ( 2518): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/chromium( 5144): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/BSUtils ( 2518): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,E/libEGL  ( 5144): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5144): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5144): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5144): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5144): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5144): Local Branch: 
I/Adreno-EGL( 5144): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5144): Local Patches: NONE
I/Adreno-EGL( 5144): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/global frequency( 2518): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2518): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2518): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2518): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2518): publish the event [tag = DEV_ATTRIBS event name = SW]
,W/ActivityManager(  881): Activity pause timeout for ActivityRecord{3f36e26b u0 com.test.thalitest/.MainActivity t3}
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b7ab955:true
,D/BluetoothAdapter( 5144): 446216149: getState() :  mService = null. Returning STATE_OFF
,I/global frequency( 2518): BcsDSCheckin.events found events 119
,D/Checkin ( 2518): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/art     (  881): Explicit concurrent mark sweep GC freed 10522(592KB) AllocSpace objects, 2(191KB) LOS objects, 33% free, 19MB/29MB, paused 1.374ms total 126.010ms
,I/BSUtils ( 2518): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
W/art     ( 5144): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5144): onDetachedFromWindow called when already detached. Ignoring
,D/MMApiWebService( 2518): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/SystemWebViewEngine( 5144): CordovaWebView is running on device made by: motorola
,W/art     ( 5144): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5144): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 4148(173KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 519us total 33.082ms
,D/OpenGLRenderer( 5144): Render dirty regions requested: true
,D/Atlas   ( 5144): Validating map...
,W/chromium( 5144): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     ( 2518): Explicit concurrent mark sweep GC freed 13902(845KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 11MB/18MB, paused 984us total 89.222ms
,I/OpenGLRenderer( 5144): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5144): Enabling debug mode 0
,D/MMApiWebService( 2518): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2518): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,I/Keyboard.Facilitator( 1405): onFinishInput()
,D/Checkin ( 2518): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2518): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2518): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2518): unknown error code mapping for: 0
I/global frequency( 2518): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2518): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2518): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2518): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,1065
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +978ms (total +1s65ms)
,W/IInputConnectionWrapper( 5144): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5144): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 5144): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5144): Cannot call determinedVisibility() - never saw a connection for the pid: 5144
,D/JsMessageQueue( 5144): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5144): JniHelper::setJavaVM(0xb843e310), pthread_self() = -1199778816
D/JX-Cordova( 5144): jxcore cordova android initializing
,W/jxcore-log( 5144): Initializing JXcore engine
W/jxcore-log( 5144): JXcore engine is ready
,W/jxcore-log( 5144): Starting JXcore engine
,W/.test.thalitest( 5144): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10372 path="socket:[7301]" dev="sockfs" ino=7301 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5144): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10372 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5144): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10372 path="socket:[7418]" dev="sockfs" ino=7418 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5144): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10372 path="socket:[22737]" dev="sockfs" ino=22737 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5144): Platform android
W/jxcore-log( 5144): 
W/jxcore-log( 5144): Process ARCH arm
W/jxcore-log( 5144): 
,I/jxcore-log( 5144): JXcore Cordova bridge is ready!
I/jxcore-log( 5144): 
W/jxcore-log( 5144): JXcore engine is started
I/Choreographer( 5144): Skipped 166 frames!  The application may be doing too much work on its main thread.
I/chromium( 5144): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5144): Toggling radios to true
I/jxcore-log( 5144): 
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  881): enable():  mBluetooth =null mBinding = false
,W/Settings( 1464): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  881): Message: 1
D/BluetoothManagerService(  881): MESSAGE_ENABLE: mBluetooth = null
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiService(  881): New client listening to asynchronous messages
D/WifiService(  881): setWifiEnabled: true pid=5144, uid=10372
,E/WifiService(  881): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine(  881): setting operational mode to 1
,I/ActivityManager(  881): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5205 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,W/Settings( 1464): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/jxcore-log( 5144): Radios toggled
I/jxcore-log( 5144): 
W/Settings( 1464): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
W/Settings( 1464): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/ResourcesManager( 5205): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 5205): Adding HeadsetService
D/AdapterServiceConfig( 5205): Adding A2dpService
D/AdapterServiceConfig( 5205): Adding HidService
D/AdapterServiceConfig( 5205): Adding HealthService
D/AdapterServiceConfig( 5205): Adding PanService
D/AdapterServiceConfig( 5205): Adding GattService
D/AdapterServiceConfig( 5205): Adding BluetoothMapService
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b685fc3:true
,D/BluetoothAdapterState( 5205): make
,I/bluedroid( 5205): init
,I/BluetoothAdapterState( 5205): Entering OffState
,I/bte_conf( 5205): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5205): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5205): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5205): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 5205): get_profile_interface socket
I/bluedroid( 5205): get_profile_interface map_client
,I/GKI_LINUX( 5205): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 5205): Address is:44:80:EB:7B:5A:05
,D/BluetoothAdapterProperties( 5205): Name is: XT1072
D/BluetoothManagerService(  881): Bluetooth Adapter name changed to XT1072
,D/BluetoothManagerService(  881): Stored Bluetooth name: XT1072
,D/BluetoothManagerService(  881): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  881): Message: 40
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 5205): config_hci_snoop_log
,D/BluetoothManagerService(  881): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  881): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 5205): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 5205): Setting state to 11
I/BluetoothAdapterState( 5205): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  881): Message: 60
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  881): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 5205): make
,I/BluetoothBondStateMachine( 5205): StableState(): Entering Off State
,I/ActivityManager(  881): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5247 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TCMD    (  479): NL - Read 1008 bytes from update socket.
,D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/TCMD    (  479): NL - Read 1008 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/Tethering(  881): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  0
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
,D/Tethering(  881): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering(  881): InitialState.processMessage what=4
,D/Tethering(  881): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
,D/Tethering(  881):  0
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
,D/Tethering(  881): sendTetherStateChangedBroadcast 0, 0, 0
,D/QsoftapCmd(  290): Got softap fwreload command we are passing on
,D/SoftapController(  290): Softap fwReload - Ok
,D/BluetoothHeadset(  881): Proxy object connected
,D/BluetoothHeadset( 1538): Proxy object connected
D/BluetoothHeadset( 1502): Proxy object connected
,D/HeadsetService( 5205): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 5205): classInitNative: succeeds
,D/HeadsetStateMachine( 5205): make
,D/BluetoothHeadset( 1502): Proxy object connected
,I/BluetoothAdapterState( 5205): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 5205): max_hf_connections = 1
I/bluedroid( 5205): get_profile_interface handsfree
,D/HeadsetStateMachine( 5205): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,D/BluetoothA2dp(  881): Proxy object connected
,D/A2dpService( 5205): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 5205): classInitNative: succeeds
,I/bluedroid( 5205): get_profile_interface avrcp
,D/CommandListener(  290): Setting iface cfg
D/CommandListener(  290): Trying to bring down wlan0
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  881): setWifiState: enabling
,E/RemoteController( 5205): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 5205): classInitNative: succeeds
D/A2dpStateMachine( 5205): make
D/Checkin ( 2914): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2914): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,E/WifiStateMachine(  881): Supplicant start successful
D/WifiMonitor(  881): startMonitoring(wlan0) with mConnected = false
I/bluedroid( 5205): get_profile_interface a2dp
I/GKI_LINUX( 5205): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/BluetoothHidServiceJni( 5205): classInitNative: succeeds
,D/A2dpStateMachine( 5205): Enter Disconnected: -2
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/HidService( 5205): Received start request. Starting profile...
,I/bluedroid( 5205): get_profile_interface hidhost
D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
I/BluetoothHealthServiceJni( 5205): classInitNative: succeeds
,D/HealthService( 5205): Received start request. Starting profile...
,I/bluedroid( 5205): get_profile_interface health
D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,I/BluetoothPanServiceJni( 5205): classInitNative(L105): succeeds
,W/ResourcesManager( 5247): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PanService( 5205): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5205): initializeNative(L110): pan
I/bluedroid( 5205): get_profile_interface pan
,D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,I/BtGatt.JNI( 5205): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 5205): handleDebugAction() action=null
,D/BtGatt.GattService( 5205): Received start request. Starting profile...
D/BtGatt.GattService( 5205): start()
I/bluedroid( 5205): get_profile_interface gatt
D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
D/BtGatt.AdvertiseManager( 5205): advertise manager created
,D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,D/BluetoothMapService( 5205): Received start request. Starting profile...
D/BluetoothMapService( 5205): start()
,D/BluetoothMapEmailSettingsLoader( 5205): Found 0 applications
D/BluetoothMapEmailAppObserver( 5205): createReceiver()
,D/BluetoothMapEmailAppObserver( 5205): initObservers()
,D/BluetoothMapEmailAppObserver( 5205): getEnabledAccountItems()
,I/wpa_supplicant( 5269): Successfully initialized wpa_supplicant
I/wpa_supplicant( 5269): Long line in configuration file truncated
,D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
I/wpa_supplicant( 5269): rfkill: Cannot open RFKILL control device
D/HeadsetStateMachine( 5205): Proxy object connected
,D/TCMD    (  479): NL - Read 1004 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/HeadsetStateMachine( 5205): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 5205): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterState( 5205): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5205): enable
D/TCMD    (  479): NL - Read 1004 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/HeadsetStateMachine( 5205): Disconnected process message: 11, size: 0
,I/bt_hci_bdroid( 5205): init
I/GKI_LINUX( 5205): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 5205): btu_task pending for preload complete event
I/bt_vendor( 5205): bt-vendor : init
D/bt_userial_mct( 5205): userial_init
I/bt_hwcfg( 5205): Starting hciattach daemon
I/bt_hwcfg( 5205): try to set false
I/bt_hwcfg( 5205): Starting hciattach daemon
I/bt_hwcfg( 5205): try to set true
,I/qcom-bluetooth( 5282): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/ActivityManager(  881): Killing 4847:android.process.acore/u0a7 (adj 15): empty #7
,I/libmdmdetect( 5269): ESOC framework not supported
E/Diag_Lib( 5269):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 5269): baseband property is set to [msm]
I/libmdmdetect( 5269): ESOC framework not supported
,E/wpa_supplicant( 5269):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5269): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5269): card_info[i].card_state: 0x0
E/wpa_supplicant( 5269): card_info[i].error_code: 0x0
E/wpa_supplicant( 5269): SIM/USIM not ready
E/wpa_supplicant( 5269): Error while reading SIM card status
,E/wpa_supplicant( 5269): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5269): card_info[i].card_state: 0x0
E/wpa_supplicant( 5269): card_info[i].error_code: 0x0
E/wpa_supplicant( 5269): SIM/USIM not ready
I/wpa_supplicant( 5269): eap_proxy: Card not ready
,I/qcom-bluetooth( 5289): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 5290): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 5292): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5293): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 5294): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/wpa_supplicant( 5269): Line 31: unknown global field 'e'.
,E/wpa_supplicant( 5269): Line 31: Invalid configuration line 'e'.
I/wpa_supplicant( 5269): rfkill: Cannot open RFKILL control device
,D/TCMD    (  479): NL - Read 1004 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_4847/cgroup.procs: No such file or directory
,E/wpa_supplicant( 5269): baseband property is set to [msm]
I/libmdmdetect( 5269): ESOC framework not supported
,D/AuthorizationBluetoothService( 1695): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/wpa_supplicant( 5269):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5269): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5269): card_info[i].card_state: 0x0
E/wpa_supplicant( 5269): card_info[i].error_code: 0x0
E/wpa_supplicant( 5269): SIM/USIM not ready
E/wpa_supplicant( 5269): Error while reading SIM card status
,E/wpa_supplicant( 5269): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5269): card_info[i].card_state: 0x0
E/wpa_supplicant( 5269): card_info[i].error_code: 0x0
E/wpa_supplicant( 5269): SIM/USIM not ready
I/wpa_supplicant( 5269): eap_proxy: Card not ready
,I/wpa_supplicant( 5269): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,E/WifiStateMachine(  881): setSuspendOptimizations: 2 true
E/WifiStateMachine(  881): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  881): Supplicant connection established
,E/WifiStateMachine(  881): setWifiState: enabled
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiConfigStore(  881): Loading config and enabling all networks 
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiConfigStore(  881):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  881):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  881): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  881): Setting external_sim to 1
,D/WifiStateMachine(  881): Setting OUI to DA-A1-19
I/WifiNative-HAL(  881): startHal
E/wifi    (  881): getStaticLongField sWifiHalHandle 0xa2e5489c
D/wifi    (  881): halHandle = 0x0, mVM = 0xb843e310, mCls = 0x10130a
I/WifiNative-HAL(  881): Could not start hal
,E/WifiStateMachine(  881): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 5269): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/wpa_supplicant( 5269): wlan0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 5269): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=5300 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,E/native  (  881): do suspend true
,D/WifiP2pService(  881): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  290): Setting iface cfg
D/CommandListener(  290): Trying to bring up p2p0
,D/WifiMonitor(  881): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  881): P2pEnablingState
D/WifiScanningService(  881): SCAN_AVAILABLE : 3
D/RttService(  881): SCAN_AVAILABLE : 3
,D/WifiScanningService(  881): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  881): startHal
E/wifi    (  881): getStaticLongField sWifiHalHandle 0xa48039cc
D/wifi    (  881): halHandle = 0x0, mVM = 0xb843e310, mCls = 0x201306
I/WifiNative-HAL(  881): Could not start hal
E/WifiScanningService(  881): could not start HAL
,D/WifiP2pService(  881): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2p socket connection successful
D/WifiP2pService(  881): P2pEnabledState
D/RttService(  881): DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): sending p2p connection changed broadcast
,D/WifiNative-HAL(  881): p2pGetDeviceAddress
,E/WifiStateMachine(  881): set country code US
,D/WifiNative-HAL(  881): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,D/WifiP2pService(  881): DeviceAddress: 44:80:eb:7b:5a:07
E/WifiStateMachine(  881): set frequency band 2
,D/WifiP2pService(  881): MCC mode enabled 0
,D/WifiP2pService(  881): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  881): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  881): InactiveState
D/WifiP2pService(  881): InactiveState{ when=-5ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-5ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5269): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 5269): wlan0: Failed to initiate AP scan
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/WifiP2pService(  881): InactiveState{ when=-8ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-8ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info0x
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/SharedPreferencesImpl(  881): Couldn't create directory for SharedPreferences file shared_prefs/android_preferences.xml
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 5300): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/MDMCTBK (  292): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  292): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): wifi_connect_to_supplicant, current pid is = 292
,D/MDMCTBK (  292): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  292): wifi_close_sockets: Exit
,E/MDMCTBK (  292): Attach monitor thread
,I/MDMCTBK (  292): createWifiMonitorThread: Started the wifi monitor thread -1201807632
D/MDMCTBK (  292): wifi_wait_on_socket: Enter monitor thread
,I/ActivityManager(  881): Killing 4995:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/Checkin ( 2914): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2914): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_4995/cgroup.procs: No such file or directory
,D/Checkin ( 2914): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  479): NL - Read 1004 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/Checkin ( 2914): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309909, SEQNUM=4381, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-14723, POWER_SUPPLY_CHARGE_COUNTER=-633, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5205): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5205): Disconnected process message: 10, size: 0
,D/MDMCTBK (  292): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  292): Event received = WPS-AP-AVAILABLE 
,I/WifiNative-HAL(  881): startHal
E/wifi    (  881): getStaticLongField sWifiHalHandle 0xa2e548fc
D/wifi    (  881): halHandle = 0x0, mVM = 0xb843e310, mCls = 0x201906
I/WifiNative-HAL(  881): Could not start hal
,E/WifiStateMachine(  881): [1,449,683,718,093 ms] noteScanEnd no scan source
,E/WifiStateMachine(  881): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@23f04f26 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  881): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  881):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  881): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  881): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,I/qcom-bluetooth( 5325): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 44:80:eb:7b:5a:05 
,I/qcom-bluetooth( 5326): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 5205): bluetooth satus is on
D/bt_userial_mct( 5205): userial_open(port:0)
,I/bt_userial_vendor( 5205): Done intiailizing UART
I/bt_userial_vendor( 5205): Done intiailizing UART
I/bt_userial_mct( 5205): CMD=53, EVT=53, ACL_Out=54, ACL_In=54
I/bt_vendor( 5205): Bluetooth Firmware and smd is initialized
D/bt_userial_mct( 5205): Entering userial_read_thread()
,I/bt-btu  ( 5205): btu_task received preload complete event
,I/        ( 5205): BTE_InitTraceLevels -- TRC_HCI
I/        ( 5205): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5205): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5205): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5205): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5205): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5205): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5205): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5205): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5205): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5205): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5205): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5205): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5205): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5205): BTE_InitTraceLevels -- TRC_BTIF
,E/WifiConfigStore(  881): will read network variables netId=0
,E/WifiStateMachine(  881): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  881): will read network variables netId=0
,E/bt-btm  ( 5205): BTM_SecRegister:p_cb_info->p_le_callback == 0xa6e15d85 
E/bt-btm  ( 5205): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa6e15d85 
,I/wpa_supplicant( 5269): wlan0: Trying to associate with SSID 'NG700'
E/bt-btif ( 5205): Calling BTA_HhEnable
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  292): Event received = Trying to associate with
,E/bt-btif ( 5205): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 5205): Address is:44:80:EB:7B:5A:05
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
E/wpa_supplicant( 5269): DSDS: eapol_sm_notify_config config->sim_num = 1
D/WifiMonitor(  881): didn't find BSSID Trying to associate with SSID 'NG700'
D/BluetoothAdapterProperties( 5205): Name is: XT1072
D/BluetoothManagerService(  881): Bluetooth Adapter name changed to XT1072
D/BluetoothManagerService(  881): Stored Bluetooth name: XT1072
D/BluetoothAdapterProperties( 5205): Scan Mode:20
D/BluetoothAdapterProperties( 5205): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5205): Adding bonded device:7C:F9:0E:37:96:AB
D/BluetoothAdapterProperties( 5205): Adding bonded device:58:2A:F7:ED:96:BE
E/BluetoothRemoteDevices( 5205): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:37:96:AB, value is empty for type: 10
E/BluetoothRemoteDevices( 5205): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
E/WifiConfigStore(  881): setLastSelectedConfiguration -1
D/bte_conf( 5205): Device ID record 1 : primary
D/bte_conf( 5205):   vendorId            = 000f
D/bte_conf( 5205):   vendorIdSource      = 0001
D/bte_conf( 5205):   product             = 1200
D/bte_conf( 5205):   version             = 1436
D/bte_conf( 5205):   clientExecutableURL = 
D/bte_conf( 5205):   serviceDescription  = 
D/bte_conf( 5205):   documentationURL    = 
D/bte_conf( 5205): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 5205): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5205): ScanMode =  20
D/BluetoothAdapterProperties( 5205): State =  11
,D/BluetoothPanServiceJni( 5205): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 5205): Setting state to 12
I/BluetoothAdapterState( 5205): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  881): Message: 60
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  881): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothA2dp(  881): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 5205): Scan Mode:21
I/BluetoothAdapterState( 5205): Entering On State
D/BluetoothAdapterProperties( 5205): Discoverable Timeout:120
D/BluetoothHeadset( 1502): onBluetoothStateChange: up=true
E/wpa_supplicant( 5269): PNO: In assoc process
D/BluetoothHeadset( 1502): onBluetoothStateChange: up=true
D/BluetoothHeadset(  881): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1538): onBluetoothStateChange: up=true
E/bt_mct  ( 5205): hci lib postload completed
D/BluetoothManagerService(  881): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  881): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 5205): onReceive
D/BluetoothManagerService(  881): Message: 40
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 5205): STATE_ON
D/BluetoothMapMasInstance( 5205): Map Service startRfcommSocketListener
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
D/BluetoothMapMasInstance( 5205): MAS initSocket()
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5205): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 5205): Accepting socket connection...
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/Telecom ( 1502): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/WifiP2pService(  881): P2pEnabledStateupdate channel list
W/ContextImpl( 5247): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/HeadsetStateMachine( 5205): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 5205): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 5205): mNumber:  mType: 128
D/HeadsetStateMachine( 5205): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 5205): terminateScoUsingVirtualVoiceCall:No present call to terminate
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6eabfcd:true
,D/LocalBluetoothProfileManager( 5247): Adding local A2DP profile
,D/BluetoothManagerService(  881): Message: 30
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/AuthorizationBluetoothService( 1695): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/BluetoothAdapter( 5205): getBluetoothService() called with no BluetoothManagerCallback
D/LocalBluetoothProfileManager( 5247): Adding local HEADSET profile
D/BluetoothManagerService(  881): Message: 30
,D/BluetoothManagerService(  881): Message: 30
,D/BluetoothManagerService(  881): Message: 30
,D/LocalBluetoothProfileManager( 5247): Adding local MAP profile
,D/BluetoothMap( 5247): Create BluetoothMap proxy object
,D/BluetoothManagerService(  881): Message: 30
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5205): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  881): Message: 30
I/BtOppRfcommListener( 5205): Accept thread started.
,D/LocalBluetoothProfileManager( 5247): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 5247): finishStartingService: stopping service
,D/BluetoothA2dp( 5247): Proxy object connected
,D/A2dpProfile( 5247): Bluetooth service connected
,D/BluetoothHeadset( 5247): Proxy object connected
,D/HeadsetProfile( 5247): Bluetooth service connected
,D/BluetoothInputDevice( 5247): Proxy object connected
D/HidProfile( 5247): Bluetooth service connected
,D/BluetoothPan( 5247): BluetoothPAN Proxy object connected
D/PanProfile( 5247): Bluetooth service connected
,D/BluetoothMap( 5247): Proxy object connected
,D/MapProfile( 5247): Bluetooth service connected
D/BluetoothMap( 5247): getConnectedDevices()
,D/BluetoothPbap( 5247): Proxy object connected
D/PbapServerProfile( 5247): Bluetooth service connected
,I/MDMCTBK (  292): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  292): NetlinkHandler, interfaceAdded
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
E/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  292): , Wifi = 0
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
,I/MDMCTBK (  292): send SAR ctrl over QMI
,D/TCMD    (  479): NL - Read 312 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 88 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 68 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/TCMD    (  479): NL - Read 1004 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,I/wpa_supplicant( 5269): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  292): Event received = Associated with c0:ff:d4
D/TCMD    (  479): NL - Read 80 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 80 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 68 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info"NG700"
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE ,
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Tethering(  881): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  0
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
D/Tethering(  881): sendTetherStateChangedBroadcast 1, 0, 0
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 5269): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 5269): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  292): Event received = WPA: Key negotiation com
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292):  STA Connected !!
D/TCMD    (  479): NL - Read 1004 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,E/MDMCTBK (  292): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  292): get_freq !!, resp=2412
I/MDMCTBK (  292): get_freq !!, Strip data
I/MDMCTBK (  292): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=0,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, Wifi Band changed, call setWifiCutback.
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 1, data=0
I/MDMCTBK (  292): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  292): MdmCutbackHndler, set WIFI TX pwr !!
,I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1201791792
I/MDMCTBK (  292): return from set_get_from_wpa_supplicant
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): wifi_set_tx_pwr: SETTXPOWER = 18
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  292): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  292): , reply_len: 3, ret: 0
E/MDMCTBK (  292): MdmCutbackHndler, resp=OK
E/MDMCTBK (  292): 
D/MDMCTBK (  292): wifi_set_tx_pwr: Exit
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  881): Network connection established
,E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  881): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  881): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  881): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  881): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine(  881): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  881): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,D/CommandListener(  290): Setting iface cfg
,E/WifiStateMachine(  881): Start Dhcp Watchdog 1
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend false
,E/wpa_supplicant( 5269): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  881): Unexpected BatchedScanResults :null
E/wpa_supplicant( 5269): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  881): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@28872151 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@28872151 target=com.android.internal.util.StateMachine$SmHandler }
,E/DHCPCD  ( 5354): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5354): version 5.5.6 starting
,E/DHCPCD  ( 5354): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 5354): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 5354): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 5354): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 5354): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 5354): wlan0: sending REQUEST (xid 0xe48134a0), next in 3.77 seconds
,I/DHCPCD  ( 5354): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 5354): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 5354): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 5354): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 5354): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5354): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5354): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/TCMD    (  479): NL - Read 60 bytes from update socket.
D/TCMD    (  479): NL - ignore NL message, type = 20
D/TCMD    (  479): Listening for incoming client connection request
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend true
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  881): WifiStateMachine DHCP successful
E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  881): Calling ARP set with IP = 192.168.1.123
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  881): Adding iface wlan0 to network 100
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  881): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  881): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  881): Adding Route [fe80::/64 -> :: wlan0] to network 100
,E/WifiStateMachine(  881): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  881): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  881): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  881): Setting Dns servers for network 100 to [/192.168.1.1]
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  881): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Connected
,D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  881):    accepting network in place of null
D/ConnectivityService(  881): Setting tx/rx TCP buffers to 131072,262144,3145728,4096,221184,3145728
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
,D/CSLegacyTypeTracker(  881): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  881): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
I/ModemStatsDSDetect( 1521): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=0
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1941): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 17:55:20 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449683720817], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449683720793]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Validated
,D/ConnectivityService(  881): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  881): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
D/ConnectivityManager.CallbackHandler( 1941): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1521): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1521): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/MMApiBackOffService( 2518): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2518): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2518): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2518): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2518): generating token using payload instead of using session token
,D/ Nonce  ( 2518):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2518): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2518): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2518): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2518): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2518): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,I/art     (  881): Explicit concurrent mark sweep GC freed 41855(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.860ms total 127.519ms
,D/MMApiWebService( 2518): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/MMApiWSBase( 2518): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2518): publish the event [tag = MOT_CCE event name = LOG]
,I/ Nonce  ( 2518):  Nonce Reponse 
D/        ( 2518): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"780f4ab4-7b50-4c3f-8e8b-a9d74a56b33e"}
D/MMApiWSBase( 2518): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2518):  Nonce Handle Reponse 
D/MMApiProvisionService( 2518): mOutstandingReq set to false
,D/MMApiProvisionService( 2518):  pTime 1449671329422 sExp 172742 cTime 1449683722127 tTime 1449844071422
D/MMApiProvisionService( 2518):  No login Required 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,W/DataUsage( 2518): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2518): publish the event [tag = MOT_CCE event name = LOG]
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524295
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityManager.CallbackHandler( 1941): CM callback handler got msg 524295
,D/MMApiWSBase( 2518): doRequest(): v1/gns/list/messages resp length: 1363
D/CCE     ( 2518): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 2518): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Checkin ( 2518): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 2518): handleGetNotificationsResponse(): got 0; more=false
,I/SundryService( 2518): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 2518): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 2518): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 2518): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2518): unbindWebServices(): un-registering our AIDL callback...
,W/DataUsage( 2518): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2518): publish the event [tag = MOT_CCE event name = LOG]
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PollingManager( 2518): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1464): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2518): now: 207992 ,futureTime: 9223372036854775807
D/PollingManager( 2518): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2518): now: 208001 ,futureTime: 9223372036854775807
,D/PollingManager( 2518): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2518): now: 208030 ,futureTime: 9223372036854775807
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5420 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/OtaApp  ( 2518): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AlarmManagerService(  881): Setting time of day to sec=1449683723
,W/AlarmManagerService(  881): Unable to set rtc to 1449683723: Invalid argument
,V/AlarmManager(  881): send {115206d6, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,D/Central_PollingManager( 1464): now: 208091 ,futureTime: 86475934
D/Central_PollingManager( 1464): Polling alarm set to expire at: 86475934 Current Time: 208092
D/OtaApp  ( 2518): [debug] > PollingManagerService, now: 208083 ,futureTime: 74229498
D/OtaApp  ( 2518): [debug] > Polling alarm set to expire at: 74229498 Current Time: 208092
,D/MMApiProvisionService( 2518): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2518): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2518): createDeviceIdOrLogin update_device
,D/Checkin ( 2518): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2518): Not proxy app, so login/provision not allowed
,E/GpsLocationProvider(  881): No APN found to select.
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 4494(202KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 835us total 46.394ms
,D/MMApiProvisionService( 2518): isDeviceProvisioned: deviceId = 2072049230914535424
,D/GpsLocationProvider(  881): NTP server returned: 1449683720763 (Wed Dec 09 18:55:20 GMT+01:00 2015) reference: 205074 certainty: 16 system time offset: -3113
,E/LocSvc_ApiV02(  881): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,D/CCE     ( 2518): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2518): createDeviceIdOrLogin update_device
,D/Checkin ( 2518): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2518): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2518): set mOutstandingReq to true.
I/ Nonce  ( 2518):  Nonce getNonce 
I/ Nonce  ( 2518):  Nonce Request 
I/ Nonce  ( 2518):  Nonce execute Request 
,D/MMApiWebService( 2518): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2518): isDeviceProvisioned: deviceId = 2072049230914535424
,E/ActivityThread( 1941): Failed to find provider info for com.android.contacts.metadata
,D/CCE     ( 2518): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2518): createDeviceIdOrLogin update_device
,D/Checkin ( 2518): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2518): Not proxy app, so login/provision not allowed
,D/SyncManager(  881): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 238902, reason: UserStart
,D/OtaApp  ( 2518): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2518): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2518): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWebService( 2518): generating token using payload instead of using session token
,D/OtaApp  ( 2518): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2518): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2518): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2518): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2518): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2518): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/ Nonce  ( 2518):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/OtaApp  ( 2518): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 2518): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2518): publish the event [tag = MOT_CCE event name = LOG]
,I/MusicStore( 5420): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5420): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Auth.Api.Credentials( 1941): [CredentialSyncAdapter] Unknown sync event.
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1695): Vacuum at: now=1449683724383 tag=VacuumService
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5420): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5420): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 5420): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5420): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5420): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     (  881): Explicit concurrent mark sweep GC freed 22004(975KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.886ms total 142.198ms
,W/ActivityThread( 5420): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5420): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5420): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5420): GMSCore installation verified
,I/ConfigStore( 5420): Config Database version: 1
,I/MediaRouter( 5420): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5420): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ Nonce  ( 2518):  Nonce Reponse 
D/        ( 2518): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"fd89bef8-a934-4a88-81d4-e3c2e40c2eae"}
D/MMApiWSBase( 2518): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2518):  Nonce Handle Reponse 
D/MMApiProvisionService( 2518): mOutstandingReq set to false
,I/NetworkMonitor( 5420): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5420): type=WIFI subType= reason=null isConnected=true
,D/MMApiProvisionService( 2518):  pTime 1449671329422 sExp 172742 cTime 1449683724887 tTime 1449844071422
D/MMApiProvisionService( 2518):  No login Required 
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5494 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 5420): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5420): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=5512 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5512): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/Mms     ( 5494): mnc/mcc: 
V/Mms     ( 5494): tag: int value: recipientLimit - 20
V/Mms     ( 5494): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 5494): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 5494): tag: int value: maxSubjectLength - 80
V/Mms     ( 5494): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 5494): tag: bool value: enableGroupMms - false
V/Mms     ( 5494):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  881): Killing 4932:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/DataUsage( 2518): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2518): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_4932/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1941): Module APK com.google.android.play.games already loaded
,I/PhenotypeConfigurator( 1695): Scheduling Phenotype for one-off execution 14325 seconds from now (1449683725391)
,D/GetConfigurationSnapshotOperation( 1695): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,W/ResourcesManager( 5494): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5545 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 21.236ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 19.213ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 20.188ms
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5567 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     ( 1538): Explicit concurrent mark sweep GC freed 29975(1923KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.069ms total 71.386ms
,I/ActivityManager(  881): Killing 5023:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 5545): Register our PhoneStateListener
,I/ContactLocale( 5567): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/PhenotypeFlagCommitter( 1695): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1695): Using platform SSLCertificateSocketFactory
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_5023/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 5545): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5545): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 5247:com.android.settings/1000 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_1000/pid_5247/cgroup.procs: No such file or directory
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 1941): 0 accounts found with uca feature
,I/CheckinService( 1941): Checkin interval check for package: unspecified last checkin: 1449681494022 min interval config: 0 actual interval: 2232170
,I/GamesSyncAdapter( 1941): Starting sync for 3a3529a
,I/CheckinService( 1941): Checking schedule, now: 1449683726218 next: 1449681523906
I/CheckinService( 1941): active receiver: enabled
,I/iu.SyncManager( 1941): SYNC; picasa accounts
,D/NetworkLogImpl( 1941): Loaded NetworkSpeedPredictor
I/CheckinService( 1941): Preparing to send checkin request
,I/GamesSyncAdapter( 1941): Sync duration for 3a3529a: 60
I/EventLogService( 1941): Accumulating logs since 1449683347348
,I/iu.Environment( 1941): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1941): num queued entries: 0
,I/iu.UploadsManager( 1941): num updated entries: 0
I/iu.SyncManager( 1941): NEXT; no task
,I/MDMCTBK (  292): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  292): NetlinkHandler, interfaceAdded
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
E/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  292): , Wifi = 1
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
,I/MDMCTBK (  292): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  292): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  292): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1201791792
I/MDMCTBK (  292): return from set_get_from_wpa_supplicant
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
D/MDMCTBK (  292): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  292): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  292): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  292): , reply_len: 3, ret: 0
E/MDMCTBK (  292): MdmCutbackHndler, resp=OK
E/MDMCTBK (  292): 
D/MDMCTBK (  292): wifi_set_tx_pwr: Exit
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,I/MDMCTBK (  292): send SAR ctrl over QMI
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=5607 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/GCM     ( 1695): GCM config loaded
,I/art     (  881): Explicit concurrent mark sweep GC freed 16337(683KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 10.717ms total 158.555ms
,D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1941): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1941): Module APK com.google.android.play.games already loaded
,I/CheckinRequestBuilder( 1941): Checkin reason type: 8 attempt count: 1
,D/WifiService(  881): New client listening to asynchronous messages
,E/ActivityThread( 1941): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 5041): Explicit concurrent mark sweep GC freed 1616(72KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 354us total 37.962ms
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1941): Explicit concurrent mark sweep GC freed 31762(2MB) AllocSpace objects, 37(592KB) LOS objects, 24% free, 15MB/20MB, paused 2.488ms total 127.282ms
,W/art     ( 5512): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5647 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 5300:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_5300/cgroup.procs: No such file or directory
,W/ResourcesManager( 5647): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5671 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 5671): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5671): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5671): VM with version 2.1.0 has multidex support
I/MultiDex( 5671): install
I/MultiDex( 5671): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5671): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5671): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5671): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5671): Installed default security provider GmsCore_OpenSSL
,I/art     ( 5671): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5671): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel_SMS( 5647): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5647): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5647): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5647): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5647): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5647): MmsConfig.loadFromResources
,E/Babel_SMS( 5647): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5647): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/NativeLibraryUtils( 5671): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fd9000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fd9000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,W/art     ( 5647): Suspending all threads took: 6.975ms
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb13bc960
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8b37420, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8b80a48, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8c537f0, idLength=0xbee012b0
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=2517792386
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8b80a48
,D/DrmWidevineDash(  294): message_length=1591, signature=0xb8b5d208, signature_length=3202355860
,W/Settings( 5647): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5647): startup - clean
,I/Babel   ( 5647): deleted: false for 0
,W/art     ( 5647): Suspending all threads took: 5.398ms
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5703 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 5647): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5647): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5647): Unsupported mime video/mpeg2
,I/jxcore-log( 5144): Test app app.js loaded
I/jxcore-log( 5144): 
,I/VideoCapabilities( 5647): Unsupported profile 4 for video/mp4v-es
,I/chromium( 5144): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/VideoCapabilities( 5647): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5647): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5647): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5647): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5647): onServiceConnected
W/Babel   ( 5647): Attempted to change video mute state without an active call.
,I/Babel   ( 5647): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 5420:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_5420/cgroup.procs: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5703): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5703): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5703): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5703): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 5703): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5703):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5703):   adb logcat -s GAv4
,W/GAv4    ( 5703): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5703): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5703): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 5729): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 5729): dex2oat took 164.251ms (threads: 4)
,I/Adreno-EGL( 5671): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5671): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5671): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5671): Local Branch: 
I/Adreno-EGL( 5671): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5671): Local Patches: NONE
I/Adreno-EGL( 5671): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 5671): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5671): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5671): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5671): Local Branch: 
I/Adreno-EGL( 5671): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5671): Local Patches: NONE
I/Adreno-EGL( 5671): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 5671): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5671): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5671): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5671): Local Branch: 
I/Adreno-EGL( 5671): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5671): Local Patches: NONE
I/Adreno-EGL( 5671): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 5703): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5703): Time to load native libraries: 2 ms (timestamps 3884-3886)
I/LibraryLoader( 5703): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5703): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 5703): Expected native library version number "",actual native library version number ""
I/chromium( 5703): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/Adreno-EGL( 5671): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5671): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5671): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5671): Local Branch: 
I/Adreno-EGL( 5671): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5671): Local Patches: NONE
I/Adreno-EGL( 5671): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/BrowserStartupController( 5703): Initializing chromium process, singleProcess=true
W/art     ( 5703): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5703): ApplicationContext is null in ApplicationStatus
,W/chromium( 5703): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5703): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5703): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5703): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5703): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5703): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5703): Local Branch: 
I/Adreno-EGL( 5703): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5703): Local Patches: NONE
I/Adreno-EGL( 5703): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
W/AudioManagerAndroid( 5703): Requires BLUETOOTH permission
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fd9000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fd9000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb54a7960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8b5d328, dataLength=8
,D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8b87f98, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8c53830, idLength=0xbee012b0
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=132116021
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8b87f98
D/DrmWidevineDash(  294): message_length=1625, signature=0xb8b01750, signature_length=3202355860
,I/NSApplication( 5703): Starting up...
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5783 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 5494:com.android.mms/u0a23 (adj 15): empty #7
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_5494/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 5545:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_5545/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 5567:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_5567/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2518): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2518): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2518): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,E/SQLiteLog( 2518): (284) automatic index on registration(APP_ID)
,D/WaitableIntentService( 2518): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2518): onServiceConnected()
,D/GetNotificationsWS( 2518): onServiceConnected(): Registered for remote service callbacks...
,I/PushService( 2518): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=5813 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/GetNotificationsWS( 2518): unbindWebServices(): un-registering our AIDL callback...
,I/CheckinRequestBuilder( 1941): Classify the device as Phone.
,W/ResourcesManager( 5813): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=5837 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 5607:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_5607/cgroup.procs: No such file or directory
,I/CheckinTask( 1941): Sending checkin request (9756 bytes)
,E/SQLiteLog( 5837): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  881): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5862 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5862): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AnalyticsLogBase( 5837): PlayLogger.onLoggerConnected
,I/ActivityManager(  881): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5883 uid=10096 gids={50096, 9997} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 5703:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ActivityManager(  881): Killing 5647:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_5703/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_5647/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5862): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,I/CheckinRequestBuilder( 1941): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1941): Failed to find provider info for com.google.android.wearable.settings
,I/System.out( 5883): TimeService: Loaded Library 
D/TimeService( 5883): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449683731142
D/        ( 5883): TimeServiceNative: User Time to be set is 1449683731142
D/QC-time-services( 5883): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5883): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5883): Lib:time_genoff_operation: pargs->ts_val = 1449683731142
,D/QC-time-services(  862): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  862): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449683731142
,D/QC-time-services(  862): Daemon:genoff_opr: Base = 2, val = 1449683731142, operation = 0
D/QC-time-services(  862): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/9/115 17:54:16
D/QC-time-services(  862): Daemon:Value read from RTC seconds = 1449683656000
D/QC-time-services(  862): Daemon:new time 1449683731142 
D/QC-time-services(  862): Daemon: delta 75142 genoff 75142 
D/QC-time-services(  862): Daemon:genoff_persistent_update: Writing genoff = 75142 to memory
D/QC-time-services(  862): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  862): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services( 5883): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  862): Updating the TOD offset
D/QC-time-services(  862): Daemon:genoff_persistent_update: Writing genoff = 75142 to memory
D/QC-time-services(  862): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  862): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  862): Daemon:Update to modem bit set
D/QC-time-services(  862): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  862): Daemon: Base = 2, Value being sent to MODEM = 18446743757744826758
,E/QC-time-services( 5883): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  862): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  862): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1941): Checkin interval check for package: unspecified last checkin: 1449681494022 min interval config: 0 actual interval: 2237154
,I/art     (  881): Explicit concurrent mark sweep GC freed 18156(844KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.455ms total 115.821ms
,I/ActivityManager(  881): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=5903 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 22.980ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 20.598ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 20.860ms
,I/CheckinRequestBuilder( 1941): Classify the device as Phone.
,I/CheckinTask( 1941): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1941): Checking schedule, now: 1449683731527 next: 1450284868522
I/CheckinService( 1941): active receiver: disabled
,I/GAv4    ( 5903): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5903):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5903):   adb logcat -s GAv4
,D/CheckinService( 1941): Recording last checkin time for package unspecified as 1449683731562
,W/GAv4    ( 5903): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  881): Killing 5512:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,W/GAv4    ( 5903): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5903): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  881): Killing 5783:com.android.chrome/u0a52 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_5512/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_5783/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 5813:com.motorola.context/u0a8 (adj 13): empty #7
,V/AlarmManager(  881): done {115206d6, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [8217ms]
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_5813/cgroup.procs: No such file or directory
,D/OtaApp  ( 2518): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2518): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2518): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  881): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2518): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2518): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2518): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2518): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2518): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2518): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2518): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2518): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2518): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2518): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2518): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2518): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,I/Keyboard.Facilitator( 1405): onFinishInput()
,W/IInputConnectionWrapper( 5144): showStatusIcon on inactive InputConnection
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5965 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CalendarProvider2( 5862): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5862): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  881): Killing 5837:com.google.android.calendar/u0a49 (adj 13): empty #7
,W/SQLiteConnectionPool( 1941): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/LaunchCheckinHandler(  881): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,369
,W/libprocessgroup(  881): failed to open /acct/uid_10049/pid_5837/cgroup.procs: No such file or directory
,W/ResourcesManager( 5965): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5965): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5965): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5965): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5965): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5965): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5965): MmsConfig.loadFromResources
E/Babel_SMS( 5965): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5965): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 5965): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5965): startup - clean
,I/Babel   ( 5965): deleted: false for 0
,W/art     ( 5965): Suspending all threads took: 25.159ms
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=5995 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 5965): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5965): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5965): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5965): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5965): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5965): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5965): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5965): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  881): Killing 5883:com.qualcomm.timeservice/u0a96 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10096/pid_5883/cgroup.procs: No such file or directory
,I/vclib   ( 5965): onServiceConnected
W/Babel   ( 5965): Attempted to change video mute state without an active call.
,D/WearableService( 1695): callingUid 10016, callindPid: 1695
,D/LocationInitializer( 1941): Restart initialization of location
,E/MDM     ( 1695): [151] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1695): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.WidgetDataReceiver: pid=6026 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1695): No location to return for getLastLocation()
,W/FusedLocationProvider( 1695): location=null
,E/SQLiteLog( 6026): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/AnalyticsLogBase( 6026): PlayLogger.onLoggerConnected
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6053 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6053): Register our PhoneStateListener
,V/SetupWizard( 6053): Connected to Gservices successfully
,I/ActivityManager(  881): Killing 5903:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10055/pid_5903/cgroup.procs: No such file or directory
,D/GCM     ( 1695): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6075 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 6075): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task.xml
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  881): Killing 5965:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_5965/cgroup.procs: No such file or directory
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1538): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6100 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/GCoreNlp( 1695): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  881): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  881): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Launcher( 1557): Deferring update until onResume
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6138 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/art     ( 1695): Explicit concurrent mark sweep GC freed 92631(5MB) AllocSpace objects, 35(583KB) LOS objects, 39% free, 14MB/24MB, paused 1.247ms total 123.837ms
,E/DataBuffer( 1695): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@912b53)
E/DataBuffer( 1695): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@e34ec90)
,E/DataBuffer( 1695): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@33fcc989)
E/DataBuffer( 1695): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@10ffbd8e)
E/DataBuffer( 1695): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@127929af)
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6156 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 5995:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_5995/cgroup.procs: No such file or directory
,V/BackupManagerService(  881): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@23e2920c
,I/ActivityManager(  881): Killing 6053:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/ResourcesManager( 6156): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_6053/cgroup.procs: No such file or directory
,I/art     (  881): Explicit concurrent mark sweep GC freed 20271(1079KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.733ms total 128.536ms
,I/Babel_SMS( 6156): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6156): MmsConfig.loadMmsSettings
I/Babel_SMS( 6156): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6156): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6156): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6156): MmsConfig.loadFromResources
,E/Babel_SMS( 6156): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6156): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6156): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6156): startup - clean
,I/Babel   ( 6156): deleted: false for 0
,I/ActivityManager(  881): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6185 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 6156): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6156): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6156): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6156): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6156): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6156): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6156): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6156): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6204 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 6185): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  881): Killing 6075:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_6075/cgroup.procs: No such file or directory
,W/asset   ( 6204): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 6204): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6204): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6204): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/vclib   ( 6156): onServiceConnected
,W/Babel   ( 6156): Attempted to change video mute state without an active call.
,D/PackageBroadcastService( 1941): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1941): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1941): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 6100): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1557): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
W/ResourcesManager( 6156): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6156): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6236 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.480ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 19.866ms
,V/JNIHelp ( 6156): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.673ms
,D/HeadsetStateMachine( 5205): Disconnected process message: 10, size: 0
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=306, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310487, SEQNUM=4418, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-18028, POWER_SUPPLY_CHARGE_COUNTER=-718, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
W/ResourcesManager( 6236): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/HeadsetStateMachine( 5205): Disconnected process message: 10, size: 0
,I/UpdateIcingCorporaServi( 6100): UpdateCorporaTask done [took 177 ms] updated apps [took 177 ms] 
,I/ActivityManager(  881): Killing 5862:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/System  ( 6156): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6156): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  881): failed to open /acct/uid_10005/pid_5862/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6262 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 5671:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_5671/cgroup.procs: No such file or directory
,W/ContextImpl( 6026): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 6026): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 6262): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6262): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6262): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6262): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 6262): Skipping gmscore version check
,D/Finsky  ( 6262): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6262): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  881): Killing 6138:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10019/pid_6138/cgroup.procs: No such file or directory
,D/Finsky  ( 6262): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6262): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  881): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6312 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6312): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6312): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,I/ActivityManager(  881): Killing 6026:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10049/pid_6026/cgroup.procs: No such file or directory
,I/Icing   ( 1941): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1941): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  881): Killing 6204:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10027/pid_6204/cgroup.procs: No such file or directory
,I/CalendarProvider2( 6312): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6312): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6333 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6100:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_6100/cgroup.procs: No such file or directory
,W/ResourcesManager( 6333): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=6355 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6185:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_6185/cgroup.procs: No such file or directory
,E/SQLiteLog( 6355): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/AnalyticsLogBase( 6355): PlayLogger.onLoggerConnected
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,I/ActivityManager(  881): Killing 6156:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6156/cgroup.procs: No such file or directory
,W/ContextImpl( 6355): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 6355): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  881): Killing 6236:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6236/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  881): send {2cd8ccff, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  881): done {2cd8ccff, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310365, SEQNUM=4429, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-770, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5205): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5205): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1695): disconnect managed GoogleApiClient
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  881): send {1ef76342, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {32ff2acc, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  881): done {32ff2acc, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [14ms]
,V/AlarmManager(  881): done {1ef76342, *alarm*:android.intent.action.TIME_TICK} [48ms]
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311131, SEQNUM=4431, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-825, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5205): Disconnected process message: 10, size: 0
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  881): send {2cd8ccff, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  881): done {2cd8ccff, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,E/ActivityThread( 1941): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  881): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 329521, reason: UserStart
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1405): run()
I/Keyboard.Facilitator( 1405): flushDynamicLanguageModels()
,I/ConfigService( 1695): onCreate
,I/ConfigService( 1695): onDestroy
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  881): send {2cd8ccff, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  881): done {2cd8ccff, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310439, SEQNUM=4433, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-961, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5205): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 5144): TAP version 13
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # multiplex can send data
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 1 String should be length:200
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # basic
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 2 sane
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # another
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 3 sane
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 4 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 5 null
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 6 (unnamed assert)
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 7 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 8 should not throw
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 9 (unnamed assert)
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 10 (unnamed assert)
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 11 should not throw
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 12 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 13 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 14 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # failed to get mobile documents path
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 15 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 16 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 17 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 18 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # #init should register the networkChanged event
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 19 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # #startBroadcasting should throw on null device name
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 20 should throw
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 21 should throw
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # #startBroadcasting should throw on non-number port
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 22 should throw
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # #startBroadcasting should throw on NaN port
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 23 should throw
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # #startBroadcasting should throw on negative port
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 24 should throw
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # #startBroadcasting should throw on too large port
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 25 should throw
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 26 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 27 should be equal
I/jxcore-log( 5144): 
I/jxcore-log( 5144): ok 28 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 29 should be equal
I/jxcore-log( 5144): 
I/jxcore-log( 5144): ok 30 should be equal
I/jxcore-log( 5144): 
I/jxcore-log( 5144): ok 31 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 32 should be equal
I/jxcore-log( 5144): 
I/jxcore-log( 5144): ok 33 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 34 should be equal
I/jxcore-log( 5144): 
I/jxcore-log( 5144): ok 35 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 36 should be equal
I/jxcore-log( 5144): 
I/jxcore-log( 5144): ok 37 should be equal
I/jxcore-log( 5144): 
I/jxcore-log( 5144): ok 38 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 39 should be equal
I/jxcore-log( 5144): 
I/jxcore-log( 5144): ok 40 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # should call Mobile("Disconnect") without an error
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 41 should be equal
I/jxcore-log( 5144): 
I/jxcore-log( 5144): ok 42 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 43 should be equal
I/jxcore-log( 5144): 
I/jxcore-log( 5144): ok 44 should be equal
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 5144): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683852199.5144
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852199.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852199.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683852199.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2041b35c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2041b35c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
,I/jxcore-log( 5144): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
,I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  881): discovery change broadcast true
,I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
,D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
,D/WifiP2pService(  881): remove client information from framework
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
I/jxcore-log( 5144): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 5144): 
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683852302.5144
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852302.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852302.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683852302.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@94682778 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@94682778 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  881): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
I/jxcore-log( 5144): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
D/WifiP2pService(  881): remove client information from framework
D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
I/jxcore-log( 5144): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 5144): 
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683852355.5144
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852355.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852355.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683852355.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7827bbe8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7827bbe8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
D/WifiP2pService(  881): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  881): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
I/jxcore-log( 5144): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
D/WifiP2pService(  881): remove client information from framework
D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
D/WifiP2pService(  881): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  881): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
I/jxcore-log( 5144): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 5144): 
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683852399.5144
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852399.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852399.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683852399.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d5d4a7d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d5d4a7d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  881): discovery change broadcast true
I/jxcore-log( 5144): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
D/WifiP2pService(  881): remove client information from framework
D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
I/jxcore-log( 5144): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 5144): 
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683852426.5144
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852426.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852426.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683852426.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2f60aa2a target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2f60aa2a target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
I/jxcore-log( 5144): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: P2P: Reject scan trigger since one is already pending
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Socket is null
,D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
D/WifiP2pService(  881): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
D/WifiP2pService(  881): remove client information from framework
D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
I/jxcore-log( 5144): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 5144): 
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683852450.5144
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852450.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852450.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683852450.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2793c7f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2793c7f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  881): discovery change broadcast true
I/jxcore-log( 5144): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
D/WifiP2pService(  881): InactiveState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
D/WifiP2pService(  881): remove client information from framework
D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
I/jxcore-log( 5144): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 5144): 
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiP2pService(  881): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683852473.5144
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852473.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852473.5144","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683852473.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@df168726 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@df168726 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5269): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  881): discovery change broadcast true
I/jxcore-log( 5144): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
D/WifiP2pService(  881): InactiveState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
D/WifiP2pService(  881): remove client information from framework
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
,I/jxcore-log( 5144): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 5144): 
D/WifiP2pService(  881): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683852496.5144
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852496.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852496.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683852496.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9699465c target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9699465c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  881): discovery change broadcast true
,I/jxcore-log( 5144): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,D/WifiP2pService(  881): remove client information from framework
D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
I/jxcore-log( 5144): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 5144): 
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiP2pService(  881): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683852516.5144
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852516.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852516.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683852516.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7b6b32aa target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7b6b32aa target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
I/jxcore-log( 5144): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
,D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
,D/WifiP2pService(  881): discovery change broadcast true
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
,D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,D/WifiP2pService(  881): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
,D/WifiP2pService(  881): InactiveState{ when=-2ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/jxcore-log( 5144): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 5144): 
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683852540.5144
D/WifiP2pService(  881): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiP2pService(  881): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852540.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683852540.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683852540.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@739e5070 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@739e5070 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  881): discovery change broadcast true
,I/jxcore-log( 5144): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
D/WifiP2pService(  881): remove client information from framework
D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
I/jxcore-log( 5144): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup,
I/jxcore-log( 5144): 
,I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
,I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
,I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
,I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
,D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 9e
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 1 9e
,I/jxcore-log( 5144): # ThaliEmitter calls startBroadcasting twice with error,
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683853488.5144
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683853488.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683853488.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683853488.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
,I/art     (  881): Explicit concurrent mark sweep GC freed 26972(1493KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.762ms total 126.209ms
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
I/jxcore-log( 5144): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
I/jxcore-log( 5144): ok 66 Cannot call startBroadcasting twice
I/jxcore-log( 5144): 
,I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6786c9d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6786c9d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
D/WifiP2pService(  881): discovery change broadcast true
D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
D/WifiP2pService(  881): remove client information from framework
D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
I/jxcore-log( 5144): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 5144): 
D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
,I/wpa_supplicant( 5269): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-84
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/WifiP2pService(  881): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 5144): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683855118.5144
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683855118.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683855118.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683855118.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8c998468 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8c998468 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  881): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
I/jxcore-log( 5144): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): connect: Trying to connect to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 5144): hasConnection: No connection with peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 5144): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 5144): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 5144): ok 69 Should not connect to a bad peer
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
,D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState clear service
,D/WifiP2pService(  881): remove client information from framework
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 5269): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/WifiP2pService(  881): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
D/WifiP2pService(  881): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
,I/jxcore-log( 5144): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/wpa_supplicant( 5269): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-84
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
,D/TCMD    (  479): Listening for incoming client connection request
,D/WifiP2pService(  881): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 5144): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683856757.5144
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683856757.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683856757.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683856757.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2df5c254 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2df5c254 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  881): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
,I/jxcore-log( 5144): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
D/io.jxcore.node.ConnectionHelper( 5144): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 5144): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
I/jxcore-log( 5144): ok 72 Disconnect should fail to a non-existant peer 
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
,D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
,D/WifiP2pService(  881): remove client information from framework
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139307 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 5269): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/WifiP2pService(  881): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
D/WifiP2pService(  881): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
I/jxcore-log( 5144): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/wpa_supplicant( 5269): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-83
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
,D/TCMD    (  479): Listening for incoming client connection request
,D/WifiP2pService(  881): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -83 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 5144): # ThaliEmitter can discover and connect to peers
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683858430.5144
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683858430.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683858430.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683858430.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e00d34e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e00d34e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  881): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
I/jxcore-log( 5144): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): restart: Restarting...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 5269): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/WifiP2pService(  881): InactiveState{ when=-4ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): discovery change broadcast false
,D/WifiP2pService(  881): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): restart: Restarting...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 5144): onPeerListChanged: Got a list of peers, which is null
,I/wpa_supplicant( 5269): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-84
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/WifiP2pService(  881): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): DefaultState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): startServiceDiscovery: Invalid state, try calling restart()
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=280, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309918, SEQNUM=4447, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-1011, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5205): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 5205): Disconnected process message: 10, size: 0
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  881): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 5269): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-84
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
,D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: 1 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/WifiP2pService(  881): InactiveState{ when=0 what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service request
,D/WifiP2pManager( 5144): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service request added successfully
,I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState discover services
,I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onServiceListChanged: Got empty list
,I/wpa_supplicant( 5269): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  881):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  881):  primary type: 10-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 392
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 37
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  881):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  881):  primary type: 10-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 392
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 37
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"1449683858475.5462","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"1449683858475.5462","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"1449683858475.5462","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB 1449683858475.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 5144): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: 1449683858475.5462, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: A5-1, Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 5144): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 5144): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5144): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): connect: A5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 5144): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,W/io.jxcore.node.ConnectionHelper( 5144): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 608)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 5144): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5205): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,W/bt-btif ( 5205): info:x10
,D/        ( 5205): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29a1e926:true
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23919314:true
,W/bt-sdp  ( 5205): process_service_search_attr_rsp
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=6484 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5b7d503:true
,I/BTConnectionReceiver( 6484): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothBondStateMachine( 5205): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,I/BluetoothBondStateMachine( 5205): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 12 NewState: 11
,E/bt-btif ( 5205): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 5205): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 5205): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 5205): Removing bonded device:7C:F9:0E:37:96:AB
I/BluetoothBondStateMachine( 5205): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,D/BluetoothMetrics( 5205): btclass5a020c
,D/Checkin ( 5205): publish the event [tag = MOT_BT event name = PAIRING]
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
I/BluetoothBondStateMachine( 5205): StableState(): Entering Off State
,W/bt-btif ( 5205): new conn_srvc id:26, app_id:1
W/bt-btif ( 5205): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 5205): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onSocketConnected: Authenticating next: [7C:F9:0E:37:96:AB 1449683858475.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 608)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): onBytesWritten: 77 bytes successfully written (thread ID: 609)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Outgoing connection initialized (*handshake* thread ID: 609)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Exiting thread (thread ID: 608)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Entering thread (ID: 609)
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6522 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): onBytesRead: Read 77 bytes successfully (thread ID: 609)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Handshake succeeded with [7C:F9:0E:37:96:AB 1449683858475.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onAuthenticated: Fully connected: [7C:F9:0E:37:96:AB 1449683858475.5462 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnected: [7C:F9:0E:37:96:AB 1449683858475.5462 7C:F9:0E:37:96:AB]
I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Outgoing connection, peer ID: 7C:F9:0E:37:96:AB, name: 1449683858475.5462, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5144): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
,I/io.jxcore.node.ConnectionHelper( 5144): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Exiting thread (ID: 609)
I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 5144): onConnected: The total number of connections is now 1
W/bt-btif ( 5205): invalid rfc slot id: 18
D/io.jxcore.node.OutgoingSocketThread( 5144): Entering thread (ID: 610)
D/io.jxcore.node.OutgoingSocketThread( 5144): Server socket local port: 44211
I/io.jxcore.node.OutgoingSocketThread( 5144): Now accepting connections...
,I/BluetoothClassifier( 6484): Bluetooth Device Name: A5-1
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2462 7e
,I/ActivityManager(  881): Killing 6262:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_6262/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=6545 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6312:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10005/pid_6312/cgroup.procs: No such file or directory
,W/bt-btif ( 5205): new conn_srvc id:26, app_id:255
W/bt-btif ( 5205): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 5205): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Incoming connection initialized (thread ID: 611)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Entering thread (ID: 611)
,W/ResourcesManager( 6545): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3119ab98:true
,I/ActivityManager(  881): Killing 6355:com.google.android.calendar/u0a49 (adj 15): empty #7
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): onBytesRead: Read 77 bytes successfully (thread ID: 611)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Got valid identity from [7C:F9:0E:37:96:AB 1449683858475.5462 7C:F9:0E:37:96:AB]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): onBytesWritten: 77 bytes successfully written (thread ID: 611)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): removeThreadFromList: Removing thread with ID 611
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Handshake thread disposed (thread ID: 611)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB 1449683858475.5462 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Exiting thread (ID: 611)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnected: [7C:F9:0E:37:96:AB 1449683858475.5462 7C:F9:0E:37:96:AB]
I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Incoming connection, peer ID: 7C:F9:0E:37:96:AB, name: 1449683858475.5462, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5144): hasConnection: We have an outgoing connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 5144): onConnected: Already connected with peer (ID: 7C:F9:0E:37:96:AB), continuing anyway...
I/io.jxcore.node.ConnectionHelper( 5144): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 5144): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 5144): Entering thread (ID: 612)
,E/io.jxcore.node.IncomingSocketThread( 5144): Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5144): java.net.ConnectException: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.IoBridge.connect(IoBridge.java:124)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:163)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.Socket.startupSocket(Socket.java:590)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.Socket.<init>(Socket.java:226)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at io.jxcore.node.IncomingSocketThread.run(IncomingSocketThread.java:49)
E/io.jxcore.node.IncomingSocketThread( 5144): Caused by: android.system.ErrnoException: connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.Posix.connect(Native Method)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.IoBridge.connectErrno(IoBridge.java:137)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.IoBridge.connect(IoBridge.java:122)
E/io.jxcore.node.IncomingSocketThread( 5144): 	... 5 more
W/io.jxcore.node.ConnectionHelper( 5144): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
I/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 612
I/io.jxcore.node.IncomingSocketThread( 5144): closeLocalSocketAndStreams: Nothing to close
I/io.jxcore.node.IncomingSocketThread( 5144): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.IncomingSocketThread( 5144): Exiting thread (ID: 612)
,W/bt-btif ( 5205): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
E/bt-btif ( 5205): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,W/libprocessgroup(  881): failed to open /acct/uid_10049/pid_6355/cgroup.procs: No such file or directory
,I/io.jxcore.node.ConnectionHelper( 5144): onListeningForIncomingConnections: Outgoing connection is using port 44211 (peer ID: 7C:F9:0E:37:96:AB)
,I/jxcore-log( 5144): ok 75 Should be able to connect without error
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): ok 76 Port should be within range
I/jxcore-log( 5144): 
,D/io.jxcore.node.ConnectionHelper( 5144): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
,I/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.IncomingSocketThread( 5144): close
I/io.jxcore.node.IncomingSocketThread( 5144): closeLocalSocketAndStreams: Nothing to close
I/io.jxcore.node.IncomingSocketThread( 5144): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 5144): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
,E/io.jxcore.node.IncomingSocketThread( 5144): Failed to create local streams: Socket closed
E/io.jxcore.node.IncomingSocketThread( 5144): java.net.SocketException: Socket closed
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:71)
W/io.jxcore.node.ConnectionHelper( 5144): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Failed to create local streams: Socket closed
E/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.IncomingSocketThread( 5144): Exiting thread (ID: 610)
,I/jxcore-log( 5144): ok 77 Should be able to disconnect without error
I/jxcore-log( 5144): 
I/jxcore-log( 5144): setting stopBroadcasting callback and ending test.
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): calling stopBroadcasting
I/jxcore-log( 5144): 
,I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
,D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): stopServiceDiscovery
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): remove channel information from framework
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
,D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 5269): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/wpa_supplicant( 5269): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/WifiP2pService(  881): InactiveState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
,D/WifiP2pService(  881): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
I/jxcore-log( 5144): stopBroadcasting returned undefined
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # ThaliEmitter can discover and connect to peers and then fail on double connect
I/jxcore-log( 5144): 
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683869320.5144
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683869320.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683869320.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683869320.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cdbed6e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cdbed6e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  881): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5144): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5144): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): connect: A5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 5144): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
I/jxcore-log( 5144): ok 78 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 614)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 5144): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5205): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): restart: Restarting...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): restart: Restarting...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
,W/bt-sdp  ( 5205): process_service_search_attr_rsp
,W/bt-btif ( 5205): new conn_srvc id:26, app_id:255
W/bt-btif ( 5205): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 5205): bta_dm_pm_ssr:2, lat:1200
,W/bt-btif ( 5205): new conn_srvc id:26, app_id:1
,W/bt-btif ( 5205): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 5205): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 5205): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Incoming connection initialized (thread ID: 615)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onSocketConnected: Authenticating next: [7C:F9:0E:37:96:AB 1449683858475.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 614)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): onBytesWritten: 77 bytes successfully written (thread ID: 616)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Outgoing connection initialized (*handshake* thread ID: 616)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Exiting thread (thread ID: 614)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Entering thread (ID: 615)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Entering thread (ID: 616)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): onBytesRead: Read 77 bytes successfully (thread ID: 615)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Got valid identity from [7C:F9:0E:37:96:AB 1449683868946.5462 7C:F9:0E:37:96:AB]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): onBytesRead: Read 77 bytes successfully (thread ID: 616)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Handshake succeeded with [7C:F9:0E:37:96:AB 1449683868946.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onAuthenticated: Fully connected: [7C:F9:0E:37:96:AB 1449683868946.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Exiting thread (ID: 616)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): onBytesWritten: 77 bytes successfully written (thread ID: 615)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): removeThreadFromList: Removing thread with ID 615
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Handshake thread disposed (thread ID: 615)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB 1449683868946.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Exiting thread (ID: 615)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnected: [7C:F9:0E:37:96:AB 1449683868946.5462 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnected: [7C:F9:0E:37:96:AB 1449683868946.5462 7C:F9:0E:37:96:AB]
I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Outgoing connection, peer ID: 7C:F9:0E:37:96:AB, name: 1449683868946.5462, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5144): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 5144): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 5144): onConnected: The total number of connections is now 1
I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Incoming connection, peer ID: 7C:F9:0E:37:96:AB, name: 1449683868946.5462, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5144): hasConnection: We have an outgoing connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 5144): onConnected: Already connected with peer (ID: 7C:F9:0E:37:96:AB), continuing anyway...
I/io.jxcore.node.ConnectionHelper( 5144): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 5144): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 5144): Entering thread (ID: 617)
D/io.jxcore.node.IncomingSocketThread( 5144): Server socket local port: 34285
I/io.jxcore.node.IncomingSocketThread( 5144): Now accepting connections...
,D/io.jxcore.node.IncomingSocketThread( 5144): Entering thread (ID: 618)
,E/io.jxcore.node.IncomingSocketThread( 5144): Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5144): java.net.ConnectException: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.IoBridge.connect(IoBridge.java:124)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:163)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.Socket.startupSocket(Socket.java:590)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.Socket.<init>(Socket.java:226)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at io.jxcore.node.IncomingSocketThread.run(IncomingSocketThread.java:49)
E/io.jxcore.node.IncomingSocketThread( 5144): Caused by: android.system.ErrnoException: connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.Posix.connect(Native Method)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.IoBridge.connectErrno(IoBridge.java:137)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.IoBridge.connect(IoBridge.java:122)
E/io.jxcore.node.IncomingSocketThread( 5144): 	... 5 more
W/io.jxcore.node.ConnectionHelper( 5144): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
I/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 618
I/io.jxcore.node.IncomingSocketThread( 5144): closeLocalSocketAndStreams: Nothing to close
I/io.jxcore.node.IncomingSocketThread( 5144): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.IncomingSocketThread( 5144): Exiting thread (ID: 618)
,W/bt-btif ( 5205): invalid rfc slot id: 21
,W/bt-btif ( 5205): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
E/bt-btif ( 5205): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,I/io.jxcore.node.ConnectionHelper( 5144): onListeningForIncomingConnections: Outgoing connection is using port 34285 (peer ID: 7C:F9:0E:37:96:AB)
,I/jxcore-log( 5144): ok 79 Should be able to connect without error
I/jxcore-log( 5144): 
I/jxcore-log( 5144): ok 80 Port should be within range
I/jxcore-log( 5144): 
,I/io.jxcore.node.ConnectionHelper( 5144): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5144): hasConnection: We have an outgoing connection with peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 5144): connect: We already have a connection to peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): connect: A5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 5144): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 619)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 5144): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5205): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 5205): process_service_search_attr_rsp
,W/bt-btif ( 5205): new conn_srvc id:26, app_id:1
W/bt-btif ( 5205): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 5205): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onSocketConnected: Authenticating next: [7C:F9:0E:37:96:AB 1449683858475.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 619)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): onBytesWritten: 77 bytes successfully written (thread ID: 620)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Outgoing connection initialized (*handshake* thread ID: 620)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Exiting thread (thread ID: 619)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Entering thread (ID: 620)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): onBytesRead: Read 77 bytes successfully (thread ID: 620)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Handshake succeeded with [7C:F9:0E:37:96:AB 1449683868946.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onAuthenticated: Fully connected: [7C:F9:0E:37:96:AB 1449683868946.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Exiting thread (ID: 620)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnected: [7C:F9:0E:37:96:AB 1449683868946.5462 7C:F9:0E:37:96:AB]
I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Outgoing connection, peer ID: 7C:F9:0E:37:96:AB, name: 1449683868946.5462, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5144): hasConnection: We have an outgoing connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 5144): onConnected: Already connected with peer (ID: 7C:F9:0E:37:96:AB), continuing anyway...
,I/io.jxcore.node.ConnectionHelper( 5144): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
,I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 5144): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 5144): Entering thread (ID: 621)
D/io.jxcore.node.OutgoingSocketThread( 5144): Server socket local port: 60655
I/io.jxcore.node.OutgoingSocketThread( 5144): Now accepting connections...
,W/bt-btif ( 5205): invalid rfc slot id: 23
,I/io.jxcore.node.ConnectionHelper( 5144): onListeningForIncomingConnections: Outgoing connection is using port 60655 (peer ID: 7C:F9:0E:37:96:AB)
I/jxcore-log( 5144): not ok 81 Should fail on double connect
I/jxcore-log( 5144): 
I/jxcore-log( 5144):   ---
I/jxcore-log( 5144): 
I/jxcore-log( 5144):     operator: ok
I/jxcore-log( 5144): 
I/jxcore-log( 5144):     expected: true
I/jxcore-log( 5144): 
I/jxcore-log( 5144):     actual:   null
I/jxcore-log( 5144): 
I/jxcore-log( 5144):   ...
I/jxcore-log( 5144): 
,D/io.jxcore.node.ConnectionHelper( 5144): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 5144): close
I/io.jxcore.node.OutgoingSocketThread( 5144): closeLocalSocketAndStreams: Nothing to close
I/io.jxcore.node.OutgoingSocketThread( 5144): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 5144): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 5144): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 5144): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 5144): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 5144): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 5144): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 5144): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 5144): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:71)
W/io.jxcore.node.ConnectionHelper( 5144): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Failed to create local streams: Socket closed
,D/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 5144): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
,I/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 5144): close
I/io.jxcore.node.OutgoingSocketThread( 5144): closeLocalSocketAndStreams: Nothing to close
I/io.jxcore.node.OutgoingSocketThread( 5144): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 5144): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 5144): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 5144): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 5144): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 5144): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 5144): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 5144): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 5144): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:71)
W/io.jxcore.node.ConnectionHelper( 5144): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Failed to create local streams: Socket closed
,D/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.OutgoingSocketThread( 5144): Exiting thread (ID: 617)
,E/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.OutgoingSocketThread( 5144): Exiting thread (ID: 621)
,I/jxcore-log( 5144): ok 82 Should be able to disconnect without error
I/jxcore-log( 5144): 
I/jxcore-log( 5144): setting stopBroadcasting callback and ending test.
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/wpa_supplicant( 5269): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-81
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/WifiP2pService(  881): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -81 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -81 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): startServiceDiscovery: Invalid state, try calling restart()
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 5205): new conn_srvc id:26, app_id:255
W/bt-btif ( 5205): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 5205): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Incoming connection initialized (thread ID: 622)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Entering thread (ID: 622)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): onBytesRead: Read 77 bytes successfully (thread ID: 622)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Got valid identity from [7C:F9:0E:37:96:AB 1449683868946.5462 7C:F9:0E:37:96:AB]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): onBytesWritten: 77 bytes successfully written (thread ID: 622)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): removeThreadFromList: Removing thread with ID 622
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Handshake thread disposed (thread ID: 622)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB 1449683868946.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Exiting thread (ID: 622)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnected: [7C:F9:0E:37:96:AB 1449683868946.5462 7C:F9:0E:37:96:AB]
I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Incoming connection, peer ID: 7C:F9:0E:37:96:AB, name: 1449683868946.5462, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5144): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
,I/io.jxcore.node.ConnectionHelper( 5144): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
,I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 5144): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 5144): Entering thread (ID: 623)
,E/io.jxcore.node.IncomingSocketThread( 5144): Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5144): java.net.ConnectException: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.IoBridge.connect(IoBridge.java:124)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:163)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.Socket.startupSocket(Socket.java:590)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.Socket.<init>(Socket.java:226)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at io.jxcore.node.IncomingSocketThread.run(IncomingSocketThread.java:49)
E/io.jxcore.node.IncomingSocketThread( 5144): Caused by: android.system.ErrnoException: connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.Posix.connect(Native Method)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.IoBridge.connectErrno(IoBridge.java:137)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.IoBridge.connect(IoBridge.java:122)
E/io.jxcore.node.IncomingSocketThread( 5144): 	... 5 more
W/io.jxcore.node.ConnectionHelper( 5144): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
I/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 623
I/io.jxcore.node.IncomingSocketThread( 5144): closeLocalSocketAndStreams: Nothing to close
I/io.jxcore.node.IncomingSocketThread( 5144): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.IncomingSocketThread( 5144): Exiting thread (ID: 623)
,W/bt-btif ( 5205): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
E/bt-btif ( 5205): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,I/jxcore-log( 5144): calling stopBroadcasting
I/jxcore-log( 5144): 
I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
,D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139298 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
,D/WifiP2pService(  881): remove client information from framework
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState clear service request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5269): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
,I/jxcore-log( 5144): stopBroadcasting returned undefined
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # ThaliEmitter can discover and connect to peers and then fail on double disconnect
I/jxcore-log( 5144): 
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683872967.5144
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683872967.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,D/btif_config_util( 5205): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683872967.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683872967.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cac47412 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cac47412 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  881): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5144): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5144): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): connect: A5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 5144): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
I/io.jxcore.node.ConnectionHelper( 5144): start: OK
I/jxcore-log( 5144): ok 83 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): restart: Restarting...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  881): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 625)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 5144): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/BTIF_SOCK( 5205): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
,W/bt-sdp  ( 5205): process_service_search_attr_rsp
,I/wpa_supplicant( 5269): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-84
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: 1 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Start timer timeout, starting now...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Cannot start, because not initialized
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  881): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,W/bt-btif ( 5205): new conn_srvc id:26, app_id:255
,W/bt-btif ( 5205): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 5205): bta_dm_pm_ssr:2, lat:1200
,W/bt-btif ( 5205): new conn_srvc id:26, app_id:1
,W/bt-btif ( 5205): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 5205): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 5205): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onSocketConnected: Authenticating next: [7C:F9:0E:37:96:AB 1449683858475.5462 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 625)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Incoming connection initialized (thread ID: 626)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): onBytesWritten: 77 bytes successfully written (thread ID: 627)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Outgoing connection initialized (*handshake* thread ID: 627)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Exiting thread (thread ID: 625)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Entering thread (ID: 627)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Entering thread (ID: 626)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): onBytesRead: Read 77 bytes successfully (thread ID: 627)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 5144): Handshake succeeded with [7C:F9:0E:37:96:AB 1449683873053.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onAuthenticated: Fully connected: [7C:F9:0E:37:96:AB 1449683873053.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Exiting thread (ID: 627)
,W/bt-btif ( 5205): invalid rfc slot id: 26
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): onBytesRead: Read 77 bytes successfully (thread ID: 626)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Got valid identity from [7C:F9:0E:37:96:AB 1449683873053.5462 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnected: [7C:F9:0E:37:96:AB 1449683873053.5462 7C:F9:0E:37:96:AB]
I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Outgoing connection, peer ID: 7C:F9:0E:37:96:AB, name: 1449683873053.5462, Bluetooth address: 7C:F9:0E:37:96:AB
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): onBytesWritten: 77 bytes successfully written (thread ID: 626)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): removeThreadFromList: Removing thread with ID 626
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Handshake thread disposed (thread ID: 626)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB 1449683873053.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 5144): Exiting thread (ID: 626)
,D/io.jxcore.node.ConnectionHelper( 5144): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 5144): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
,I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
,D/io.jxcore.node.ConnectionHelper( 5144): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnected: [7C:F9:0E:37:96:AB 1449683873053.5462 7C:F9:0E:37:96:AB]
I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Incoming connection, peer ID: 7C:F9:0E:37:96:AB, name: 1449683873053.5462, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5144): hasConnection: We have an outgoing connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 5144): onConnected: Already connected with peer (ID: 7C:F9:0E:37:96:AB), continuing anyway...
I/io.jxcore.node.ConnectionHelper( 5144): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
I/io.jxcore.node.ConnectionHelper( 5144): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 5144): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 5144): Entering thread (ID: 628)
D/io.jxcore.node.IncomingSocketThread( 5144): Server socket local port: 55498
I/io.jxcore.node.IncomingSocketThread( 5144): Now accepting connections...
,D/io.jxcore.node.IncomingSocketThread( 5144): Entering thread (ID: 629)
,E/io.jxcore.node.IncomingSocketThread( 5144): Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5144): java.net.ConnectException: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.IoBridge.connect(IoBridge.java:124)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:163)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.Socket.startupSocket(Socket.java:590)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.Socket.<init>(Socket.java:226)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at io.jxcore.node.IncomingSocketThread.run(IncomingSocketThread.java:49)
E/io.jxcore.node.IncomingSocketThread( 5144): Caused by: android.system.ErrnoException: connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.Posix.connect(Native Method)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.IoBridge.connectErrno(IoBridge.java:137)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.IoBridge.connect(IoBridge.java:122)
E/io.jxcore.node.IncomingSocketThread( 5144): 	... 5 more
W/io.jxcore.node.ConnectionHelper( 5144): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
I/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 629
I/io.jxcore.node.IncomingSocketThread( 5144): closeLocalSocketAndStreams: Nothing to close
I/io.jxcore.node.IncomingSocketThread( 5144): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.IncomingSocketThread( 5144): Exiting thread (ID: 629)
,W/bt-btif ( 5205): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
E/bt-btif ( 5205): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,I/io.jxcore.node.ConnectionHelper( 5144): onListeningForIncomingConnections: Outgoing connection is using port 55498 (peer ID: 7C:F9:0E:37:96:AB)
,I/jxcore-log( 5144): ok 84 Should be able to connect without error
I/jxcore-log( 5144): 
I/jxcore-log( 5144): ok 85 Port should be within range
I/jxcore-log( 5144): 
D/io.jxcore.node.ConnectionHelper( 5144): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.IncomingSocketThread( 5144): close
I/io.jxcore.node.IncomingSocketThread( 5144): closeLocalSocketAndStreams: Nothing to close
I/io.jxcore.node.IncomingSocketThread( 5144): closeBluetoothSocketAndStreams
,E/io.jxcore.node.IncomingSocketThread( 5144): Failed to create local streams: Socket closed
E/io.jxcore.node.IncomingSocketThread( 5144): java.net.SocketException: Socket closed
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.IncomingSocketThread( 5144): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:71)
W/io.jxcore.node.ConnectionHelper( 5144): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Failed to create local streams: Socket closed
,D/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 5144): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
,E/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
,D/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.IncomingSocketThread( 5144): Exiting thread (ID: 628)
,I/jxcore-log( 5144): ok 86 Should be able to disconnect without error
I/jxcore-log( 5144): 
D/io.jxcore.node.ConnectionHelper( 5144): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 5144): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 5144): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 5144): ok 87 Disconnect should fail 
I/jxcore-log( 5144): 
I/jxcore-log( 5144): setting stopBroadcasting callback and ending test.
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # setup
I/jxcore-log( 5144): 
,I/wpa_supplicant( 5269): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-84
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/WifiP2pService(  881): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
,D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: 1 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/WifiP2pService(  881): InactiveState{ when=0 what=139301 arg2=10 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139301 arg2=10 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service request
,D/WifiP2pManager( 5144): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service request added successfully
,I/jxcore-log( 5144): calling stopBroadcasting
I/jxcore-log( 5144): 
,I/io.jxcore.node.ConnectionHelper( 5144): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
,D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): stopServiceDiscovery
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): remove channel information from framework
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 5269): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/WifiP2pService(  881): InactiveState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
D/WifiP2pService(  881): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: NOT_INITIALIZED
,I/jxcore-log( 5144): stopBroadcasting returned undefined
I/jxcore-log( 5144): 
,I/jxcore-log( 5144): # ThaliEmitter handles socket disconnect correctly
I/jxcore-log( 5144): 
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 5144): # teardown
I/jxcore-log( 5144): 
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: 44:80:EB:7B:5A:05 1449683879896.5144
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5144): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1449683879896.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): start: {"pi":"44:80:EB:7B:5A:05","pn":"1449683879896.5144","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1449683879896.5144","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  881): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b7d6b902 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b7d6b902 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service
D/WifiP2pService(  881): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  881): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5144): start: OK
,I/jxcore-log( 5144): ok 88 Should be able to call startBroadcasting without error
I/jxcore-log( 5144): 
I/jxcore-log( 5144): echo server started
I/jxcore-log( 5144): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): restart: Restarting...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=139307 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): restart: Restarting...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
,D/WifiP2pService(  881): InactiveState{ when=0 what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState discover services
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Failed to start the service discovery, got error code: 3
,D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
,I/wpa_supplicant( 5269): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-84
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: 1 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): startServiceDiscovery: Invalid state, try calling restart()
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,E/bt-btm  ( 5205): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 5205): onReceive
,I/BTConnectionReceiver( 6484): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6484): Bluetooth Device Name: A5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): start: Starting peer discovery...
,D/WifiP2pService(  881): InactiveState{ when=0 what=139265 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139265 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  881): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 5269): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-84
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/WifiP2pService(  881): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
,D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: 1 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/WifiP2pService(  881): InactiveState{ when=0 what=139301 arg2=10 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139301 arg2=10 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState add service request
,D/WifiP2pManager( 5144): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service request added successfully
,I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
,D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/WifiP2pService(  881): InactiveState{ when=0 what=139310 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139310 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState discover services
,I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onServiceListChanged: Got empty list
,I/wpa_supplicant( 5269): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-84
I/wpa_supplicant( 5269): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: 3-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 128
D/WifiP2pService(  881):  grpcapab: 9
D/WifiP2pService(  881):  devcapab: 4
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -84 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  881):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  881):  primary type: 10-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 392
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 37
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  881):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  881):  primary type: 10-0050F204-5
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 392
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 37
D/WifiP2pService(  881):  status: 3
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  881): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"1449683879831.5462","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"1449683879831.5462","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"1449683879831.5462","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB 1449683879831.5462 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 5144): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: 1449683879831.5462, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: A5-1, Wi-Fi Direct address: 7e:f9:0e:37:96:ac
,I/io.jxcore.node.ConnectionHelper( 5144): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 5144): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
,D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
,D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
,D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2462 7e
,I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
,D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,I/wpa_supplicant( 5269): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
,D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,I/jxcore-log( 5144): Toggling radios to false
I/jxcore-log( 5144): 
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  881): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@cc6dad1 mBinding = false
,D/BluetoothManagerService(  881): Message: 2
,W/Settings( 1464): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  881): Sending off request.
,D/BluetoothAdapterState( 5205): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 5205): Setting state to 13
I/BluetoothAdapterState( 5205): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 5205): onBluetoothDisable()
,I/BluetoothAdapterState( 5205): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 5205): Scan Mode:20
,D/BluetoothAdapterState( 5205): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/BtOppRfcommListener( 5205): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 5205): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/BluetoothMapMasInstance( 5205): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 5205): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 5205): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
V/BluetoothMapMasInstance( 5205): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
V/BluetoothMapMasInstance( 5205): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
V/BluetoothMapMasInstance( 5205): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 5205): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 5205): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,W/bt-btif ( 5205): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 5205): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5205): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  881): Message: 60
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  881): Bluetooth State Change Intent: 12 -> 13
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/BluetoothMapService( 5205): onReceive
D/BluetoothMapService( 5205): STATE_TURNING_OFF
D/BluetoothMapService( 5205): MAP Service closeService in
D/BluetoothMapMasInstance( 5205): MAP Service shutdown
,I/BtOppRfcommListener( 5205): stopping Accept Thread
,I/BtOppRfcommListener( 5205): BluetoothSocket listen thread finished
,W/Settings( 1464): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:517)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:494)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:404)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): onServerStopped: Restarting the server...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5144): shutdown
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5144): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 5205): Socket listen failed: 2
E/BluetoothAdapterService(655543442)( 5205): Failed to create socket channel
,D/WifiService(  881): setWifiEnabled: false pid=5144, uid=10372
,E/WifiService(  881): Invoking mWifiStateMachine.setWifiEnabled
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Failed to create the socket listener thread: Error: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): java.io.IOException: Error: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): 	at android.bluetooth.BluetoothAdapter.createNewRfcommSocketAndRecord(BluetoothAdapter.java:1212)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): 	at android.bluetooth.BluetoothAdapter.listenUsingInsecureRfcommWithServiceRecord(BluetoothAdapter.java:1159)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.<init>(BluetoothServerThread.java:73)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector.startListeningForIncomingConnections(BluetoothConnector.java:135)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector.onServerStopped(BluetoothConnector.java:312)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:121)
,W/ContextImpl( 6545): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/AuthorizationBluetoothService( 1695): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/Settings( 1464): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/WifiStateMachine(  881): WifiStateMachine: Leaving Connected state
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
,E/WifiStateMachine(  881): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  881): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/Settings( 1464): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/jxcore-log( 5144): Radios toggled
I/jxcore-log( 5144): 
,E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  881): do suspend true
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onBluetoothAdapterScanModeChanged: Mode changed to 20
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onBluetoothAdapterScanModeChanged: Bluetooth disabled, stopping...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5144): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5144): stop: Stopping services
,D/WifiP2pService(  881): InactiveState{ when=0 what=139298 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139298 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState clear service
D/BluetoothManagerService(  881): Message: 30
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): stopServiceDiscovery
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: INITIALIZED
,I/io.jxcore.node.ConnectionHelper( 5144): onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
,D/CommandListener(  290): Clearing all IP addresses on wlan0
D/TCMD    (  479): NL - Read 60 bytes from update socket.
D/TCMD    (  479): NL - ignore NL message, type = 21
D/TCMD    (  479): Listening for incoming client connection request
D/WifiP2pService(  881): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): InactiveState{ when=0 what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState clear service request
D/WifiP2pService(  881): remove channel information from framework
D/WifiP2pService(  881): InactiveState{ when=-1ms what=139268 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5269): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
D/BluetoothManagerService(  881): Message: 30
I/wpa_supplicant( 5269): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 5269): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/WifiP2pService(  881): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): discovery change broadcast false
D/WifiP2pService(  881): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 1695): Read error: ssl=0xb88476f0: I/O error during system call, Connection timed out
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  881):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  881):  primary type: null
D/WifiP2pService(  881):  secondary type: null
D/WifiP2pService(  881):  wps: 0
D/WifiP2pService(  881):  grpcapab: 0
D/WifiP2pService(  881):  devcapab: 0
D/WifiP2pService(  881):  status: 4
D/WifiP2pService(  881):  wfdInfo: null
D/WifiP2pService(  881):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 1695): SSL shutdown failed: ssl=0xb88476f0: I/O error during system call, Broken pipe
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5144): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Peer discovery stopped successfully
,D/ConnectivityService(  881): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
,D/LocalBluetoothProfileManager( 6545): Adding local MAP profile
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/BluetoothMap( 6545): Create BluetoothMap proxy object
,D/BluetoothManagerService(  881): Message: 30
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info<unknown ssid>
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6641 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 5205): ag scb idx 1 not allocated
E/bt-btif ( 5205): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 5205): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5205): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5205): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5205): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5205): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5205): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_userial_mct( 5205): exiting userial_read_thread
D/bt_userial_mct( 5205): Leaving userial_evt_read_thread()
D/bt_userial_mct( 5205): userial_close_reader Joined userial reader thread: 0
I/bt_hwcfg( 5205): hw_epilog_process
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/bt_userial_mct( 5205): userial_close
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BluetoothManagerService(  881): Message: 30
,D/LocalBluetoothProfileManager( 6545): LocalBluetoothProfileManager construction complete
,D/WifiMetrics(  881): connected time updated 171644
,D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 5269): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  881): Unexpected BatchedScanResults :null
E/wpa_supplicant( 5269): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  881): [1,449,683,892,181 ms] noteScanEnd no scan source
D/WifiP2pService(  881): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pDisablingState
,D/WifiP2pService(  881): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): p2p socket connection lost
D/WifiP2pService(  881): P2pDisabledState
,D/WifiScanningService(  881): SCAN_AVAILABLE : 1
D/RttService(  881): SCAN_AVAILABLE : 1
D/WifiScanningService(  881): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  881): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5144): onWifiStateChanged: State changed to 1
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/DockEventReceiver( 6545): finishStartingService: stopping service
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  881): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - enter - invokeEnterMethods
D/BluetoothInputDevice( 6545): Proxy object connected
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/HidProfile( 6545): Bluetooth service connected
,D/BluetoothPan( 6545): BluetoothPAN Proxy object connected
,D/PanProfile( 6545): Bluetooth service connected
D/BluetoothMap( 6545): Proxy object connected
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/MapProfile( 6545): Bluetooth service connected
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/BluetoothMap( 6545): getConnectedDevices()
D/BluetoothMap( 6545): Bluetooth is Not enabled
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  881): do suspend true
,W/ResourcesManager( 6641): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/WifiP2pService(  881): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/Checkin ( 2914): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2914): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/bt_hwcfg( 5205): Starting hciattach daemon
I/bt_hwcfg( 5205): try to set false
I/bt_vendor( 5205): cleanup
,I/GKI_LINUX( 5205): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 5205): GKI_exit_task 0 done
I/GKI_LINUX( 5205): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 5205): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 5205): mProfilesStarted : true supportedProfileServices.length : 7
D/HeadsetService( 5205): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 5205): quit
,D/BluetoothAdapterState( 5205): Stopping profile services that were post enabled
,D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,D/HeadsetStateMachine( 5205): Exit Disconnected: -1
D/BluetoothHeadset(  881): Proxy object disconnected
,D/AudioService(  881): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1502): Proxy object disconnected
D/BluetoothHeadset( 1502): Proxy object disconnected
,D/BluetoothHeadset( 1538): Proxy object disconnected
D/A2dpService( 5205): Received stop request...Stopping profile...
,D/A2dpStateMachine( 5205): Exit Disconnected: -1
,D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,D/BluetoothA2dp(  881): Proxy object disconnected
D/AudioService(  881): onServiceDisconnected: Bluetooth profile: 2
,D/HidService( 5205): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,D/BluetoothInputDevice( 6545): Proxy object disconnected
D/HidProfile( 6545): Bluetooth service disconnected
D/HealthService( 5205): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,D/PanService( 5205): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
D/BtGatt.DebugUtils( 5205): handleDebugAction() action=null
D/BluetoothPan( 6545): BluetoothPAN Proxy object disconnected
D/PanProfile( 6545): Bluetooth service disconnected
,D/BtGatt.GattService( 5205): Received stop request...Stopping profile...
D/BtGatt.GattService( 5205): stop()
D/BtGatt.AdvertiseManager( 5205): advertise clients cleared
,D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,D/BluetoothMapService( 5205): Received stop request...Stopping profile...
,D/BluetoothMapService( 5205): stop()
D/BluetoothMapEmailAppObserver( 5205): deinitObservers()
D/BluetoothMapEmailAppObserver( 5205): removeReceiver()
D/BluetoothAdapterService( 5205): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
D/BluetoothMap( 6545): Proxy object disconnected
,D/MapProfile( 6545): Bluetooth service disconnected
D/HeadsetStateMachine( 5205): Unbinding service...
W/BluetoothHeadsetServiceJni( 5205): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 5205): Cleaning up Bluetooth Handsfree callback object
I/GKI_LINUX( 5205): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 5205): GKI_exit_task 2 done
I/GKI_LINUX( 5205): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 5205): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 5205): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5205): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 5205): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 5205): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 5205): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5205): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 5205): MAP Service closeService in
D/BluetoothMapService( 5205): cleanup()
D/BluetoothMapService( 5205): MAP Service closeService in
D/BluetoothAdapterState( 5205): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 5205): Setting state to 10
I/BluetoothAdapterState( 5205): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  881): Message: 60
D/BluetoothManagerService(  881): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService(  881): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothA2dp(  881): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 5205): Entering OffState
D/BluetoothPbap( 6545): onBluetoothStateChange: up=false
D/BluetoothMap( 6545): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1502): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1502): onBluetoothStateChange: up=false
,D/BluetoothPan( 6545): onBluetoothStateChange on: false
D/BluetoothHeadset(  881): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1538): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 6545): onBluetoothStateChange: up=false
D/BluetoothManagerService(  881): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  881): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService(  881): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@cc6dad1 mBinding = false
,D/BluetoothManagerService(  881): Sending unbind request.
,D/BluetoothManagerService(  881): Bluetooth State Change Intent: 13 -> 10
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,I/GKI_LINUX( 5205): gki_task task_id=1 [BTIF] terminating
,D/ConnectivityService(  881): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/Nat464Xlat(  881): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  881): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  881): stopping supplicant
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  881): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/BluetoothAdapter( 1291): 621119601: getState() :  mService = null. Returning STATE_OFF
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Disconnected - quitting
E/WifiStateMachine(  881): setWifiState: disabling
,D/BluetoothAdapter( 1291): 621119601: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1291): 621119601: getState() :  mService = null. Returning STATE_OFF
D/ConnectivityManager.CallbackHandler( 1941): CM callback handler got msg 524292
,E/ConnectivityService(  881): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1521): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1521): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/GKI_LINUX( 5205): GKI_exit_task 1 done
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/GKI_LINUX( 5205): GKI_shutdown(): task [BTIF] terminated
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/BluetoothServiceJni( 5205): cleanupNative: return from cleanup
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/BluetoothAdapter( 1695): 929716277: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1695): 929716277: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1695): 929716277: getState() :  mService = null. Returning STATE_OFF
E/BluetoothDevice( 1695): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1695): BT not enabled. Cannot get Remote Device name
E/BluetoothDevice( 1695): BT not enabled. Cannot get Remote Device Alias
E/BluetoothDevice( 1695): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1695): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1695): BT not enabled. Cannot get Remote Device name
E/BluetoothDevice( 1695): BT not enabled. Cannot get Remote Device Alias
,I/art     ( 5205): System.exit called, status: 0
I/AndroidRuntime( 5205): VM exiting with result code 0, cleanup skipped.
,I/wpa_supplicant( 5269): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292):  STA Disconnected !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  479): NL - Read 1004 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
,D/TCMD    (  479): Listening for incoming client connection request
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
D/TCMD    (  479): NL - Read 1004 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 68 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 68 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,I/MDMCTBK (  292): send SAR ctrl over QMI
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
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
,I/wpa_supplicant( 5269): eap_proxy Deinitialzed
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 0
,D/TCMD    (  479): NL - Read 1004 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,I/wpa_supplicant( 5269): wlan0: CTRL-EVENT-TERMINATING 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  292): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  292):  Wpa Supplicant Exiting !!
D/MDMCTBK (  292): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  292): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  292): wifi_close_sockets: Exit
,E/WifiStateMachine(  881): Supplicant connection lost
,I/ActivityManager(  881): Process com.android.bluetooth (pid 5205) has died
,E/QC-QMI  (  441): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  441): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  441): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
E/QC-QMI  (  441): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
,E/QC-QMI  (  441): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,I/Babel_SMS( 6641): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6641): MmsConfig.loadMmsSettings
I/Babel_SMS( 6641): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6641): MmsConfig.loadFromDatabase
,E/WifiStateMachine(  881): setWifiState: disabled
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 1695): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel_SMS( 6641): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6641): MmsConfig.loadFromResources
,E/Babel_SMS( 6641): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6641): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6641): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6641): startup - clean
,I/Babel   ( 6641): deleted: false for 0
,W/ContextImpl( 6545): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/VideoCapabilities( 6641): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6641): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6641): Unsupported mime video/mpeg2
,I/ActivityManager(  881): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6686 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
D/DockEventReceiver( 6545): finishStartingService: stopping service
,W/ResourcesManager( 6686): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/VideoCapabilities( 6641): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6641): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6641): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6641): Unrecognized profile 2130706433 for video/avc
,D/AdapterServiceConfig( 6686): Adding HeadsetService
,D/AdapterServiceConfig( 6686): Adding A2dpService
,D/AdapterServiceConfig( 6686): Adding HidService
D/AdapterServiceConfig( 6686): Adding HealthService
D/AdapterServiceConfig( 6686): Adding PanService
D/AdapterServiceConfig( 6686): Adding GattService
D/AdapterServiceConfig( 6686): Adding BluetoothMapService
W/VideoCapabilities( 6641): Unrecognized profile 2130706433 for video/avc
,D/Checkin ( 2914): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/AuthorizationBluetoothService( 1695): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  881): Killing 1941:com.google.android.gms/u0a16 (adj 15): empty #7
D/Checkin ( 2914): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/ConnectivityService(  881): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@15697617)
D/WifiService(  881): Client connection lost with reason: 4
D/ConnectivityService(  881): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  881): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TCMD    (  479): NL - Read 444 bytes from update socket.
D/TCMD    (  479): NL - ignore NL message, type = 17
D/TCMD    (  479): Listening for incoming client connection request
,D/Checkin ( 2914): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  479): NL - Read 1004 bytes from update socket.
,D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,V/AlarmManager(  881): send {1ef76342, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {2cac7a04, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_1941/cgroup.procs: No such file or directory
,I/vclib   ( 6641): onServiceConnected
W/Babel   ( 6641): Attempted to change video mute state without an active call.
,V/AlarmManager(  881): done {2cac7a04, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [181ms]
,V/AlarmManager(  881): done {1ef76342, *alarm*:android.intent.action.TIME_TICK} [214ms]
,D/TCMD    (  479): NL - Read 444 bytes from update socket.
D/TCMD    (  479): NL - ignore NL message, type = 17
D/TCMD    (  479): Listening for incoming client connection request
,D/Checkin ( 2914): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  292): NetlinkHandler, wifiStateChanged 0
,I/MDMCTBK (  292): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1464): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2518): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2518): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2518): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/OtaApp  ( 2518): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6717 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1464): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1464): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2518): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2518): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2518): Registering with Alarm Manager to restart CCE
,D/PollingManager( 2518): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2518): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2518): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2518): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2518): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2518): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2518): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2518): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2518): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2518): [debug] > CusSM.onRadioDown
,I/MusicStore( 6717): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6717): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6717): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6717): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6717): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6717): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6717): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6717): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6717): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6717): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6717): GMSCore installation verified
,I/ConfigStore( 6717): Config Database version: 1
,I/MediaRouter( 6717): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6717): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/art     (  881): Explicit concurrent mark sweep GC freed 37738(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.656ms total 126.741ms
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6758 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 24.200ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 318us total 20.941ms
,I/GHttpClientFactory( 6717): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6717): Using platform SSLCertificateSocketFactory
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 32.184ms
,V/Mms     ( 6758): mnc/mcc: 
V/Mms     ( 6758): tag: int value: recipientLimit - 20
,V/Mms     ( 6758): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6758): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6758): tag: int value: maxSubjectLength - 80
V/Mms     ( 6758): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6758): tag: bool value: enableGroupMms - false
V/Mms     ( 6758):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  881): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=6789 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6522:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10019/pid_6522/cgroup.procs: No such file or directory
,W/ResourcesManager( 6789): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6789): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6758): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MultiDex( 6789): VM with version 2.1.0 has multidex support
I/MultiDex( 6789): install
I/MultiDex( 6789): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6811 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6484:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_6484/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6811): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6811): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6811): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 6545:com.android.settings/1000 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_1000/pid_6545/cgroup.procs: No such file or directory
,V/JNIHelp ( 6789): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6789): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6789): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@534c195: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6789): Installed default security provider GmsCore_OpenSSL
,I/iu.SyncManager( 6789): SYNC; picasa accounts
,D/NetworkLogImpl( 6789): Loaded NetworkSpeedPredictor
,I/ActivityManager(  881): Killing 6686:com.android.bluetooth/1002 (adj 15): empty #7
,D/NativeLibraryUtils( 6789): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  881): failed to open /acct/uid_1002/pid_6686/cgroup.procs: No such file or directory
,D/WifiP2pService(  881): P2pDisabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6845 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6866 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 6641): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  881): Killing 6717:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/ActivityManager(  881): Waited long enough for: ServiceRecord{d2d5f8 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6717/cgroup.procs: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6866): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6866): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6866): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6866):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6866):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6866): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6866): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6866): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6866): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6866): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6866): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6866): Time to load native libraries: 1 ms (timestamps 2320-2321)
,I/LibraryLoader( 6866): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6866): Binding Chromium to main looper Looper (main, tid 1) {38f40ea1}
I/LibraryLoader( 6866): Expected native library version number "",actual native library version number ""
I/chromium( 6866): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6866): Initializing chromium process, singleProcess=true
,W/art     ( 6866): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6866): ApplicationContext is null in ApplicationStatus
,W/chromium( 6866): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6866): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6866): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6866): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6866): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6866): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6866): Local Branch: 
I/Adreno-EGL( 6866): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6866): Local Patches: NONE
I/Adreno-EGL( 6866): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6866): Requires BLUETOOTH permission
,I/NSApplication( 6866): Starting up...
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6922 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6758:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_6758/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6941 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6811:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_6811/cgroup.procs: No such file or directory
,W/ResourcesManager( 6941): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6961 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6641:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ActivityManager(  881): Killing 6845:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 6961): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6641/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2518): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_6845/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2518): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2518): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2518): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2518): onServiceConnected()
,D/GetNotificationsWS( 2518): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2518): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6991 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6991): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6991): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6991): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6991): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6991): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6991): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6991): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6991): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6991): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6991): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6991): GMSCore installation verified
,I/ConfigStore( 6991): Config Database version: 1
,I/MediaRouter( 6991): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6991): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7022 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6991): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6991): Using platform SSLCertificateSocketFactory
,I/art     (  881): Explicit concurrent mark sweep GC freed 13178(686KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.566ms total 117.785ms
,I/ActivityManager(  881): Killing 6866:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_6866/cgroup.procs: No such file or directory
,V/Mms     ( 7022): mnc/mcc: 
V/Mms     ( 7022): tag: int value: recipientLimit - 20
,V/Mms     ( 7022): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7022): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7022): tag: int value: maxSubjectLength - 80
,V/Mms     ( 7022): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7022): tag: bool value: enableGroupMms - false
V/Mms     ( 7022):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7022): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7048 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6922:com.android.chrome/u0a52 (adj 15): empty #7
,D/PhoneMonitor( 7048): Register our PhoneStateListener
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_6922/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7048): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7048): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 6941:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6941/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7066 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 24.743ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 22.006ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.407ms
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7083 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6961:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_6961/cgroup.procs: No such file or directory
,W/ResourcesManager( 7083): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7083): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7083): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7083): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7083): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7083): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7083): MmsConfig.loadFromResources
,E/Babel_SMS( 7083): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7083): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7083): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7083): startup - clean
,I/Babel   ( 7083): deleted: false for 0
,W/art     ( 7083): Suspending all threads took: 9.104ms
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7118 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7083): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7083): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7083): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7083): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7083): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7083): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7083): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7083): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7118): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/vclib   ( 7083): onServiceConnected
,W/Babel   ( 7083): Attempted to change video mute state without an active call.
,I/Babel   ( 7083): connection state changed from UNKNOWN to DISCONNECTED
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7118): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7118): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7118):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7118):   adb logcat -s GAv4
,I/ActivityManager(  881): Killing 6991:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7118): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7118): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6991/cgroup.procs: No such file or directory
,W/GAv4    ( 7118): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7118): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7118): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7118): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7118): Time to load native libraries: 2 ms (timestamps 5570-5572)
,I/LibraryLoader( 7118): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7118): Binding Chromium to main looper Looper (main, tid 1) {38f40ea1}
,I/LibraryLoader( 7118): Expected native library version number "",actual native library version number ""
I/chromium( 7118): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7118): Initializing chromium process, singleProcess=true
,W/art     ( 7118): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7118): ApplicationContext is null in ApplicationStatus
,W/chromium( 7118): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7118): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7118): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7118): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7118): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7118): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7118): Local Branch: 
I/Adreno-EGL( 7118): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7118): Local Patches: NONE
I/Adreno-EGL( 7118): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7118): Requires BLUETOOTH permission
I/NSApplication( 7118): Starting up...
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7184 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 7022:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_7022/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7203 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7048:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7048/cgroup.procs: No such file or directory
,W/ResourcesManager( 7203): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7223 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7083:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 7223): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  881): Killing 7066:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7066/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7083/cgroup.procs: No such file or directory
,D/WearableService( 1695): callingUid 10016, callindPid: 1695
,E/MDM     ( 1695): [177] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6789): Restart initialization of location
,D/AuthorizationBluetoothService( 1695): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7253 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6789): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6789): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,W/GCoreFlp( 1695): No location to return for getLastLocation()
,W/FusedLocationProvider( 1695): location=null
,W/IcingInternalCorpora( 6789): getNumBytesRead when not calculated.
,I/MDMCTBK (  292): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  292): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
,E/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
,I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ActivityManager(  881): Killing 7118:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_7118/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): Got discovery timeout, restarting...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5144): restart: Cannot restart, because not initialized
,I/MDMCTBK (  292): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  292): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  292): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  292): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,W/SQLiteConnectionPool( 6789): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311018, SEQNUM=4509, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-1201, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,D/ConnectivityService(  881): Failed to find a new network - expiring NetTransition Wakelock
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  881): send {1ef76342, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {719acb1, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  881): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7302 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 7302): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7302):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7302):   adb logcat -s GAv4
,W/GAv4    ( 7302): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  881): done {1ef76342, *alarm*:android.intent.action.TIME_TICK} [173ms]
,W/GAv4    ( 7302): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7302): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  881): Explicit concurrent mark sweep GC freed 11427(556KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.414ms total 119.354ms
,V/AlarmManager(  881): done {719acb1, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [323ms]
I/ActivityManager(  881): Killing 7184:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_7184/cgroup.procs: No such file or directory
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
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309712, SEQNUM=4517, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-1672, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
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
,V/AlarmManager(  881): send {1ef76342, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {23e4d3d2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  881): done {23e4d3d2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [12ms]
,V/AlarmManager(  881): done {1ef76342, *alarm*:android.intent.action.TIME_TICK} [49ms]
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
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310807, SEQNUM=4518, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-2469, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,I/UsageStatsService(  881): User[0] Flushing usage stats to disk
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
,V/AlarmManager(  881): send {1ef76342, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {1a72a596, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  881): done {1a72a596, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [26ms]
,V/AlarmManager(  881): done {1ef76342, *alarm*:android.intent.action.TIME_TICK} [42ms]
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
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310781, SEQNUM=4521, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-52, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {1ef76342, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {23e4d3d2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  881): done {23e4d3d2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [11ms]
,V/AlarmManager(  881): done {1ef76342, *alarm*:android.intent.action.TIME_TICK} [50ms]
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
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309306, SEQNUM=4522, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=-27, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7364): 
D/AndroidRuntime( 7364): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7364): CheckJNI is OFF
D/AndroidRuntime( 7364): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10372 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 5144:com.test.thalitest/u0a372 (adj 9): stop com.test.thalitest
I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
W/PackageSettings(  881): Skipping PackageSetting{f36067b com.example.hello/10359} due to missing metadata
I/WindowState(  881): WIN DEATH: Window{36dda1c5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  881): Client connection lost with reason: 4
I/ActivityManager(  881):   Force finishing activity ActivityRecord{3f36e26b u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  881): Spurious death for ProcessRecord{196a3d04 5144:com.test.thalitest/u0a372}, curProc for 5144: null
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10372 user=0: pkg removed
I/ActivityManager(  881):   Force finishing activity ActivityRecord{3f36e26b u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  881): Duplicate finish request for ActivityRecord{3f36e26b u0 com.test.thalitest/.MainActivity t3 f}
I/art     ( 2914): Explicit concurrent mark sweep GC freed 16043(2MB) AllocSpace objects, 30(480KB) LOS objects, 40% free, 7MB/12MB, paused 669us total 44.118ms
I/ProcessStatsService(  881): Prepared write state in 14ms
I/art     ( 1557): Explicit concurrent mark sweep GC freed 7696(550KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 491us total 82.331ms
I/ProcessStatsService(  881): Prepared write state in 9ms
W/GeofencerStateMachine( 1695): Ignoring removeGeofence because network location is disabled.
I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1405): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1405): run()
I/Decoder ( 1405): createOrResetDecoder
I/art     (  881): Explicit concurrent mark sweep GC freed 11416(950KB) AllocSpace objects, 10(213KB) LOS objects, 33% free, 20MB/30MB, paused 2.681ms total 172.185ms
I/art     (  881): WaitForGcToComplete blocked for 107.091ms for cause Explicit
D/VoicemailCleanupService( 7223): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7392 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ConfigService( 1695): onCreate
W/asset   ( 7392): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7392): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7392): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7392): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1405): run()
D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  881): removeObsoleteFile: deleting file=3_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1405): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = contacts
I/ProcessStatsService(  881): Pruning old procstats: /data/system/procstats/state-2015-12-09-06-39-04.bin
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = user
I/art     (  881): Explicit concurrent mark sweep GC freed 4047(208KB) AllocSpace objects, 1(49KB) LOS objects, 33% free, 20MB/30MB, paused 1.850ms total 183.685ms
I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7418 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1405): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1405): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1405): run()
I/StatsUtilsManager( 1405): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1405): shouldRecordStats() = Too Soon
I/ActivityManager(  881): Killing 7203:com.google.android.apps.plus/u0a90 (adj 15): empty #7
W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7203/cgroup.procs: No such file or directory
D/AndroidRuntime( 7364): Shutting down VM
W/ContextImpl( 7418): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 6789): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 6789): Reading stored module config
D/AccountUtils( 6789): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 6789): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6789): Loading module APK com.google.android.play.games
I/Launcher( 1557): Deferring update until onResume
I/LocationSettingsChecker( 6789): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 6789): App measurement is starting up, version: 8489
I/GMPM-SVC( 6789): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1695): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1695): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 6789): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6789): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6789): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6789): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6789): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6789): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 6789): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 6789): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6789): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6789): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6789): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6789): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6789): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7448 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
V/AlarmManager(  881): send {1ef76342, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {16a34d60, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  881): send {ab8589, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
V/AlarmManager(  881): send {1cadc98e, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
W/BaseAppContext( 6789): Using Auth Proxy for data requests.
D/ChimeraCfgMgr( 6789): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6789): Module APK com.google.android.play.games already loaded
W/Launcher( 1557): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
I/Icing   ( 6789): Storage manager: low false usage 1.72MB avail 3.19GB capacity 4.85GB
I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7485 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 20.409ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 18.862ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 21.279ms
E/BaseAppContext( 6789): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 6789): Using Auth Proxy for data requests.
W/BaseAppContext( 6789): Using Auth Proxy for data requests.
W/BaseAppContext( 6789): Using Auth Proxy for data requests.
D/ConnectivityService(  881): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/BaseAppContext( 6789): Using Auth Proxy for data requests.
W/BaseAppContext( 6789): Using Auth Proxy for data requests.
W/BaseAppContext( 6789): Using Auth Proxy for data requests.
W/BaseAppContext( 6789): Using Auth Proxy for data requests.
W/DriveInitializer( 6789): Awaiting to be initialized
W/DriveInitializer( 6789): Background init thread started
V/AlarmManager(  881): done {1ef76342, *alarm*:android.intent.action.TIME_TICK} [430ms]
I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7524 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 7448): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6789): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
I/ActivityManager(  881): Killing 7253:com.google.android.apps.photos/u0a88 (adj 15): empty #7
I/PeopleDatabaseHelper( 6789): cleanUpNonGplusAccounts done.
W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7253/cgroup.procs: No such file or directory
W/DriveInitializer( 6789): Background init thread ended
I/art     ( 5041): Explicit concurrent mark sweep GC freed 2341(89KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 430us total 32.331ms
I/GAv4    ( 7485): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7485):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7485):   adb logcat -s GAv4
W/GAv4    ( 7485): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/SQLiteDatabase( 1695): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 1695): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1695): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1695): 	at com.google.android.gms.playlog.store.r.d(SourceFile:97)
E/SQLiteDatabase( 1695): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:155)
E/SQLiteDatabase( 1695): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/SQLiteDatabase( 1695): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1695): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1695): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1695): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 1695): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 1695): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearcutLoggerIntentService( 1695): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearcutLoggerIntentService( 1695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 1695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 1695): 	at com.google.android.gms.playlog.store.r.d(SourceFile:97)
E/ClearcutLoggerIntentService( 1695): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:155)
E/ClearcutLoggerIntentService( 1695): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearcutLoggerIntentService( 1695): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1695): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1695): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearcutLoggerIntentService( 1695): 	at java.lang.Thread.run(Thread.java:818)
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
E/SQLiteDatabase( 1695): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 1695): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1695): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1695): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1695): 	at com.google.android.gms.playlog.store.r.d(SourceFile:97)
E/SQLiteDatabase( 1695): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:155)
E/SQLiteDatabase( 1695): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/SQLiteDatabase( 1695): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1695): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1695): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1695): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 1695): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 1695): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearcutLoggerIntentService( 1695): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearcutLoggerIntentService( 1695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 1695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 1695): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 1695): 	at com.google.android.gms.playlog.store.r.d(SourceFile:97)
E/ClearcutLoggerIntentService( 1695): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:155)
E/ClearcutLoggerIntentService( 1695): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearcutLoggerIntentService( 1695): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1695): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1695): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearcutLoggerIntentService( 1695): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 7485): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak

```
